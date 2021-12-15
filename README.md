# DATA512-A7
## Introduction
This repository contains the data and code used to investigate whether there is a relationship between the spread of Covid19 and different kinds of human activity.

## Data Summaries
For simplicity, these data tables will only describe the data used in my project.
### John Hopkins
Original File: RAW_us_confirmed_cases.csv/RAW_us_confirmed_cases.csv
| Feature | Description|
|---------|------------|
| Province | The state/province reporting the cases |
| Admin2 | The jurisdiction one level below the state/province that is reporting the cases. |
| UID | unique identifier for the juridisction reporting cases. |
| iso2 | 2 character ISO country code |
| iso3 | 3 character ISO country code |
| code3 | numerical representation of country |
| FIPS | unique identifier for county |
| Country_Region | the country reporting the cases. |
| Lat | the latitude of the jurisdiction reporting the cases. |
| Long_ | the longiturde of the jurisdiction reporting the cases. |
| Combined_Key | full name of the jurisdiction with all levels included |
| All other columns | The cumulative number of cases reported on the date that is the column name. |

### Apple Mobility Data
Original File: applemobilitytrends-2021-12-06.csv
| Feature | Description|
|---------|------------|
| geo_type | The type of jurisdiction the data is from |
| region | the name of the jurisdiction the data is from |
| transportation_type | The type of routing request made. |
| alternative_name | alternative name of the region the data is from. |
| sub-region | The sub-region the data is from. |
| country | the country the data is from |
| All other columns | The level of mobility for the given type on the date that is the column name relative to the level on 1/13/2020. |

### OpenTable Table Reservations
Original File: 2020-2021vs2019_Seated_Diner_Data.csv
| Feature | Description|
|---------|------------|
| Type | Type of area the data is from. |
| Name | The name of the area the data is from. |
| All other columns | The level of table reservations on the date that is the column name relative to the same day of the year in 2019. |

### Final Output
File: merged_filtered.csv
This file contains the data used in the models.
| Feature | Description|
|---------|------------|
| County | The county the data represents |
| SecondDate | The date the activity level and change in new cases was reported. |
| Cases_Change | The change in the number of daily new cases relative to the previous day's number of new cases. |
| Cases_Change% | The percent change in the number of daily new cases as a percent of the previous day's number of new cases. |
| Transit_Change | The change in the transit mobility relative to the previous day's transit mobility. |
| Transit_Change% | The percent change in the transit mobility as a percent of the previous day's level of transit mobility. |
| Transit_Level | The level of transit mobility relative to Jan 13, 2020. |
| Driving_Change | The change in the driving mobility relative to the previous day's driving mobility. |
| Driving_Change% | The percent change in the driving mobility as a percent of the previous day's level of driving mobility. |
| Driving_Level | The level of driving mobility relative to Jan 13, 2020. |
| Walking_Change | The change in the walking mobility relative to the previous day's walking mobility. |
| Walking_Change% | The percent change in the walking mobility as a percent of the previous day's level of walking mobility. |
| Walking_Level | The level of walking mobility relative to Jan 13, 2020. |
| Table_Change | The change in the table reservations relative to the previous day's table reservations. |
| Table_Change% | The percent change in the table reservations as a percent of the previous day's level of table reservations. |
| Table_Level | The level of table reservations relative to the same day of the year in 2019. |