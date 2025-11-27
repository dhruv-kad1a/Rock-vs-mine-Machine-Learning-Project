# **Rock vs Mine Prediction | Logistic Regression**

## 📌 **Project Overview**
This machine learning project classifies sonar signals to determine whether an object detected underwater is a rock or a mine. The model is trained using logistic regression and analyzes 60 signal frequency readings to make predictions. The goal is to support underwater navigation and security systems by identifying potential threats.

## 📂 **Dataset Description**
- **Total rows**: 208
- **Total columns**: 61
- **Features**: 60 numerical sonar readings
- **Target**:
  - ``R`` = Rock
  - ``M`` = Mine
Each row represents energy readings from sonar signal returns bounced off various objects.

## 🔧 **Technologies Used**
| Component     | Tools
| ----------- | ----------|
Programming Language       |    Python
Libraries                  |   NumPy, Pandas, Scikit-Learn, Matplotlib
Model                      |  Logistic Regression
Environment                | Jupyter Notebook

## 🚀 **Project Workflow**
1. Importing dependencies and loading data
2. Exploratory data analysis
3. Preprocessing
    - Label encoding
    - Train-test split (80-20)
4. Model training using Logistic Regression
5. Model evaluation
6. Prediction system for new input data
<img src='https://github.com/dhruv-kad1a/Rock-vs-mine-Machine-Learning-Project/blob/main/workflow.PNG' width='700'>
