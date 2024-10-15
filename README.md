# Heart Disease Detection

## Problem Statement
The primary objective of this project is to predict the occurrence of heart disease using various machine learning techniques. By analyzing clinical parameters, the project aims to classify patients into those with heart disease and those without.

## Dataset Description
This dataset contains *303 rows and 14 columns*. It includes medical attributes that are critical for predicting heart disease.

| Num | Feature | Description |
| --- | --- | --- |
| 1  | Age | Age of the patient in years |
| 2  | Sex | Gender of the patient (1 = male; 0 = female) |
| 3  | cp | Chest pain type (0-3) |
| 4  | trestbps | Resting blood pressure (mm Hg) |
| 5  | chol | Serum cholesterol (mg/dl) |
| 6  | fbs | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| 7  | restecg | Resting electrocardiographic results (0-2) |
| 8  | thalach | Maximum heart rate achieved |
| 9  | exang | Exercise induced angina (1 = yes; 0 = no) |
| 10 | oldpeak | ST depression induced by exercise relative to rest |
| 11 | slope | Slope of the peak exercise ST segment (0-2) |
| 12 | ca | Number of major vessels colored by fluoroscopy (0-3) |
| 13 | thal | Thalium stress result (1, 3 = normal; 6 = fixed defect; 7 = reversible defect) |
| 14 | target | Target variable indicating heart disease presence (1 = yes; 0 = no) |

## Tools
The project utilizes tools such as pandas, NumPy, Matplotlib, and seaborn for data analysis and visualization. Machine learning models will be implemented using Scikit-Learn.

## Algorithms
### Supervised Learning
- Logistic Regression
- K-Nearest Neighbors
- Random Forest Classifier

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
