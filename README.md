# NYC Taxi Fare Prediction – Exploratory Data Analysis

## Project Overview

The New York City Taxi & Limousine Commission (NYC TLC) partnered with Automatidata to develop a regression model capable of predicting taxi ride fares.

Before building the predictive model, it is essential to perform **Exploratory Data Analysis (EDA)** to understand the dataset, detect anomalies, clean the data, and identify the most relevant variables for modeling.

This project focuses on analyzing NYC taxi trip data to uncover patterns, identify data issues, and prepare the dataset for future machine learning and regression analysis.

---

## Business Objective

The primary objective of this analysis is to:

- Explore NYC TLC taxi trip data
- Identify inconsistencies and anomalies
- Clean and structure the dataset
- Determine the most relevant variables for fare prediction
- Prepare the data for regression modeling

---

## Problem Statement

Initial exploratory data analysis revealed **data quality issues** that could negatively affect model performance.

One significant issue identified was:

- Trips with **total fare amounts recorded but a trip distance of 0**

These records appear to be **data anomalies or outliers** and could lead to inaccurate fare predictions if not addressed properly.

Handling such inconsistencies is a critical step before building a reliable predictive model.

---

## Key Insights

Through the initial EDA process, several important observations were made:

- **Trip distance** and **total fare amount** are the most significant variables in representing a taxi ride.
- Certain records contain **invalid or inconsistent data**, such as trips with a fare but no recorded distance.
- These anomalies must either be **removed or properly handled** before model training.

A scatter plot visualization was created to examine the relationship between:

- **Trip Distance**
- **Total Fare Amount**

The visualization helps illustrate how trip distance generally correlates with ride cost.

---

## Data Visualization

A **scatter plot created in Tableau** was used to visualize the relationship between:

- Trip Distance
- Total Amount

This visualization provides a clear representation of how ride distance influences fare prices and helps identify outliers in the dataset.

---

## Data Preparation Steps

The exploratory analysis includes the following steps:

1. **Understanding the dataset**
2. **Identifying missing values**
3. **Detecting anomalies and outliers**
4. **Cleaning inconsistent records**
5. **Exploring relationships between variables**
6. **Preparing the dataset for regression modeling**

---

## Proposed Solution

Based on the exploratory analysis:

- **Trip Distance** and **Total Amount** were identified as key variables.
- Outliers such as **trips with distance = 0 but a recorded fare** should be removed or handled during preprocessing.
- Visualization techniques were used to better understand relationships within the data.

This approach ensures the dataset becomes more reliable for future predictive modeling.

---

## Next Steps

The following steps will be taken in the next phase of the project:

- Identify additional **unusual data points** that could affect fare prediction.
- Confirm with NYC TLC that the provided dataset sample accurately represents the full dataset.
- Develop a strategy for handling other potential outliers, such as:
  - Short trip distances with unusually high fares
  - Trips with longer durations but lower costs
- Identify variables with the **strongest influence on trip fares**.
- Select the most relevant features for:
  - Regression modeling
  - Statistical analysis
  - Model parameter tuning

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Tableau
- Jupyter Notebook

---

## Expected Outcome

This analysis will provide a **clean, structured dataset** and identify the most relevant variables required to build an accurate **taxi fare prediction regression model**.

---

## Author

This project was completed as part of a **data analytics project focusing on exploratory data analysis and predictive modeling preparation using NYC Taxi & Limousine Commission data.**

