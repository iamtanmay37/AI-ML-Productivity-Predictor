Student Productivity & Burnout Predictor (AI/ML)

📌 Project Overview

This project is a Supervised Machine Learning application designed to predict a student's daily productivity level based on their lifestyle habits. By analyzing factors such as sleep, study hours, and digital screen time, the model classifies a day into one of three categories: Low, Medium, or High productivity.
The goal is to provide a data-driven approach to understanding burnout and optimizing student schedules.


📊 Key Features (Dataset)
The model evaluates the following inputs:

Sleep_Hours: Total hours of rest.

Study_Hours: Time spent on focused academic work.

Screen_Time: Hours spent on digital devices (non-study).

Exercise_Mins: Physical activity duration.

Is_Weekend: Binary indicator (0 for Weekday, 1 for Weekend).



🛠️ Technologies Used
Language: Python 3.x

Libraries: * Pandas (Data manipulation)

NumPy (Numerical processing)

Matplotlib & Seaborn (Data visualization)

Scikit-Learn (Machine Learning model & evaluation)



🚀 How to Run the Project
1. Prerequisites
Ensure you have Python installed. You can install the necessary libraries using pip:

Bash:
pip install pandas numpy matplotlib seaborn scikit-learn

2. Execution Steps
Follow these steps in order to replicate the results:

Generate Data: Run data_generation.py to create the student_productivity_data.csv file.

Analyze Data: Run analysis.py to generate the correlation heatmap and see data trends.

Train Model: Run model.py to train the Random Forest Classifier and view the accuracy report.



📈 Model Performance
Algorithm: Random Forest Classifier

Evaluation Metric: Accuracy, Precision, and Recall.

Current Accuracy: ~92% (Approximate based on synthetic data generation).



📂 Repository Structure
data_generation.py: Script to create the synthetic dataset.

analysis.py: Script for Exploratory Data Analysis (EDA).

model.py: Script to train and test the ML model.

student_productivity_data.csv: The dataset used for training.

correlation_chart.png: Visual representation of feature relationships.

Project_Report.pdf: Detailed documentation of the project.
