Diabetes Prediction Using Artificial Neural Networks (ANN)
Overview
This project uses an Artificial Neural Network (ANN) to predict whether a patient is likely to have diabetes based on medical and demographic information.

The model is trained on the Pima Indians Diabetes Dataset and demonstrates the application of deep learning in healthcare analytics.

Features
Data preprocessing and feature scaling
Artificial Neural Network implementation using TensorFlow/Keras
Model training and evaluation
Diabetes risk prediction for new patients
Accuracy and loss visualization
Confusion matrix and classification report
Dataset
Dataset: Pima Indians Diabetes Dataset

Input Features
Feature	Description
Pregnancies	Number of pregnancies
Glucose	Blood glucose level
BloodPressure	Blood pressure
SkinThickness	Triceps skin fold thickness
Insulin	Insulin level
BMI	Body Mass Index
DiabetesPedigreeFunction	Family history factor
Age	Age of patient
Target Variable
Value	Meaning
0	Non-Diabetic
1	Diabetic
Technologies Used
Python
TensorFlow / Keras
NumPy
Pandas
Matplotlib
Scikit-learn
Jupyter Notebook
Project Workflow
Data Collection
Data Preprocessing
Feature Scaling
Train-Test Split
ANN Model Development
Model Training
Model Evaluation
Prediction of New Patient Records
ANN Architecture
Input Layer (8 Features)

↓

Hidden Layer (16 Neurons, ReLU)

↓

Hidden Layer (8 Neurons, ReLU)

↓

Output Layer (1 Neuron, Sigmoid)

Evaluation Metrics
Accuracy Score
Precision
Recall
F1 Score
Confusion Matrix
ROC Curve
Results
The model successfully predicts diabetes risk using patient health records and achieves competitive performance on the dataset.
