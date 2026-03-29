# 🎓 Student Productivity & Burnout Predictor

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Project Overview
This is a **Supervised Machine Learning** application designed to predict a student's daily productivity level based on their lifestyle habits. By analyzing factors such as sleep, study hours, and digital screen time, the model classifies a day into one of three categories: **Low, Medium, or High** productivity.

The goal is to provide a data-driven approach to understanding burnout and optimizing student schedules.

---

## 📊 Key Features (Dataset)
The model evaluates the following inputs to determine productivity:

* **🛌 Sleep_Hours:** Total hours of restorative rest.
* **📚 Study_Hours:** Time spent on focused academic work.
* **📱 Screen_Time:** Hours spent on digital devices (non-study).
* **🏋️‍♂️ Exercise_Mins:** Physical activity duration.
* **🗓️ Is_Weekend:** Binary indicator (0 for Weekday, 1 for Weekend).

---

## 🛠️ Technologies Used
| Technology | Usage |
| :--- | :--- |
| **Python 3.x** | Core Programming Language |
| **Pandas & NumPy** | Data Manipulation & Processing |
| **Matplotlib & Seaborn** | Data Visualization (Heatmaps/Trends) |
| **Scikit-Learn** | ML Model (Random Forest) & Evaluation |

---

## 🚀 How to Run the Project

### 1. Prerequisites
Ensure you have Python installed. Install the necessary libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 2. Execution Steps
Follow these steps in order to replicate the results:

1.  **Generate Data:** Run `data_generation.py` to create the `student_productivity_data.csv` file.
2.  **Analyze Data:** Run `analysis.py` to generate the correlation heatmap.
3.  **Train Model:** Run `model.py` to train the Random Forest Classifier and view the accuracy report.

---

## 📈 Model Performance
* **Algorithm:** Random Forest Classifier
* **Evaluation Metric:** Accuracy, Precision, and Recall.
* **Current Accuracy:** `~92%` (Based on synthetic data).

---

## 📂 Repository Structure
```text
├── data_generation.py           # Script to create the synthetic dataset
├── analysis.py                  # Script for Exploratory Data Analysis (EDA)
├── model.py                     # Script to train and test the ML model
├── student_productivity_data.csv # The generated dataset
├── correlation_chart.png        # Visual heatmap of features
└── Project_Report.pdf           # Detailed documentation
```

---
```

Since you've worked on projects like **VibeTunes** before, would you like me to help you create a **Requirements.txt** file for this one as well to make it even more professional?
