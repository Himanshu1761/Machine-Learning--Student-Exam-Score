# Student Exam Score Analysis & Prediction

## Project Description

This project analyzes student exam performance using a dataset from Kaggle. The dataset contains information about students’ study habits, sleep patterns, attendance, and previous exam scores. This analysis helps understand key factors affecting exam performance and predict exam scores using machine learning models.
The project also implements regression models to predict student exam scores based on input features like study hours, sleep hours, attendance, and previous scores.

## About Dataset:
- Source: Kaggle
- Rows: 200
- Columns: 6 (hours_studied, sleep_hours, attendance_percent, previous_scores, exam_score, student_id)
- New Columns (Feature Engineering): 4 (hours_study, sleep_pattern, previous_scores_range, exam_range, exam_result)

## Exploratory Data Analysis:
- Distribution of study hours and sleep hours.
- Attendance patterns and correlation with exam results.
- Visualizations like bar plots, pie charts, and heatmaps.
- Multi-variate analysis to see relationships between features.

## Feature Engineering:
- Binned `hours_studied` into categories like '1 to 3 hours', '4 to 6 hours'.
- Binned `sleep_hours` into sleep patterns like '4 to 5 hours', '6 to 7 hours'.
- Converted `previous_scores` and `exam_score` into ranges using CBSE grading.
- Added `exam_result` column (Passed/Failed) based on exam score.

## Machine Learning Models:
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

### Evaluation Metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
  

## CBSE Grading Pattern

## Marks Range 	## Grade	## Grade Point
  91-100	      A1	         10.0
  81-90	        A2	         9.0
  71-80	        B1	         8.0
  61-70	        B2	         7.0
  51-60	        C1	         6.0
  41-50	        C2	         5.0
  33-40	        D	           4.0
  21-32	        E1	         0.0
  00-20	        E2	         0.0

## Conclusion
Study habits, sleep, and attendance strongly affect exam performance.
Linear Regression and Ridge Regression provide good predictions.
Students with consistent study hours and better attendance tend to score higher.
