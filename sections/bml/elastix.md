This project is funded by the Chan Zuckerberg Initiative DAF, grant numbers 2020-21851 and 2021-237461
August 2020 – August 2023

Principal investigator from LUMC: dr. Marius Staring

Image registration is the task of finding the spatial relationship between two or more images, and is abundantly used in biomedical image processing. The applicants have previously developed an open source tool for performing image registration, dubbed elastix. While being one of the most popular image registration toolboxes, efforts are needed to sustain the software, anchor code quality more deeply in the development process, and better connect to users and the other software they use. Firstly, an important trend among researchers is the increased use of Python in the science community at large but also Java in e.g. the biology community, and secondary tools such as elastix should therefore be natively available in such languages as well. While rudimentary wrappings to such scripting languages are currently available [5, 6], much of the cumbersome build process is delegated to users, and the user interface requires more functionality. We observe that elastix is increasingly integrated in other packages, workflows and software (see for a list below), which mandates a much higher state of interoperability of elastix than is currently available. Secondly, the software base requires modernization (development started in 2003), performance improvements, and better unit testing. Thirdly, the majority of elastix users are not registration experts, and currently much of the getting started advice depends on the availability of a static manual: much more can be done to facilitate the ease of use of our software. In
this software development project we target these three issues.

The project results can be found at:
- elastix: https://github.com/SuperElastix/elastix
- python elastix: https://github.com/InsightSoftwareConsortium/ITKElastix
- PyPi: https://pypi.org/project/itk-elastix/
- Model Zoo: https://elastix.lumc.nl/modelzoo/

## Associated researchers
- Niels Dekker
- Stefan Klein (Erasmus MC)
- Matt McCormick (Kitware)
- Marius Staring
- Viktor van der Valk
- Dzenan Zukic (Kitware)