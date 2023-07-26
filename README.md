# Clinical Patient Pathway Map

## Introduction
This script demonstrates a visualisation for the process map that Alzheimer's patients take through the hospital system from the decision to refer to service to discharge.

## Methods
This project was designed in RStudio in the NHS England Unified Data Access Layer (UDAL) environment and requires an NHS England UDAL login (the login is vacant and will need editing).
Secondary Uses Service (SUS) data are read into the script from the Performance Analysis Team database.
Data are filtered for Alzheimer's patients using relevant ICD-10 codes.
Data are cleaned and organised into event logs.
The 80% most frequent patient process pathways are identified and visualised as a static or animated process map.

### Built With
- R Markdown

### Strengths
This can be adapted for any relevant ICD-10 code meaning it can apply to any disease area where the patient journey through the hospital system needs to be visualised.
This script can show the stages and delays experienced throughout the patient journey.

### Limitations
This process only includes Secondary Uses Service (SUS) data. There is no information on primary care, community care, outpatients etc, there is potential to link this data however.
Only primary OPCS level 4 codes are visualised, other OPCS level 4 treatment codes that are assigned to the patient are omitted from the visualisation.
There is no information on the duration of the stage or treatment, only the time between the stages is documented.
Durations between stages are only accurate to the nearest day.

## License
Distributed under the MIT License. See LICENSE.md for more information.

## Contact
Project contact email: gallin.montgomery@nhs.net
