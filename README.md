# Task 2: Exploratory Data Analysis (EDA)

This repository contains the second task of my internship at **Elevate Labs**, where I perform Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns and insights.

## 📌 Objective

Understand the Titanic dataset by analyzing its features using statistical methods and visualizations, which will inform the machine learning modeling phase.

- Generate summary statistics
- Create visualizations (histograms, boxplots, etc.)
- Investigate feature relationships
- Identify patterns, trends, and anomalies

## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly

## 🔍 Steps Performed

1. **Dataset Overview**  
   - Explored the structure of the dataset (column types, null values, etc.)
   - Identified key features like `Survived`, `Pclass`, `Sex`, `Fare`, and `Age`

2. **Summary Statistics**  
   - Generated descriptive statistics (mean, median, std, etc.) for numerical features.
   - Checked for data skewness and the presence of outliers.

3. **Data Visualizations**  
   - Created histograms and boxplots to understand the distribution of numerical features.
   - Used pairplots and correlation matrices to explore relationships between features.

4. **Feature-Level Inferences from Visuals**  
   - Analyzed patterns, such as higher survival rates for females and 1st class passengers.
   - Detected potential data issues like the lack of variation in the `Parch` column.

5. **Feature Selection**  
   - Dropped the `Parch` column due to its lack of variability.

## 📁 Files

- `task2.ipynb` - Notebook containing all EDA code
- `titanic_cleaned.csv` - Initial preprocessed dataset used in Task 2
- `titanic_cleaned_1.csv` - Updated dataset saved after dropping the `Parch` column
- `README.md` - This documentation

## 📊 Dataset

Dataset: [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset/data)
