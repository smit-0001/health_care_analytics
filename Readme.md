# Health Care Analytics

In this project we try to predict health score of different people using their health profile using machine learning model - Decsion Tree Regression

## Apendix

- Part 1 - Data Preprocessing
    - importing the dataset
    - merging and joining the dataset
    - dealing with missing values

- Part 2 - EDA
    - Pie chart
    - Histograms
    - Scatter plots

- Part 3 - Model Building
    - We build a Decision Tree Regression model
    - Make Predictions using this model

## A beirf Info On dataset

Health_Camp_Detail.csv 
– File containing Health_Camp_Id, Camp_Start_Date, Camp_End_Date and Category details of each camp.

Train.csv 
– File containing registration details for all the test camps. This includes Patient_ID, Health_Camp_ID, Registration_Date and a few anonymized variables as on registration date.

Patient_Profile.csv 
– This file contains Patient profile details like Patient_ID, Online_Follower, Social media details, Income, Education, Age, First_Interaction_Date, City_Type and Employer_Category

First_Health_Camp_Attended.csv 
– This file contains details about people who attended health camp of first format. This includes Donation (amount) & Health_Score of the person.

Second_Health_Camp_Attended.csv 
- This file contains details about people who attended health camp of second format. This includes Health_Score of the person.

Third_Health_Camp_Attended.csv 
- This file contains details about people who attended health camp of third format. This includes Number_of_stall_visited & Last_Stall_Visited_Number.

Test.csv 
– File containing registration details for all the test camps. This includes Patient_ID, Health_Camp_ID, Registration_Date and a few anonymized variables as on registration date.


with the patient profile dataset we merge first , second and third health camp info using patient_id giving us a 25 column dataset 

We drop column with more than 50% missing value
filling categorial column with mode values
filling numerial column with mean value

To Predict health score

we choose only important columns to make a dataset 
and use that dataset to make model and predictions.
