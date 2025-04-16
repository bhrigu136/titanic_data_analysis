# 🚢 Titanic Survival Prediction 

## 📘 Project Overview

This project uses the Titanic dataset from Kaggle to build a classification model that predicts passenger survival based on features like gender, age, class, and more, we identify key patterns that influenced survival rates. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning models.

---

## 📂 Project Structure


---

## 📁 Dataset
- Files used: `train.csv`
  
---

## 🧹 Workflow Summary

### 1. **Data Cleaning**
- Handled missing values in `Age` and `Embarked`.
- Dropped less useful or highly missing columns like `Cabin` and `Ticket`.

### 2. Exploratory Data Analysis (EDA)
- We explored:

- Survival Count
- Class-based survival
- Gender-based survival
- Age distribution
- Overall Survival Count
  
- Used seaborn and matplotlib for clear graphical insights.

### 3. Feature Engineering
- Created new features like `FamilySize`, `IsAlone`, and `Title` extracted from names.
- Encoded categorical variables using `LabelEncoder`.

### 4. Model Building
- Used two supervised models:
  - **Logistic Regression** (baseline model)
  - **Random Forest Classifier** (ensemble model)
- Performed a train-test split for validation.

### 5. Model Evaluation
- Accuracy scores for both models.
- Confusion matrix visualization.
- Feature importance plot for Random Forest.

---

## 📈 Results

| Model               | Accuracy (Approx.) |
|--------------------|--------------------|
| Logistic Regression| ~77%               |
| Random Forest      | ~83%               |

> 📝 Note: Exact accuracy may vary depending on random split and data processing.

---

## 🔍 Key Insights

- Gender was a strong predictor of survival — females had a higher survival rate.
- Passenger Class (Pclass) and Title also had significant impact.
- FamilySize and IsAlone provided additional context for survival chances.

---

## 🛠️ Tools & Libraries

- Pandas & NumPy – Data manipulation
- Matplotlib & Seaborn – Visualization
- Scikit-learn – ML models
- Jupyter Notebook

---

## 📌 How to Run

1. Clone the repo or download the `.ipynb` or `.py` file.
2. Make sure you have the required libraries:
   
   pip install pandas numpy matplotlib seaborn scikit-learn
