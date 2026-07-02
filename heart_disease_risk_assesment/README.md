#  Heart Disease Prediction using Machine Learning

##  About the Project

Heart disease is one of the leading causes of death worldwide. Early prediction can help doctors provide timely treatment and improve patient care. This project uses Machine Learning techniques to predict whether a patient is likely to have heart disease based on medical attributes.

Two classification algorithms, **Decision Tree** and **Random Forest**, are implemented and compared to determine which model performs better for this prediction task.

---

##  Objectives

- Predict the presence of heart disease.
- Train and compare Decision Tree and Random Forest models.
- Evaluate model performance using Accuracy Score.
- Identify the most influential features using Feature Importance.

---

##  Dataset Information

**Dataset:** UCI Heart Disease Dataset

The dataset contains patient health records with different medical attributes.

### Input Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- Slope
- Number of Major Vessels (CA)
- Thalassemia (Thal)

### Target Variable

- **0** → No Heart Disease
- **1** → Heart Disease

---

##  Technologies Used

- Python
- Pandas
- Scikit-learn

---

##  Machine Learning Models

### Decision Tree
A tree-based classification algorithm that predicts heart disease by creating decision rules from the dataset.

### Random Forest
An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

##  Project Workflow

- Import required libraries
- Load the dataset
- Prepare features and target
- Split the data into training and testing sets
- Train the Decision Tree model
- Evaluate Decision Tree accuracy
- Train the Random Forest model
- Evaluate Random Forest accuracy
- Analyze Feature Importance
- Compare model performance

---

##  Model Evaluation

The models are evaluated using:

- Accuracy Score

The model with higher accuracy is considered more effective for heart disease prediction.

---

##  Feature Importance

Random Forest provides Feature Importance scores, which indicate how much each feature contributes to the prediction. This helps identify the most significant medical factors associated with heart disease.

---

##  Results

- Successfully trained Decision Tree and Random Forest models.
- Compared the accuracy of both models.
- Identified the most important health features.
- Predicted whether a patient has heart disease or not.

---

##  Future Scope

- Add Confusion Matrix
- Add Precision, Recall and F1-Score
- Create interactive visualizations
- Build a web application using Streamlit
- Deploy the model online

---

##  Project Files

```
Heart-Disease-Prediction/
│
├── heart_disease_cleveland.csv
├── Heart_Disease_Prediction.ipynb
├── README.md
├── requirements.txt
```

---

##  Author

**Mayank**

