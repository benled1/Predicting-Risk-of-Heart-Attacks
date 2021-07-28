## Predicting Risk of Heart Attacks in Patients
Using a dataset of patients, I trained a simple machine learning algorithm to predict which of them were at high risk for a heart attack in the near future.

## Datasets
The two datasets that were used here are heart_test.csv and heart_train.csv. These datasets display information about the patients cariovascular health. The fields that are displayed in the data are written below.

- Age : Age of the patient
- Sex : Sex of the patient
- exang: exercise induced angina (1 = yes; 0 = no)
- ca: number of major vessels (0-3)
- cp : Chest Pain type chest pain type
  - Value 1: typical angina
  - Value 2: atypical angina
  - Value 3: non-anginal pain
  - Value 4: asymptomatic
- trtbps : resting blood pressure (in mm Hg)
- chol : cholestoral in mg/dl fetched via BMI sensor
- fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- rest_ecg : resting electrocardiographic results
  - Value 0: normal
  - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or 
depression of > 0.05 mV)
- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- thalach : maximum heart rate achieved
- target : 0= no chance of heart attack 1= very high chance of heart attack

#### heart_test.csv 
This is un-labelled data that provides the above information about the patients. As mentioned this dataset does not have labels signifying if a patient is at high risk of a heart attack. This is the data that the model is fed to predict.

#### heart_train.csv
This is the labelled data that provides all the same information as heart_test.csv, with an additional column signifying if the particular patient is at high risk of a heart attack in the near future. In this column a 1 = Yes and a 0 = No. This is the data used to train the model and ensure that it is making satisfactory predictions.

#### Showing my work

The steps in my work and the results are all displayed in the jupyter notebook file in this repository. To view this open up "Heart Attack Prediction.ipynb". There you will see not only the model I used, but also the exploratory data analysis I did to gain a better understanding of the data.
