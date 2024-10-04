## crime-detection

#  Dataset Description
In this competition, you'll analyze a dataset filled with information about crime incidents. You'll look at where the incidents happened, details about the victims, and other important factors. 

https://www.kaggle.com/competitions/crime-cast-forecasting-crime-categories/data

Your goal is to use this data to predict the type of crime that occurred.

# Dataset Overview:
Welcome to the Crime Category Prediction Challenge! Our dataset serves as your gateway to exploring the world of crime incidents. Each entry encapsulates a unique narrative, featuring details such as incident locations, victim demographics, and other key attributes. Your task is to explore this comprehensive dataset and construct predictive models that can forecast the category of crime for each incident. Unleash your creativity and analytical skills to uncover the underlying patterns.

# Citation
iitmbscs2008p. (2024). CrimeCast: Forecasting Crime Categories. Kaggle. https://kaggle.com/competitions/crime-cast-forecasting-crime-categories


## Data Files:

The dataset consists of the following files:

- train.csv: The training set, inclusive of the target variable 'crime_category' and relevant feature attributes.
- test.csv: The test set, containing similar feature attributes but excluding the target variable 'crime_category', as it is the variable to be predicted.
- sample_submission.csv: A sample submission file provided in the correct format for competition submissions.

# Columns Description:
- Location: Street address of the crime incident.
- Cross_Street: Cross street of the rounded address.
- Latitude: Latitude coordinates of the crime incident.
- Longitude: Longitude coordinates of the crime incident.
- Date_Reported: Date the incident was reported.
- Date_Occurred: Date the incident occurred.
- Time_Occurred: Time the incident occurred in 24-hour military time.
- Area_ID: LAPD's Geographic Area number.
- Area_Name: Name designation of the LAPD Geographic Area.
- Reporting_District_no: Reporting district number.
- Part 1-2: Crime classification.
- Modus_Operandi: Activities associated with the suspect.
- Victim_Age: Age of the victim.
- Victim_Sex: Gender of the victim.
- Victim_Descent: Descent code of the victim.
- Premise_Code: Premise code indicating the location of the crime.
- Premise_Description: Description of the premise code.
- Weapon_Used_Code: Weapon code indicating the type of weapon used.
- Weapon_Description: Description of the weapon code.
- Status: Status of the case.
- Status_Description: Description of the status code.
- Crime_Category: The category of the crime (Target Variable)