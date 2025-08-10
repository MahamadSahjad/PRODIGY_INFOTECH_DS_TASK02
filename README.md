# PRODIGY_INFOTECH_DS_TASK02
Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic dataset as part of my Prodigy InfoTech Data Science Virtual Internship. Includes feature engineering, visualizations, and key survival insights.

🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)
About the Project
This project is part of my Prodigy InfoTech Virtual Internship (Data Science). The objective was to perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset to discover patterns, correlations, and insights into survival outcomes.

The work involves:

Handling missing values

Feature engineering

Data visualization

Insight generation

Objectives

Clean and preprocess raw Titanic data

Explore variable relationships with survival

Visualize trends and distributions

Identify key predictors of survival

Dataset

Source: Kaggle Titanic Dataset or DataScienceDojo GitHub Link

Size: 891 rows × 12 columns (original dataset)

Tools & Libraries

Python

Pandas – Data manipulation & analysis

NumPy – Numerical computations

Matplotlib – Data visualization

Seaborn – Statistical graphics

Analysis Workflow

Data Loading – Imported dataset directly from a GitHub source.

Data Cleaning – Filled missing Age with median values, replaced missing Embarked with the mode, and dropped Cabin due to excessive missing values.

Feature Engineering – Extracted Title from passenger names, created FamilySize and IsAlone features, binned Age and Fare into categorical ranges.

Exploratory Data Analysis – Performed univariate, bivariate, and correlation analysis to uncover patterns.

Key Insights & Conclusion

Gender Disparity – Females had a far higher survival rate than males, reflecting the "women and children first" policy.

Passenger Class Impact – Third-class passengers had the lowest survival rate despite being the largest group.

Gender × Class Interaction – Males from third class faced the highest risk.

Age Influence – Young adults had the lowest survival rate.

Key Predictors – Fare, Sex, Passenger Class, and Embarked location strongly correlated with survival.

This analysis reinforces how social norms, economic status, and demographics collectively influenced survival outcomes.

Visualizations

Survival Count – Distribution of survival (0 = No, 1 = Yes)

Age Distribution – Age distribution of passengers

Survival by Gender – Gender vs. Survival comparison

Correlation Heatmap – Correlation matrix between features

How to Run This Project

Clone the repository

Navigate to the project folder

Install dependencies from requirements.txt

Run the Jupyter Notebook

Folder Structure

data/ – Dataset files

images/ – Saved plot images

Prodigy_Task_02_EDA_Titanic.ipynb – Main notebook

README.md – Project documentation

requirements.txt – Dependencies list

LICENSE – License file

Connect with Me
Name: Mahamad Sahjad Dewan
