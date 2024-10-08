# Crime Detection Project

## Background
Crime is a significant issue in many urban areas, and understanding the patterns and factors associated with different types of crimes can help in developing effective prevention strategies. This project is part of the Crime Category Prediction Challenge on Kaggle, where the goal is to analyze a dataset of crime incidents and predict the type of crime that occurred based on various features.

## Goal
The primary objective of this project is to build predictive models that can accurately forecast the category of crime for each incident in the dataset. By leveraging machine learning techniques, we aim to uncover patterns and insights that can assist law enforcement agencies in better understanding and preventing crime.

## Dataset Description
The dataset provided for this competition includes detailed information about crime incidents, such as the location, victim demographics, and other relevant attributes. The dataset is divided two main files:

- `train.csv`: The training set, which includes the target variable `crime_category` and relevant feature attributes.
- `test.csv`: The test set, containing similar feature attributes but excluding the target variable `crime_category`.

### Columns Description
- **Location**: Street address of the crime incident.
- **Cross_Street**: Cross street of the rounded address.
- **Latitude**: Latitude coordinates of the crime incident.
- **Longitude**: Longitude coordinates of the crime incident.
- **Date_Reported**: Date the incident was reported.
- **Date_Occurred**: Date the incident occurred.
- **Time_Occurred**: Time the incident occurred in 24-hour military time.
- **Area_ID**: LAPD's Geographic Area number.
- **Area_Name**: Name designation of the LAPD Geographic Area.
- **Reporting_District_no**: Reporting district number.
- **Part 1-2**: Crime classification.
- **Modus_Operandi**: Activities associated with the suspect.
- **Victim_Age**: Age of the victim.
- **Victim_Sex**: Gender of the victim.
- **Victim_Descent**: Descent code of the victim.
- **Premise_Code**: Premise code indicating the location of the crime.
- **Premise_Description**: Description of the premise code.
- **Weapon_Used_Code**: Weapon code indicating the type of weapon used.
- **Weapon_Description**: Description of the weapon code.
- **Status**: Status of the case.
- **Status_Description**: Description of the status code.
- **Crime_Category**: The category of the crime (Target Variable).


## Citation
iitmbscs2008p. (2024). CrimeCast: Forecasting Crime Categories. Kaggle. https://kaggle.com/competitions/crime-cast-forecasting-crime-categories

