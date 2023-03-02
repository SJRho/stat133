# California Fire Perimeters Data-Dictionary

Source: https://frap.fire.ca.gov/frap-projects/fire-perimeters/


## Data Set Information

- The data is related with the so-called __California Fire Perimeters__ Database.

- The attributes listed below are the variables of the CSV file "California_Fire_Perimeters.csv".

- Keep in mind that this file is part of a larger collection of various files that form the ESRI ArcGIS file geodatabase of the "California Fire Perimeters" database.

- For more information, please refer to: https://frap.fire.ca.gov/frap-projects/fire-perimeters/



## Fire Perimeters Attribute Table Definitions

| Variable       | Description                                                                            | Data Type |
|----------------|----------------------------------------------------------------------------------------|-----------|
| OBJECTID       | Identifier                                                                             | Integer   |
| YEAR           | Fire Year                                                                              | Integer   |
| STATE          | State (2-letter abbreviation)                                                          | Text      |
| AGENCY         | Direct protection agency responsible for fire                                          | Text      |
| UNIT_ID        | ICS code for unit                                                                      | Text      |
| FIRE_NAME      | Name of the fire                                                                       | Text      |
| INC_NUM        | Number assigned by the Emergency Command Center of the responsible agency for the fire | Text      |
| ALARM_DATE     | Alarm date for fire                                                                    | Date      |
| CONT_DATE      | Containment data for fire                                                              | Date      |
| CAUSE          | Reason fire ignited                                                                    | Integer   |
| REPORT_AC      | Estimated area consumed in fire                                                        | Double    |
| GIS_ACRES      | GIS calculated area in acres                                                           | Double    |
| C_METHOD       | Method used to collect perimeter data                                                  | Integer   |
| OBJECTIVE      | Either suppression or resource benefit                                                 | Integer   |
| FIRE_NUM       | *Description unavailable*                                                              | Text      |



### State Coding

STATE codes:

-   CA: California
-   NV: Nevada
-   OR: Oregon
-   AZ: Arizona



### Agency Coding

AGENCY codes:

-   BIA: USDI Bureau of Indian Affairs
-   BLM: Bureau of Land Management
-   CDF: California Department of Foresty and Fire Protection
-   CCO: Contract Counties
-   DOD: Department of Defense
-   FWS: USDI Fish and Wildfire Service
-   LRA: Local Response Area
-   NOP: No Protection
-   NPS: National Park Service
-   PVT: Private
-   USF: United States Forest Service
-   OTH: Other



### Cause Coding

CAUSE codes:

- 1 = Lightning
- 2 = Equipment Use
- 3 = Smoking
- 4 = Campfire
- 5 = Debris
- 6 = Railroad
- 7 = Arson
- 8 = Playing with Fire
- 9 = Miscellaneous
- 10 = Vehicle
- 11 = Power Line
- 12 = Firefighter Training
- 13 = Non-Firefighter Training
- 14 = Unknown/Unidentified
- 15 = Structure
- 16 = Aircraft
- 17 = Volcanic
- 18 = Escaped Prescribed Burn
- 19 = Illegal Alien Campfire



### Collection Method Coding

C_METHOD codes:

- 1 = GPS Ground 
- 2 = GPS Air 
- 3 = Infrared 
- 4 = Other Imagery 
- 5 = Photo Interpretation 
- 6 = Hand Drawn 
- 7 = Mixed Collection Methods 
- 8 = Unknown



### Objective Coding

OBJECTIVE codes:

- 1 = Suppresion (Wildfire)
- 2 = Resource Benefit (WFU)

