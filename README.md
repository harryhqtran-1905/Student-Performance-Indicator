# Student Performance Indicator

## Overview
Brief description of what this project does.

## Dataset
- Source: [Kaggle - Students Performance](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- Features: gender, race/ethnicity, parental education, lunch, test prep, scores

## Tools Used
- Python, Pandas, Matplotlib, Seaborn

## Keyfinding: 
- Female student outperform male student overall (dataset is 50/50 split)
- Parental education is associated with student scores but it is not a strict determinant
- Race/Ethnicity is associated with student score but it is not a strict determinant

## Model Performance: 
|Model Name	                |R2_Score   |
|---------------------------|-----------|
|Linear Regression	        |0.162172   |
|Ridge	                    |0.161946   |
|AdaBoost Regressor	        |0.105783   |
|Lasso	                    |0.068120   |
|Random Forest Regressor	|-0.019185  |
|K-Neighbors Regressor	    |-0.047842  |
|XGBRegressor	            |-0.070459  |
|Decision Tree	            |-0.079119  |

## How to Run
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open `EDA_student_performnace.ipynb`
