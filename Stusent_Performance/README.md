# 🎓 Student Performance Prediction

## 📌 Project Overview

This project predicts a student's **Math Score** using machine learning based on student information such as gender, parental education, lunch type, test preparation course, reading score, and writing score.

---

## 🎯 Objective

Build a machine learning model to predict **Math Score** using student-related features.

---

## 📂 Dataset

Dataset Name: Students Performance in Exams

Features:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Reading Score
- Writing Score

Target:
- Math Score

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 🤖 Machine Learning Algorithm

- Linear Regression

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Explore the Dataset
4. Encode Categorical Data using LabelEncoder
5. Visualize the Data
6. Select Features (X) and Target (y)
7. Split Dataset into Training and Testing Sets
8. Train Linear Regression Model
9. Make Predictions
10. Evaluate the Model
11. Save the Trained Model

---

## 📈 Model Performance

- MAE: 4.13
- MSE: 28.28
- R² Score: 0.884

---

## 📁 Project Structure

```
Student_Performance_Prediction/
│
├── StudentsPerformance.csv
├── student_performance.ipynb
├── student_performance.pkl
├── README.md
└── requirements.txt
```

---

## 💾 Save Model

```python
import joblib
joblib.dump(model, "student_performance.pkl")
```

---

## 🔮 Example Prediction

Input:

- Gender: Male
- Race/Ethnicity: Group C
- Parental Education: Bachelor's Degree
- Lunch: Standard
- Test Preparation: Completed
- Reading Score: 80
- Writing Score: 85

Predicted Math Score:

```
89.22
```

---

## 📚 Libraries Required

```
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
```

---

## 🚀 Future Improvements

- Compare multiple machine learning models.
- Perform feature engineering.
- Tune model hyperparameters.
- Deploy the model using Streamlit or Flask.

---

## 👨‍💻 Author

**Arman**

B.Sc. Data Science Student

Project: Student Performance Prediction