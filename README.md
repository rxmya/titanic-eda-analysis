# Titanic Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic passenger dataset to identify patterns and factors associated with passenger survival.

The analysis explores passenger demographics, passenger class, age, fare, gender, and survival outcomes using Python-based data analysis and visualization techniques.

## Objective

The main objective of this project is to understand the Titanic dataset and identify important patterns related to passenger survival.

The analysis focuses on:

- Understanding the structure of the dataset
- Identifying and handling missing values
- Exploring passenger demographics
- Analyzing survival rates
- Comparing survival across gender and passenger class
- Analyzing survival across different age groups
- Studying the relationship between fare and survival
- Identifying correlations between numerical variables

## Dataset

The dataset contains information about Titanic passengers, including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Gender
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket
- Fare
- Cabin
- Port of embarkation

The dataset used in this project is the Titanic training dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
titanic-eda-analysis/
│
├── Titanic_EDA.ipynb
├── train.csv
└── README.md
```

## Analysis Performed

### 1. Data Understanding

The dataset was explored by checking:

- Dataset shape
- Column names
- Data types
- Dataset information
- Statistical summary
- Missing values

### 2. Data Cleaning

The following data-cleaning techniques were applied:

- Missing values in the `Age` column were replaced using the median.
- Missing values in the `Embarked` column were replaced using the mode.
- The `Cabin` column was removed because it contained a large proportion of missing values.
- The cleaned dataset was verified to ensure the required missing values were handled.

### 3. Univariate Analysis

Individual variables were analyzed to understand their distributions and frequencies.

The analysis included:

- Survival distribution
- Gender distribution
- Passenger class distribution
- Age distribution
- Fare distribution

The following visualizations were used:

- Count plots
- Histograms
- Distribution plots

### 4. Bivariate Analysis

Relationships between two variables were analyzed to identify factors associated with passenger survival.

The analysis included:

- Gender vs Survival
- Passenger Class vs Survival
- Age Group vs Survival
- Fare vs Survival

Bar plots and box plots were used to visualize these relationships.

### 5. Correlation Analysis

A correlation matrix was calculated for numerical variables.

A correlation heatmap was created to visually identify positive and negative relationships between numerical features.

## Key Findings

- Female passengers had a significantly higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Third-class passengers had the lowest survival rate.
- Survival rates varied across different age groups.
- Passengers who paid higher fares generally had better survival outcomes.
- Passenger class and fare showed a noticeable relationship.
- Gender and passenger class were among the important factors associated with survival.

## Conclusion

The Exploratory Data Analysis revealed several important patterns associated with Titanic passenger survival.

Female passengers and passengers from higher classes had considerably better survival outcomes compared with male and lower-class passengers.

The analysis also showed differences in survival across age groups and a relationship between ticket fare and survival.

Overall, this project demonstrates how Python, Pandas, NumPy, Matplotlib, and Seaborn can be used to perform data cleaning, exploratory analysis, visualization, correlation analysis, and insight generation from a real-world dataset.
