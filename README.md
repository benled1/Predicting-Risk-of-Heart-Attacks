## Predicting Risk of Heart Attacks in Patients
Using a dataset of patients, I trained a simple machine learning algorithm to predict which of them were at high risk for a heart attack in the near future.

## Datasets
The two datasets that were used here are heart_test.csv and heart_train.csv. 

#### heart_test.csv 
This is un-labelled data that provides information about the patients.
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
