# Diabetes-Detection-System
This project uses a machine learning model to predict whether a person is diabetic or not based on various health parameters. The system is built using Python and leverages libraries like pandas, numpy, scikit-learn, and SVM (Support Vector Machine).

Dataset
The dataset used for this project is the Pima Indians Diabetes Database. It contains health details of 768 patients, such as:

Pregnancies
Glucose Level
Blood Pressure
Skin Thickness
Insulin Level
BMI (Body Mass Index)
Diabetes Pedigree Function
Age
Outcome (0: Non-Diabetic, 1: Diabetic)


Features
Data Preprocessing: Standardization of the dataset using StandardScaler.
Model: SVM classifier with a linear kernel.
Training and Testing: Data is split into training (80%) and testing (20%) sets using train_test_split.
Evaluation: The model is evaluated based on accuracy for both training and testing data.


Accuracy
Training Data Accuracy: ~78.66%
Testing Data Accuracy: ~77.27%


Usage
You can modify the input_data in the script to predict if a new person is diabetic based on their health parameters.
