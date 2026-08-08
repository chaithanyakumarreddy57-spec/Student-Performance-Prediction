# Student Performance Prediction Using Machine Learning

## Project Overview

This project focuses on building a machine learning model to predict students' final academic performance using the Student Performance dataset. Different machine learning algorithms are applied to train and evaluate the prediction model based on student-related features.

---

## Objective

The objective of this project is to develop a predictive model that estimates a student's final grade (G3) using demographic, family, and academic information. The project also compares model performance using evaluation metrics.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Dataset

- **Dataset:** Student Performance Dataset
- **Source:** UCI Machine Learning Repository

### Features Used

- School
- Gender
- Age
- Study Time
- Family Size
- Parents' Education
- Travel Time
- Failures
- Absences
- Previous Grades (G1, G2)
- Final Grade (G3)

**Target Variable:**
- **G3 (Final Grade)**

---

## Machine Learning Algorithms

The following machine learning models were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Explore and preprocess the data.
4. Check for missing values.
5. Encode categorical variables.
6. Split the dataset into training and testing sets.
7. Train machine learning models.
8. Predict final student grades.
9. Evaluate model performance.
10. Compare different algorithms.

---

## Model Evaluation

The models were evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

Visualization used:

- Model Comparison Graph
- Feature Importance Plot
- Actual vs Predicted Values Plot

---

## Results

The Random Forest Regressor achieved the best prediction performance among the implemented models, providing higher accuracy and lower prediction error compared to Linear Regression and Decision Tree Regressor.

---

## Repository Structure

```text
Student-Performance-Prediction/
│── Student_Performance_Prediction.ipynb
└── README.md
```

---

## Future Improvements

- Hyperparameter tuning for improved accuracy.
- Feature engineering.
- Cross-validation for better model evaluation.
- Deploy the model as a web application using Flask or Streamlit.

---

**Chaitanya Kumar Reddy C**
