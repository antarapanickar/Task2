# Titanic EDA – Task 2

This is the submission for the second task of the internship which is on performing Exploratory Data Analysis using the Titanic dataset.

## What I Did

- Loaded the Titanic dataset using pandas
- Observed the structure of the data via `head()`, `info()`, and `describe()`
- Checked for missing data and basic statistics
- Plotted histograms (Age, Fare), boxplots, and a heatmap of correlation using seaborn and matplotlib
- Explored the relationships between features, i.e., Pclass, Fare, and Survival

## Key Findings

- Age and Fare are not normally distributed — both right-skewed
- Some outliers are present in the Fare column
- Heavy negative correlation between Pclass and Fare
- Missing data present in some columns like Age and Cabin

## Tools Used

- Python (Jupyter Notebook)
- Libraries: pandas, seaborn, matplotlib

## Dataset

Used Titanic Dataset from Kaggle:  
https://www.kaggle.com/datasets/yasserh/titanic-dataset

## File Present in this Repo

- `EDA_Titanic.ipynb`: The notebook containing all codes and visualizations
- `Titanic-Dataset.csv`: The dataset file
