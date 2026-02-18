## 🚢 Titanic Survival Analysis – Data Cleaning & EDA
## 📌 Project Overview

This project focuses on cleaning and analyzing the Titanic passenger dataset obtained from Kaggle.
The main objective is to explore factors that influenced passenger survival using data cleaning, exploratory data analysis (EDA), and visualization techniques.

All analysis was performed using Python in Google Colab.

## 📁 Dataset

Source: Kaggle – Titanic Dataset
Link: https://www.kaggle.com/datasets/yasserh/titanic-dataset

File used: Titanic-Dataset.csv

Note: The dataset is not included in this repository.
Please download it directly from Kaggle using the link above.

## 🛠 Tools & Technologies

Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn

## 🧹 Data Cleaning Steps

The following preprocessing steps were applied:

Removed duplicate records

Handled missing values

Filled or removed null values in Age, Cabin, and Embarked columns

Converted data types where necessary

Renamed columns for clarity

Checked for outliers and inconsistencies

A cleaned dataset was prepared after these steps.

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

Survival rate by gender

Survival rate by passenger class

Age distribution of passengers

Fare distribution

Relationship between age, fare, and survival

Multiple visualizations were created to support these analyses.

## 🔍 Key Insights

Female passengers had a higher survival rate than males

Passengers in 1st class were more likely to survive

Younger passengers showed slightly better survival chances

Higher ticket fares were associated with higher survival probability

## 📂 Project Structure
Titanic-Survival-Analysis/

│

├── notebooks/

│      └── titanic_analysis.ipynb

│

└── README.md

## ▶ How to Run the Project

Download the dataset from the Kaggle link

Place Titanic-Dataset.csv in the same folder as the notebook (or update the file path in the code)

Open titanic_analysis.ipynb

Run all cells

## 📈 Visualizations

The following visualizations were created using Matplotlib and Seaborn:

- Survival Count Plot  
  Shows the number of passengers who survived and did not survive.

- Survival by Gender (Bar Chart)  
  Compares survival rates between male and female passengers.

- Survival by Passenger Class (Bar Chart)  
  Displays survival distribution across Pclass (1st, 2nd, 3rd).

- Age Distribution (Histogram)  
  Shows the distribution of passenger ages.

- Fare Distribution (Histogram)  
  Visualizes how ticket prices are distributed.

- Age vs Survival (Box Plot)  
  Compares age distributions of survivors and non-survivors.

- Fare vs Survival (Box Plot)  
  Shows the relationship between ticket fare and survival.

- Correlation Heatmap  
  Displays correlation between numerical features.

## 👤 Author

Ayan
