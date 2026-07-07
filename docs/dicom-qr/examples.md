# Examples

## List studies for patient IDs listed in a CSV file.

### `example.csv`
```csv
pat_id
4165299
3870658
0000007
```

### `example_1.py`
```python
# /// script
# requires-python = ">=3.11"
# dependencies = [
#     "dicom-qr",
#     "typer"
# ]
# ///
import csv

import typer

import dicom_qr.logger
import dicom_qr.query
import dicom_qr.search
import dicom_qr.settings

dicom_qr.logger.ENABLE_FILE_LOGGING = False


def main(csv_file: str = typer.Argument(..., help='CSV file with patient IDs.')) -> None:
    dicom_qr.logger.setup_logging()

    with open(csv_file, encoding='utf-8') as fp:
        patient_ids = [row['pat_id'] for row in csv.DictReader(fp)]

    print('PatientID,StudyDate,StudyDescription AccesionNumber')  # noqa:T201
    for patient_id in patient_ids:
        with dicom_qr.query.get_query(dicom_qr.settings.get_settings()) as query:
            studies = query.get_studies(dicom_qr.search.SearchTerms(patid=patient_id))

            if len(studies) == 0:
                print(f'{patient_id},,,')  # noqa:T201
                continue

            for study in studies:
                print(f'{study.PatientID},{study.StudyDate},{study.StudyDescription},{study.AccessionNumber}')  # noqa:T201


if __name__ == "__main__":
    typer.run(main)
```

```shell
uv run example_1.py example.csv
```