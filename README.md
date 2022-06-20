# Predicting heart disease using machine learning

This notebook looks into using various machine learning and data science libraries in attempt to build a machine learning model capable 
of predicting wheather or not someone has heart disease based on their medical attributes

**approaches**
1. problem defination
2. data
3. evaluation 
4. features
5. modeling
6. exprimentation

## 1. Problem  defination
In a statement,
> Given clinical parameters about a patient, can we predict wheather or not they have heart diseases ?

## 2. Data 
The original data is came from the cleavland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/heart+disease .
Data is also available on kaggle https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

## 3. Evaluation 
> if we can reach 95% or more accuracy whether or not patient has heart disease during the proof of concept, we'll pursue the project 

## 3. features
This is where you get each and every information about the data
**Create a data dictionary**

* id (Unique id for each patient)
* age (Age of the patient in years)
* sex (1-Male/0-Female)
* cp chest pain type ([typical angina, atypical angina, non-anginal, asymptomatic])
* trestbps resting blood pressure (resting blood pressure (in mm Hg on admission to the hospital))
* chol (serum cholesterol in mg/dl)
* fbs (if fasting blood sugar > 120 mg/dl)
* restecg (resting electrocardiographic results)
* -- Values: [normal, stt abnormality, lv hypertrophy]
* thalach: maximum heart rate achieved
* exang: exercise-induced angina (True/ False)
* oldpeak: ST depression induced by exercise relative to rest
* slope: the slope of the peak exercise ST segment
* ca: number of major vessels (0-3) colored by fluoroscopy
* thal: [normal; fixed defect; reversible defect]
* target: [0 - not having heart disease, 1 - has heart disease]
