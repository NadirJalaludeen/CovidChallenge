# CovidChallenge - January 2023
Data Challenge for First Year Bachelor Students of Sorbonne University


**Context**

COVID-19 is an infectious disease caused by a recently discovered coronavirus. Most people infected with the virus will have mild to moderate respiratory illness and will recover without the need for special treatment. The elderly and those with underlying medical conditions such as cardiovascular disease, diabetes, chronic respiratory disease and cancer are more likely to develop severe disease. Throughout the pandemic, one of the major issues facing health care providers has been the lack of medical resources and an appropriate plan to distribute them effectively. In these difficult times, being able to predict the type of resources an individual may need at the time they test positive or even before that will be of immense help to authorities as they will be able to procure and organize the resources necessary to save that patient's life.


**Objective**

The main objective of this project is to build a machine learning model that, given a Covid-19 patient's current symptoms, condition and medical history, will predict whether the patient is at high risk or not. The variable to be predicted is the variable LABEL which measures the severity of the COVID-19 infection and can take the values

- SOFT_COVID : mild covid
- STRONG_COVID : covid requiring heavy medical care
- DEAD : fatal covid


**Dataset**

- USMER: indicates whether the patient treated first or second level medical units
- MEDICAL_UNIT: type of institution in the national health system that provided the care (from 1 to 13)
- SEX: sex of the patient (1 for women and 2 for men)
- PNEUMONIA: whether the patient already has inflammation of the air sacs of the lungs (1) or not (2)
- AGE: age of the patient
- PREGNANT: if the patient is pregnant (1) or not (2)
- DIABETES : if the patient is diabetic (1) or not (2)
- COPD: if the patient has chronic obstructive pulmonary disease(1) or not (2)
- ASTHMA: if the patient is asthmatic (1) or not (2)
- INMSUPR: if the patient is immunosuppressed (1) or not (2)
- HIPERTENSION: if the patient is hypertensive (1) or not (2)
- OTHER_DISEASE: if the patient has another disease (1) or not (2)
- CARDIOVASCULAR: if the patient has a heart or blood vessel disease (1) or not (2)
- OBESITY: if the patient is obese (1) or not (2)
- RENAL_CHRONIC : if the patient has a chronic renal disease (1) or not (2)
- TOBACCO : if the patient smokes (1) or not (2)


From the Kaggle Challenge "ARESD 2023 - CovidChallenge", by Margaux Brégère and Simone Azeglio
https://www.kaggle.com/competitions/aresd-2023-covidchallenge
