# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs detailed **Exploratory Data Analysis (EDA)** on the famous Titanic dataset using Python libraries: **Pandas**, **Matplotlib**, and **Seaborn**.

## 📁 Dataset

- **Source**: Titanic passenger data (CSV)
- **Columns Include**:
  - `Survived`: Survival (0 = No, 1 = Yes)
  - `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
  - `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`, etc.

## 📌 Objectives

- Understand the structure and quality of the data
- Visualize survival trends across various features
- Generate statistical insights to inform future modeling

## 🛠️ Tools Used

- Python 3.x
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

## 📊 Key Visualizations

- Survival distribution
- Survival by Gender, Class, Age Group, Embarkation Port
- Age and Fare distribution
- Family Size analysis
- Correlation heatmap

## 🧠 Key Insights

- **Females had a significantly higher survival rate** than males.
- **1st class passengers survived more** than 2nd and 3rd class.
- **Children (age < 12)** were more likely to survive.
- **Higher fares correlated with higher survival**.
- Passengers with small families had better chances of survival.
- Embarked from **Cherbourg (C)** → higher survival rate.

## 📂 File Structure

```bash
├── Titanic-Dataset.csv
├── Titanic_EDA.ipynb          # Jupyter notebook for EDA
└── README.md                  # This file
