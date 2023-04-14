# ❤️ Topic: Cardio Vascular Disease (CVD)

---
### About:

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on exploring the factors that affect Heart Disease.

### Introduction:
What is Cardiovascular Disease?
Cardiovascular disease (CVD) is a general term that describes a disease of the heart or blood vessels. The term refers to set of diseases that one can be diagnosed with when blood flow to the heart, brain or body is reduced due to blood clots (Thrombosis) or a build-up of fatty deposits inside an artery, which usually leads to the artery becoming hard and narrow.

### Dataset:
The Dataset that we have chosen is taken from Kaggle and contains data of a group of 70,000 patients, with CVD present in some of them. The data depicts certain factors and characteristics of these patients, some of which may have contributed to their CVD.

We will explore this Dataset in this project.

---
### Contributors:
1. @evertone13
2. @BryanTohWS
3. @keithfykai

---
### Problem Statement:
Our aim of this project is to use different Machine Learning Models and Algorithms to analyse the cardio-vascular dataset and the accuracy of the various models used and see which is the most accurate and suitable for predicting the presence of cardio-vascular diseases in a person.

We will do this by passing the cardio vascular dataset we have obtained from kaggle through the Machine Learning Models and also performing different Exploratory Data Analysis techniques on the dataset to prepare the dataset fully before implementation.

---
### Models Used:
1. XGBoost
2. Logistic Regression
3. Neural Network Classifier

---
### Conclusion:
- Accuracy of the 3 Models were extremely similar
- This may be due to the nature of the dataset as it may have some inherent characteristics that make it easy for these models to achieve similar performance
- Neural Network Classifier had the best accuracy out of the 3 Models
- Models may also have been affected by the hyperparameters chosen
- BMI has the highest correlation out of all the numerical variables with Cardio Vascular Disease
- Inclusion of hyperparameters did help to boost the accuracy slightly


---
### What did we learn from this project:
1. Handling imbalanced datasets using resampling methods and imblearn package
2. Logistic Regression from sklearn
3. XGBoost from xgboost
4. NNC from sklearn
5. Other packages such as tqdm, json, XGBoost
6. Collaborating using GitHub
7. Concepts about Precision, Recall, F1 Score and Support

---
### References
- Cardio Dataset: https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset
- Systolic and Diastolic Bounds: https://www.heart.org/en/health-topics/high-blood-pressure/understanding-blood-pressure-readings
- Logistic Regression 1: https://www.nickmccullum.com/python-machine-learning/logistic-regression-python/ 
- Logistic Regression 2: https://towardsdatascience.com/quick-and-easy-explanation-of-logistics-regression-709df5cc3f1e 
- Normalization of Data: https://www.digitalocean.com/community/tutorials/normalize-data-in-python
