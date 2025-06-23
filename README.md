# Titanic-Data-Preprocessing
Task 1: Data cleaning &amp; preprocessing on Titanic dataset

Titanic Dataset - Data Cleaning & Preprocessing:
This is Task 1 of my AI/ML Internship – focusing on cleaning and preparing raw data for Machine Learning.

Task Objective :
- Handle missing values
- Encode categorical variables
- Normalize/Standardize numerical features
- Remove outliers
- Save the cleaned dataset

 Dataset:
- Source: [Titanic Dataset from Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `Titanic-Dataset.csv`

 Technologies Used:
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

 Preprocessing Steps :
1. Explored the dataset for nulls and data types
2. Imputed missing values using median/mode
3. Dropped the `Cabin` column due to too many nulls
4. Used one-hot encoding for `Sex` and `Embarked`
5. Standardized `Age` and `Fare` using `StandardScaler`
6. Detected and removed outliers using IQR

Output: 
- Cleaned file: `cleaned_titanic.csv`
- Python Notebook: `Titanic_Data_Preprocessing.ipynb`
