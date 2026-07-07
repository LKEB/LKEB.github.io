
This needs a settings.json file with the following data:
```json
{
  "dimse" : {
    "server_ae_title": "SOMETHING",
    "server_ae_ip": "SOMETHING",
    "server_ae_port": SOMETHING,
    "client_ae_title": "SOMETHING",
    "client_ae_port": SOMETHING,
    "transfer_method": "move"  // or 'get'
  },
  // "dicom_web" : {
  //   "url":"http://localhost:7180/dicom-web",
  //   "username": "SOMETHING",
  //   "password": "SOMETHING"
  //},
  "base_folder": "dumpdir",
  "folder_template": "${PatientID}/${StudyDate}/${StudyDescription}/${Modality}/${FolderUID}_${SeriesDescription}",
  "study_columns": [
    {"name": "Index"},
    {"name": "PatientName"}, 
    {"name": "PatientID", "no_wrap":  true},
    {"name": "PatientSex", "justify": "right"},
    {"name": "StudyDate", "no_wrap":  true},
    {"name": "ModalitiesInStudy"},
    {"name": "AccessionNumber"},
    {"name": "StudyDescription", "justify": "left"},
    {"name": "StudyInstanceUID", "justify": "left", "no_wrap":  true}
  ],
  "series_columns": [
    {"name": "Index"},
    {"name": "SeriesInstanceUID", "justify": "left", "no_wrap":  true},
    {"name": "Modality"},
    {"name": "SeriesNumber"},
    {"name": "SeriesDescription", "justify": "left"}
  ]
}
```
DICOM-Web is also supported, use the 'dicom-web' section of the config instead of the 'dimse' section.
Search strategy for settings file:

1. *'DICOM_QR_SETTINGS'* environment value
2. *'settings.json'* in current directory
3. *'~/.config/dicom_qr/settings.json'*

# Template
Folder template can contain any of the following items:

- PatientName
- PatientID
- StudyDescription
- StudyDate
- StudyTime
- Modality
- SeriesDescription
- SeriesNumber
- SeriesInstanceUID
- FolderUID _(Uses the uid_mapping provided to RetrievePacs class)_
- StudyInstanceUID
- AccessionNumber

# study columns:
### names:
 - StudyInstanceUID
 - PatientID
 - PatientName
 - PatientSex
 - PatientBirthDate
 - StudyID
 - StudyDate
 - StudyDescription
 - StudyTime
 - AccessionNumber

### justify
 - default
 - left
 - center
 - right
 - full

### no_wrap
 - true
 - false