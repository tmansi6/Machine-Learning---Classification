# Machine_Learning-Classification
Predicting Heart Disease Using Machine Learning: Study of Logistic Regression and Random Forest Models.

## 📌 Project Overview  
This project analyzes a heart disease dataset to develop machine learning models for predicting the presence or absence of heart disease. The analysis involves preprocessing, exploratory data analysis (EDA), model training, hyperparameter tuning, and evaluation.

## 📊 Dataset  
Download Dataset from: [Kaggle - Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

The dataset includes features like:
* Independent Variables (Features):
  - Age: Age of the patient in years.
  - Sex: Gender (1 = male, 0 = female).
  - ChestPain Type: Chest pain type (categorical).
  - RestingBP: Resting blood pressure (mm Hg).
  - Cholesterol: Serum cholesterol (mg/dl).
  - FastingBS: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false).
  - RestingECG: Resting electrocardiographic results (categorical).
  - MaxHR: Maximum heart rate achieved.
  - ExerciseAngina: Exercise-induced angina (1 = yes, 0 = no).
  - Oldpeak: ST depression induced by exercise relative to rest.
  - ST_Slope: Slope of the peak exercise ST segment (categorical).
* Dependent Variable (Target):
  - HeartDsease: Presence of heart disease (1 = disease, 0 = no disease).

## 🛠️ Technologies & Tools  
- Python
- Jupyter Notebook  
- Pandas, NumPy – Data processing  
- Matplotlib, Seaborn – Data visualization  
- Scikit-learn – Machine Learning models

## ⚙️ Machine Learning Models Used  
We compare two ML models for heart disease prediction:  
| Model                 | Accuracy |
|-----------------------|----------|
| Logistic Regression   |    85%   |
| Random Forest         |    89%   |
📌 Conclusion: The Random Forest model performed better.


