# DATA512-A7
## Introduction
This repository contains the data and code used to investigate whether there is a relationship between the spread of Covid19 and different kinds of human activity.

## Data Summaries
For simplicity, these data tables will only describe the data used in my project.
### John Hopkins
Original File: RAW_us_confirmed_cases.csv/RAW_us_confirmed_cases.csv
| Feature | Description|
|---------|------------|
| County | The county the data represents |
| SecondDate | The date the covid cases were reported |
| Cases_Change | The change in the number of daily new cases relative to the previous day's number of new cases. |
| Cases_Change% | The percent change in the number of daily new cases as a percent of the previous day's number of new cases. |

### Apple Mobility Data
Original File: applemobilitytrends-2021-12-06.csv
| Feature | Description|
|---------|------------|
| County | The county the data represents |
| SecondDate | The date the covid cases were reported |
| Transit_Change | The change in the transit mobility relative to the previous day's transit mobility. |
| Transit_Change% | The percent change in the transit mobility as a percent of the previous day's level of transit mobility. |
| Transit_Level | The level of transit mobility relative to Jan 13, 2020. |
| Driving_Change | The change in the driving mobility relative to the previous day's driving mobility. |
| Driving_Change% | The percent change in the driving mobility as a percent of the previous day's level of driving mobility. |
| Driving_Level | The level of driving mobility relative to Jan 13, 2020. |
| Walking_Change | The change in the walking mobility relative to the previous day's walking mobility. |
| Walking_Change% | The percent change in the walking mobility as a percent of the previous day's level of walking mobility. |
| Walking_Level | The level of walking mobility relative to Jan 13, 2020. |

### OpenTable Table Reservations
Original File: 2020-2021vs2019_Seated_Diner_Data.csv
| Feature | Description|
|---------|------------|
| County | The county the data represents |
| SecondDate | The date the covid cases were reported |
| Table_Change | The change in the table reservations relative to the previous day's table reservations. |
| Table_Change% | The percent change in the table reservations as a percent of the previous day's level of table reservations. |
| Table_Level | The level of table reservations relative to the same day of the year in 2019. |

### Final Output
File: merged_filtered.csv
This file contains the data used in the models.