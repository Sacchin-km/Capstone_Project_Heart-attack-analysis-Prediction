# Capstone_Project_Heart-attack-analysis-Prediction
Capstone_project_Heart attack analysis &amp; Prediction Classifier [EDA + ML]

# Problem Statement
To predict the risk of a heart attack based on a patient's health condition.


# Objectives
We have data on patients seen by a cardiologist.The main goal is to exploit machine learning techniques on medical data set to assist in identifying the major factors influencing heart attack and that will be able to predict the risk of  heart attack based on a patient's health condition.

# Dataset
The dataset is taken from kaggle, https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

Here we have the description of the features:(Also detailed data dictionary available)

age - age in years

sex - sex (0 = female; 1 = male)

cp - chest pain type (1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 0 = asymptomatic)

trtbps - resting blood pressure (in mm Hg on admission to the hospital)

chol - serum cholestoral in mg/dl

fbs - fasting blood sugar > 120 mg/dl (0 = false; 1 = true)

restecg - resting electrocardiographic results (0 = normal; 1 = hypertrophy; 2 = having ST-T wave abnormality)

thalachh - maximum heart rate achieved

exng - exercise induced angina (0 = no; 1 = yes)

oldpeak - ST depression induced by exercise relative to rest

slp - the slope of the peak exercise ST segment (0 = downsloping; 1 = flat; 2 = upsloping)

caa - number of major vessels (0-4)

thall - thallium stress test (1 = fixed defect; 2 = reversable defect; 3 = normal)

output - 0 = less chance of heart attack; 1 = more chance of heart attack

# Methodologies

1.Dataset collection

2.Data Visualization

3.Performed EDA : Handled Outliers , Deleted duplicate rows, visualization and Feature scaling.

4.Created 7 different Classification Models : LogisticRegression, RandomForestClassifier, XGBClassifier.
Performed comparative analysis on the techniques used.

# Libraries used

1.Data Cleaning: numpy, pandas

2.Visualisation: seaborn, matplotlib

3.Feature scaling: MinMaxScaler

4.Splitting to train and test: train_test_split

5.Accuracy calculation & confusion matixs: metrics,confusion_matrix,accuracy_score,precision_score,recall_score,f1_score

6.Algorithms: LogisticRegression, RandomForestClassifier, XGBClassifier
