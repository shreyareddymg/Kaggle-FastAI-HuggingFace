# Kaggle Dataset Analysis: Titanic Dataset

## Objectives
- Explore a Kaggle dataset using Python and Colab.
- Perform basic data cleaning, visualization, and summary statistics.
- Understand patterns like survival rate by gender, age, and class.

## Dataset Information
- **Name:** Titanic Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/heptapod/titanic)
- **Number of rows:** 1309
- **Number of columns:** 9 (after cleaning)
- **Column Description:**
  - `Passengerid` → Passenger ID
  - `Age` → Age of passenger
  - `Fare` → Ticket fare
  - `Sex` → Gender (0=Male, 1=Female, mapped to Male/Female)
  - `sibsp` → Siblings/Spouses aboard
  - `Parch` → Parents/Children aboard
  - `Pclass` → Passenger class
  - `Embarked` → Port of Embarkation
  - `Survived` → Survival status (0=Not Survived, 1=Survived, mapped for plots)

## Data Cleaning Steps
- Dropped irrelevant columns (like `zero`, `zero.1`, etc.).
- Mapped `Sex` and `Survived` to readable labels.
- Checked for missing values (`Age` or `Embarked`).

## Analysis / Visualizations
- **Passenger Survival Count:** Most passengers did not survive (~74%).
- **Survival by Gender:** Females had higher survival rate than males.
- **Survival by Passenger Class:** Passengers in Class 1 survived more than Class 3.
- **Age Distribution:** Most passengers were aged 20–40.
- **Fare Distribution:** Higher fares mostly correspond to Class 1 passengers.

## Files in this folder
- `titanic_clean.csv` → Cleaned dataset ready for analysis
- `titanic_summary.csv` → Summary statistics
- `Titanic_Analysis.ipynb` → Colab notebook with all code, visualizations, and observations
