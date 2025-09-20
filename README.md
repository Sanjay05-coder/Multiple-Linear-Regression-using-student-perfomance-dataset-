
# Student Performance Prediction using Multiple Linear Regression

## 📋 Description
This project uses multiple linear regression to predict a student's **Performance Index** based on their **Previous Scores** and **Sample Question Papers Practiced**. The goal is to understand how these factors influence overall academic performance and to provide insights for personalized learning strategies.

## 📊 Dataset
The dataset contains the following columns:
- **Hours Studied**
- **Previous Scores**
- **Extracurricular Activities**
- **Sleep Hours**
- **Sample Question Papers Practiced**
- **Performance Index**

## 🏷️ Features Used
- **Previous Scores** (X1)
- **Sample Question Papers Practiced** (X2)
- **Performance Index** (Y, target)

## 🤖 Model
A multiple linear regression model is trained using scikit-learn to predict the Performance Index from the selected features.

## 📈 Results
- **R² Score:** 0.8289
- **Mean Squared Error:** 59.1801

These results indicate a strong fit, with the model explaining about 82.89% of the variance in student performance.

## 📊 Visualization
The project includes 3D scatter plots and regression planes to visualize the relationship between the predictors and the target variable.

