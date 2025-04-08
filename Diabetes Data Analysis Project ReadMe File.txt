# Diabetes Data Analysis Project

## Overview

This project involves the analysis of a healthcare-related dataset focused on diabetes. The primary goal is to explore the data, understand the relationships between various health metrics and diabetes diagnosis, and potentially build predictive models. The analysis includes data cleaning, exploratory data analysis (EDA), statistical analysis, and visualization.

## Dataset

The dataset used in this project is `Healthcare-Diabetes.csv`. It contains patient information with features related to health measurements and a binary outcome variable indicating the presence or absence of diabetes.

### Features:

* `Id`: Unique identifier for each patient.
* `Pregnancies`: Number of times pregnant.
* `Glucose`: Plasma glucose concentration.
* `BloodPressure`: Diastolic blood pressure.
* `SkinThickness`: Triceps skin fold thickness.
* `Insulin`: 2-Hour serum insulin.
* `BMI`: Body mass index.
* `DiabetesPedigreeFunction`: Diabetes pedigree function (genetic predisposition).
* `Age`: Age in years.
* `Outcome`: Target variable (0 = no diabetes, 1 = diabetes).

## Project Structure

The project is structured as follows:

1.  **Data Loading and Initial Exploration:**
    * Loading the dataset using pandas.
    * Displaying basic information about the data (data types, missing values).
    * Previewing the first few rows.
2.  **Data Cleaning and Preprocessing:**
    * Handling missing values (replacing zeros with NaN and imputing).
    * Outlier detection and handling.
    * Data type conversion (if necessary).
    * Binning continuous variables (e.g., Age, Glucose, BloodPressure).
3.  **Exploratory Data Analysis (EDA):**
    * Univariate analysis (distributions of individual features using histograms and KDE plots).
    * Bivariate analysis (relationships between pairs of features, including scatter plots and box plots).
    * Multivariate analysis (pair plots).
    * Stratified analysis (analyzing distributions across age groups).
    * Correlation analysis (using heatmaps).
4.  **Statistical Analysis:**
    * T-tests to compare means between outcome groups.
    * ANOVA to compare means across multiple groups (e.g., age groups).
    * Chi-square tests for categorical relationships.
5.  **Predictive Modeling (If applicable):**
    * Model selection (e.g., Logistic Regression, Decision Trees, Random Forests).
    * Model training and evaluation.
    * Hyperparameter tuning.
    * Feature importance analysis.
    * ROC curve analysis.
6.  **Results and Visualization:**
    * Creating various visualizations to support findings (histograms, KDE plots, box plots, scatter plots, pair plots, ROC curves).
    * Generating summary statistics.
    * Developing an interactive dashboard (if feasible).
7.  **Conclusion and Recommendations:**
    * Summarizing key findings.
    * Providing insights and actionable recommendations.

## Key Findings (Based on Provided Images)

* **Class Imbalance:** The dataset exhibits a class imbalance, with more individuals without diabetes than with diabetes.
* **Glucose as a Strong Predictor:** Glucose levels are a strong discriminator between diabetic and non-diabetic individuals.
* **BMI, Age, and BloodPressure as Risk Factors:** Higher BMI, older age, and higher blood pressure are associated with diabetes.
* **Insulin Issues:** The distribution of Insulin shows unusual patterns, potentially indicating data quality issues.
* **Overfitting Concern:** The Random Forest model showed a perfect AUC, raising concerns about overfitting.
* **Tuned Logistic Regression Performance:** Tuned Logistic Regression achieves a good AUC, indicating effective discrimination.
* **Age-Related Glucose Differences:** Glucose distributions vary across age groups, with older groups showing more distinct separation between diabetic and non-diabetic individuals.

## Visualizations

The project includes various visualizations, such as:

* Histograms and KDE plots to show feature distributions.
* Box plots to compare feature distributions across outcome groups.
* Scatter plots to visualize relationships between two continuous variables.
* Pair plots to explore multivariate relationships.
* ROC curves to evaluate model performance.
* Bar charts to show class distribution.

## Tools and Technologies

* Python
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* Jupyter Notebook

## How to Run the Analysis

1.  Ensure you have Python and the required libraries installed.
2.  Place the `Healthcare-Diabetes.csv` file in the appropriate directory.
3.  Run the Jupyter Notebook containing the analysis code.

## Future Work

* Address the overfitting issue in the Random Forest model.
* Conduct more rigorous hyperparameter tuning.
* Explore advanced feature engineering techniques.
* Develop an interactive dashboard for better data exploration.
* Validate findings on an external dataset.

## Author

\[M.Junaid Iqbal]

## Date

\[April 8th,2025]