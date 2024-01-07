# Crime-area-prediction-with-classification
## Introduction
This project aimed to predict where a crime most likely occured (specifically violent crimes) based on multiple factors. The locations in question are the zipcodes within charlotte.
Factors Include
- Crime NIBRS classification
- Weapon used
- Season in which the crime occured

Predicting areas where a crime could occur could help states and cities make themselves a safer place.   

## Data Source
This data is found in the following website:
- https://data.charlottenc.gov/datasets/charlotte::cmpd-incidents-1/about

## Data Preparation 
- Grouped all years together
- Combined the different data sets crimes and weapons
- Zipcodes had to be cleaned up and aggregated
- Grouped together similar NIBRS classifications
- Took out crimes where either no weapon was used or only hands/feet were used
- Dealt with other NA fields
