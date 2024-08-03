https://archive.ics.uci.edu/dataset/360/air+quality

| Variable Name | Role    | Type        | Description                                                                                            | Units      | Missing Values |
| ------------- | ------- | ----------- | ------------------------------------------------------------------------------------------------------ | ---------- | -------------- |
| Date          | Feature | Date        |                                                                                                        |            | no             |
| Time          | Feature | Categorical |                                                                                                        |            | no             |
| CO(GT)        | Feature | Integer     | True hourly averaged concentration CO in mg/m^3 (reference analyzer)                                   | mg/m^3     | no             |
| PT08.S1(CO)   | Feature | Categorical | hourly averaged sensor response (nominally CO targeted)                                                |            | no             |
| NMHC(GT)      | Feature | Integer     | True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer) | microg/m^3 | no             |
| C6H6(GT)      | Feature | Continuous  | True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)                          | microg/m^3 | no             |
| PT08.S2(NMHC) | Feature | Categorical | hourly averaged sensor response (nominally NMHC targeted)                                              |            | no             |
| NOx(GT)       | Feature | Integer     | True hourly averaged NOx concentration in ppb (reference analyzer)                                     | ppb        | no             |
| PT08.S3(NOx)  | Feature | Categorical | hourly averaged sensor response (nominally NOx targeted)                                               |            | no             |
| NO2(GT)       | Feature | Integer     | True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)                              | microg/m^3 | no             |
| PT08.S4(NO2)  | Feature | Categorical | hourly averaged sensor response (nominally NO2 targeted)                                               |            | no             |
| PT08.S5(O3)   | Feature | Categorical | hourly averaged sensor response (nominally O3 targeted)                                                |            | no             |
| T             | Feature | Continuous  | Temperature                                                                                            | °C         | no             |
| RH            | Feature | Continuous  | Relative Humidity                                                                                      | %          | no             |
| AH            | Feature | Continuous  | Absolute Humidity                                                                                      |            | no             |
