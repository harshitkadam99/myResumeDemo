🎓 Student Performance Prediction System
📌 Project Overview

This project predicts a student’s final exam score (G3) using academic, social, and family-related features. It demonstrates how machine learning can be applied to real-world education analytics.
The system uses supervised learning to find patterns in student data and estimate their future academic performance.

🧠 Machine Learning Techniques Used
Supervised Learning
Linear Regression
Feature Encoding (One-Hot Encoding)
Train–Test Split
Model Evaluation (R² Score)
Data Visualization using Matplotlib

📦 Dataset
Source: UCI / Kaggle – Student Performance Dataset
The dataset contains:
395 students
33 features such as:
Study time
Absences
Family background
Internet access
Previous grades (G1, G2, G3)
G3 is the final exam score and is used as the prediction target.

⚙️ Project Workflow

Loaded CSV data using Pandas
Inspected and cleaned the dataset
Separated input features (X) and output (G3)
Converted categorical columns into numeric form
Split data into training and testing sets
Trained a Linear Regression model
Evaluated model performance
Visualized trends using Matplotlib
Predicted final student scores

📊 Data Visualization

The following graphs were created using Matplotlib:
Distribution of final grades (G3)
Study time vs final score
Absences vs final score
G2 vs G3 (previous vs final grade)
These visualizations help understand trends, outliers, and correlations in student performance.

📈 Model Performance

The Linear Regression model achieved approximately:
72% accuracy (R² score)
This means the model explains most of the variation in students’ final exam results using available data.

🚀 Technologies Used

Python
Pandas
NumPy
Matplotlib
Scikit-Learn
Jupyter Notebook

🎯 Conclusion

This project demonstrates a complete end-to-end Machine Learning pipeline on a real-world dataset, including data preprocessing, model training, evaluation, visualization, and prediction.
It shows how ML can be used to solve real problems in the education sector.
