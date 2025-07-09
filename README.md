#  Titanic Survival Prediction Project

This project is an end-to-end data analysis and machine learning pipeline built on the classic 
**Titanic dataset** from [Kaggle](https://www.kaggle.com/c/titanic/data).  
It covers **data cleaning, exploratory data analysis (EDA), feature engineering, multiple model training, evaluation, and final model comparison.**

---

##  **Project Objectives**

- Perform data cleaning to handle missing values and irrelevant features.
- Conduct EDA to understand passenger survival patterns.
- Engineer useful features (like `FamilySize`) to improve prediction.
- Build and compare multiple classification models:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Naive Bayes
  - K-Nearest Neighbors (KNN)
  - Decision Tree
- Evaluate models using accuracy score and confusion matrix.
- Visualize the final model comparison.

---
##  **Steps Performed**

###  1. Data Cleaning
- Filled missing `Age` with median.
- Filled missing `Embarked` with mode.
- Dropped `Cabin` due to excessive missing values.

### 2. Exploratory Data Analysis (EDA)
- Survival distribution by `Sex` and `Pclass`.
- Age distribution.
- Correlation heatmap for numeric features.

###  3. Feature Engineering
- Created `FamilySize` 

###  4. Data Preprocessing
- Encoded categorical variables (`Sex`, `Embarked`) using `get_dummies`.
- Scaled numeric features using `StandardScaler`.

### 5. Model Training & Evaluation
- Split data using `train_test_split` (70% train, 30% test).
- Trained and tested multiple models.
- Used accuracy score and confusion matrix to evaluate performance.

---
###  Key Findings

- **Females and children had higher survival rates** compared to adult males.
- **Passengers in higher classes (1st class)** had a significantly better chance of survival than those in 2nd or 3rd class.
- **Fare amount** was positively correlated with survival — passengers who paid higher fares were more likely to survive.
- **Family size** played a role: passengers traveling with small families had slightly higher survival rates than those alone or with very large families.
- **Naive Bayes** performed best on this dataset.
- Logistic Regression came close.

### Tools Used
Python 
Pandas, NumPy,Matplotlib, Seaborn,Scikit-learn

### Author
VAISHNAVI MOHITE

https://www.linkedin.com/in/vaishnavi-mohite-082069319/ | https://github.com/Vaishnavi231004 | mohitevaishnavi2310@gmail.com
