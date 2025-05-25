# Multi-Model Project

## Overview
Predict if a patient has a 10-year risk of developing coronary heart disease (CHD).

## Problem
The World Health Organization has estimated 12 million deaths occur worldwide every year due to heart disease. Half the deaths in the United States and other developed countries are due to cardiovascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high-risk patients and, in turn, reduce the complications. This research intends to pinpoint the most relevant/risk factors of heart disease and predict the overall risk. 

## Source 
The source dataset is publicly available on the Kaggle website, and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes. Variables attribute a potential risk factor. There are both demographic, behavioral, and medical risk factors.

### Demographic Attributes:
- gender: Male / Female
- age: integer
- attended_college: whether or not the patient attended college

### Behavioral Attributes:
- currentSmoker: whether or not the patient is a current smoker
- cigsPerDay: the number of cigarettes that the person smoked on average in one day

### Medical History Attributes:
- BPMeds: whether or not the patient was on blood pressure medication
- prevalentStroke: whether or not the patient had previously had a stroke
- prevalentHyp: whether or not the patient was hypertensive
- diabetes: whether or not the patient had diabetes.

### Current Medical Condition Attributes (continuous variables):
- totChol: total cholesterol level
- sysBP: systolic blood pressure
- diaBP: diastolic blood pressure
- BMI: Body Mass Index
- heartRate: heart rate
- glucose: glucose level

### Target variable to predict:
TenYearCHD: 10-year risk of coronary heart disease (CHD)
