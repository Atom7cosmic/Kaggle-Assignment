Logistic Regression Model – Summer Analytics Hackathon

Author: Aryan Soni
Notebook Name: Logistic Regression Model 2
Platform: Kaggle
Hackathon: Summer Analytics First Hackathon (by IIT Guwahati)

 
 About

This repository contains my solution notebook for the Summer Analytics Hackathon conducted on Kaggle. The task was to build a classification model using the provided dataset (hacktrain.csv, hacktest.csv) and predict classes for the test data.

The approach used in this notebook is Logistic Regression, along with preprocessing techniques for feature scaling and label encoding.


 
 What’s Inside
	•	Data loading from provided CSV files
	•	Data preprocessing: label encoding, scaling
	•	Splitting data into train and validation sets
	•	Training a Logistic Regression model
	•	Evaluation using classification metrics
	•	Generating a .csv for submission

 Libraries Used
pandas  
numpy  
scikit-learn (LogisticRegression, train_test_split, StandardScaler, LabelEncoder)



from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder, StandardScaler
from sklearn.metrics import classification_report


Files
	•	logistic-regression-model-2.ipynb – Main notebook
	•	submission.csv – Sample submission file (if applicable)
