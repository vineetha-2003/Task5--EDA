# Titanic Dataset - Exploratory Data Analysis (Task 5)

# Objective
The goal of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, relationships, and important factors influencing survival.

# Dataset Overview
- **Dataset:** Titanic-Dataset.csv
- **Records:** 891 passengers
- **Features:** Passenger details like Age, Sex, Class, Fare, Embarked Port, Survival status

# Tools & Libraries Used
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Google Colab (for notebook execution)

# EDA Steps Performed
- Loaded and understood data using `.info()`, `.describe()`, and `.isnull().sum()`
- Univariate analysis: Age, Passenger Class, Survival Rate
- Bivariate analysis: Survival vs Gender, Survival vs Class, Age vs Fare scatter plot
- Multivariate analysis: Pairplot
- Correlation analysis: Heatmap showing relationships between numerical features
- Detected missing values in 'Age', 'Cabin', and 'Embarked' columns
- Summarized key findings from the analysis

# Key Insights
- Females had a much higher survival rate compared to males.
- First Class passengers were more likely to survive than Second or Third Class passengers.
- Younger passengers had slightly better chances of survival.
- High correlation between Fare and Passenger Class was observed.
- Missing values were mainly in 'Age', 'Cabin', and 'Embarked' fields.



