

# 🚢 Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

This repository contains **Task 2** of my **Data Science Internship**, where I worked on the Titanic dataset to perform data cleaning, exploratory data analysis (EDA), and uncover meaningful patterns related to survival.


## 🧠 Objective

* Clean and preprocess the Titanic dataset
* Handle missing data thoughtfully
* Explore and visualize the relationships between different variables
* Identify key patterns and insights about passenger survival


## 📁 Dataset

The dataset used is the classic **Titanic dataset** from [Kaggle](https://www.kaggle.com/competitions/titanic/data), containing information about passengers such as:

* Age, Sex, Passenger Class (Pclass)
* Ticket Fare, Family relations (SibSp & Parch)
* Embarkation Port, Survival outcome

---

## 🔧 Data Cleaning Steps

* Handled missing values in `Age` and `Embarked`
* Dropped `Cabin` due to high percentage of missing values
* Created new features like:

  * `FamilySize` = `SibSp` + `Parch`
  * `Title` extracted from passenger names


## 📊 EDA Highlights

* Survival rate is higher among:

  * Females
  * Passengers in 1st class
  * Younger age groups (especially children)
* Larger families had lower survival chances
* Higher fare correlated with better survival rate
* Visualization tools used: `seaborn`, `matplotlib`

---

## 📌 Key Findings

* **Gender and class** were strong predictors of survival
* **Fare and age** also showed interesting survival trends
* Engineered features like `FamilySize` helped uncover deeper insights

---

## 📎 Tools Used

* Python (Pandas, NumPy)
* Data Visualization: Seaborn, Matplotlib
* Jupyter Notebook / Google Colab

---




## 🙌 Acknowledgements

* Dataset source: [Kaggle Titanic Challenge](https://www.kaggle.com/competitions/titanic)
* This work was done as part of a Data Science Internship project.
