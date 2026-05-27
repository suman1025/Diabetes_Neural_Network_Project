# Diabetes Neural Network Project
## Project Overview
This project focuses on predicting diabetes using patient medical data. I used a Neural Network model to learn patterns from healthcare features such as glucose level, blood pressure, BMI, insulin level, age, and other medical measurements. The main goal of this project is to understand how Machine Learning can support healthcare prediction tasks.

## Project Objectives
- To understand the diabetes dataset and its medical features.
- To prepare and preprocess the healthcare data for analysis.
- To build a Neural Network model for diabetes prediction.
- To evaluate the performance of the model.
- To compare the baseline model and improved model.
- To interpret the results and suggest future improvements.

## Dataset Information
The dataset used in this project is the Pima Indians Diabetes Dataset. It contains patient medical information related to diabetes prediction. The target variable is `Outcome`.

- 0 means No Diabetes
- 1 means Diabetes

The dataset includes features such as:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome

## Tools and Technologies Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- scikit-learn
- TensorFlow / Keras

## Data Preprocessing

In this project, I first loaded the dataset and checked the basic structure of the data. I reviewed the number of rows and columns, data types, missing values, and summary statistics. After that, I separated the input features and target variable. I also scaled the input data because Neural Network models work better when the feature values are in a similar range.

## Exploratory Data Analysis

I used basic exploratory data analysis to understand the dataset before building the model. I checked the dataset structure, feature distribution, and relationship between variables. This step helped me understand the medical features used for diabetes prediction.

## Model Development

I first built a baseline Neural Network model. After that, I created an improved model by adding more layers and Dropout. The purpose of improving the model was to check whether the prediction performance could be better than the first model.

## Model Evaluation

The model was evaluated using accuracy, confusion matrix, and classification report. These evaluation results helped me understand how well the model predicted diabetes and no-diabetes cases.

## Key Findings and Analytical Perspective

The improved Neural Network model gave better prediction results compared to the baseline model. The result shows that model structure and preprocessing steps can affect prediction performance. In healthcare prediction, accuracy is important, but recall is also important because missing a possible diabetes case can be risky.

## Direct Prediction

I also tested the trained model using new patient medical data. The model predicted whether the patient was likely to have diabetes or not. This step helped show how the model can be used for individual prediction.

## Conclusion

In this project, I built a Neural Network model to predict diabetes using healthcare data. The project helped me understand data preprocessing, model training, model evaluation, model improvement, and direct prediction. The improved model gave better prediction results and showed how Machine Learning can support healthcare decision-making. This model is only for learning purposes and should not replace professional medical diagnosis.
