# Predicting Heart Disease using Machine Learning
This repository consist of ML experiments in form of notebook, which looks into using various Python-libraries of Machine Learning and Data Science in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.


## Prerequisites

### Environment

Install MiniConda, for detailed setup [check](https://github.com/SaketMunda/ml-ds-tools-library-introduction#environment-setup)

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn (for heatmaps)
- Scikit-Learn

### Workspace

- Jupyter Notebook

## Steps followed
1. Problem Definition
2. Data Exploration
3. Evaluation
4. Features
5. Modelling
6. Experimentation
 
 
## Problem Definition

In a statement,

> Given clinical parameters about a patient, can we predict whether or not they have heart disease ?


## Data Source

The original data came from the Cleavland data from the UCI Machine Learning Repository.

Download it from [UCI Heart Disease Data Set](https://archive.ics.uci.edu/ml/datasets/heart+disease) or [Kaggle](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)

## Data Format

![Screenshot 2022-09-15 at 12 39 28 PM](https://user-images.githubusercontent.com/29537875/190338458-1c2e9ca0-d5de-474e-ab46-44910695ef9a.png)

## Data Features (Dictionary)

1. age: age in years
2. sex: sex (1 = male; 0 = female)
3. cp: chest pain type
    - Value 0: typical angina
    - Value 1: atypical angina
    - Value 2: non-anginal pain
    - Value 3: asymptomatic
4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
5. chol: serum cholestoral in mg/dl
6. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. restecg: resting electrocardiographic results
    - Value 0: normal
    - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina (1 = yes; 0 = no)
10. oldpeak = ST depression induced by exercise relative to rest
11. slope: the slope of the peak exercise ST segment
    - Value 0: upsloping
    - Value 1: flat
    - Value 2: downsloping
12. ca: number of major vessels (0-3) colored by flourosopy
13. thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
14. target: 0 = no disease, 1 = disease

## Models Used

1. Logistic Regression
2. RandomForest Classifier
3. K-Nearest Neighbours

