# Heart-Disease-Analysis
This project investigates a dataset of heart disease patients to determine patterns and build predictive models for diagnosing heart disease. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and building classification models.

## Dataset
The dataset used in this analysis is publicly available and can be accessed here: [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/data)  
The dataset contains several features related to patients' health, including:
- Age, sex, and other demographic information
- Various medical attributes (cholesterol levels, blood pressure, etc.)
- Target variable indicating heart disease diagnosis (presence or absence of heart disease)

## Installation
To run this notebook, you'll need Python and Jupyter Notebook installed along with the following libraries:
- pandas
- matplotlib
- seaborn
- numpy

Install the dependencies using:  
```bash
pip install pandas numpy matplotlib seaborn
```

## Project Structure
- **heart_disease_analysis.ipynb :** Jupyter notebook with all the steps of data analysis, EDA, and model training.
- **README.md :** Project overview and explanations of the steps taken in the notebook.

## Exploratory Data Analysis (EDA)
The EDA examines relationships between features and the target variable to identify patterns, trends, and correlations. Key steps include:
- **Data Cleaning:** Handling missing values, outliers, and feature scaling.
- **Feature Correlation:** Identifying significant features that have a strong relationship with heart disease.
- **Visualization:** Graphical representation of data using histograms, scatter plots, heatmaps, etc., to gain insights into feature distribution and relationships.

## Analysis
### Correlation Matrix

### Age Distribution Histogram
- **Description:** Visualizes the distribution of patients' ages with a histogram and KDE overlay.
- **Observation:** Shows the most common age ranges and identifies any skewness in the age data.

### Count of Individuals with and without Heart Disease
- **Description:** A count plot illustrating the prevalence of heart disease in the dataset.
- **Observation:** Helps to understand the proportion of patients with heart disease, essential for assessing class imbalance in predictive modeling.

### Gender Distribution
- **Description:** A count plot for gender distribution.
- **Observation:** Provides insights into the gender breakdown, highlighting any imbalance which might affect analysis.

### Distribution of Males and Females by Heart Condition
- **Description:** A stacked bar plot showing the count of males and females with and without heart disease.
- **Observation:** Reveals potential gender differences in heart disease prevalence.

### Chest Pain Types Analysis
- **Description:** A count plot displaying various chest pain types.
- **Observation:** Identifies the frequency of different chest pain types and their potential link with heart disease.

### Distribution of Chest Pain Types by Heart Condition
- **Description:** Stacked bar plot showing how chest pain types differ between individuals with and without heart disease.
- **Observation:** Highlights which chest pain types are more commonly associated with heart disease.

### Percentage Distribution of Chest Pain Types by Heart Condition
- **Description:** A percentage-based stacked bar plot for chest pain types split by heart condition.
- **Observation:** Shows the proportion of each chest pain type, providing insight into their relative impact on heart disease.

### Distribution of Various Chest Pain Types by Gender
- **Description:** A stacked bar plot showing chest pain types across genders.
- **Observation:** Explores differences in chest pain type distributions between males and females.

### Distribution of Fasting Blood Sugar Levels by Heart Condition
- **Description:** Stacked bar plot illustrating the relationship between fasting blood sugar levels and heart disease.
- **Observation:** Examines the correlation between high fasting blood sugar and heart disease presence.

### Resting Blood Pressure Distribution
- **Description:** A histogram with KDE for resting blood pressure levels.
- **Observation:** Visualizes the distribution of blood pressure readings and helps identify common ranges and outliers.

### Resting Blood Pressure by Gender
- **Description:** Box plot comparing resting blood pressure levels across genders.
- **Observation:** Allows for gender-based comparison, showing if males or females have higher median blood pressure.

### Serum Cholesterol Distribution
- **Description:** Histogram with KDE overlay for serum cholesterol levels.
- **Observation:** Shows the spread and skewness in cholesterol values, with implications for risk assessment.

### Cholesterol Distribution by Age and Sex
- **Description:** Box plot of cholesterol levels by age, split by gender.
- **Observation:** Examines age-related trends and potential gender differences in cholesterol levels.
