%%writefile README.md
# Starbucks Customer Behavior Analysis

This Jupyter Notebook analyzes customer behavior data from a Starbucks customer survey in Malaysia.  The analysis aims to understand customer demographics, purchasing habits, and identify factors influencing customer retention and visit frequency.

## Business Objective

The primary goal is to answer the business question: What are the characteristics of customers who are likely to continue buying from Starbucks?

## Data

The dataset used in this analysis is a survey from Malaysia about Starbucks customer behavior.  It includes demographic information (gender, age, employment status, income) and customer behavior data (visit frequency, preferred ordering method, time spent, location proximity, membership status).

## Methodology

1. **Data Collection:** The dataset was loaded into a Pandas DataFrame.
2. **Data Preprocessing:** Missing values were handled using forward fill.  The dataset was already numerically encoded, so no additional encoding was necessary.
3. **Exploratory Data Analysis (EDA):** Summary statistics, count plots, and a correlation matrix were generated to understand the data distribution and relationships between variables.
4. **Statistical Analysis:**
    * **Logistic Regression:** Used to predict membership card ownership based on customer characteristics. Feature importance from the model highlighted key drivers of membership.
    * **Random Forest Classifier:** Used to predict customer visit frequency. The model's classification report, accuracy score, confusion matrix, and feature importance provided insights into the factors influencing visit patterns.
    * **KMeans Clustering:** Used to segment customers based on income and age, revealing distinct customer groups with varying characteristics.
5. **Interpretation and Insights:** The results of each analysis were interpreted to provide actionable recommendations for Starbucks.

## Key Findings and Recommendations

* **Membership Card Ownership:** Focus on high-income customers, frequent visitors, and those spending more time in-store with targeted promotions and loyalty programs.
* **Visit Frequency:** Analyze income, age, gender, preferred ordering method, location proximity, and membership status to design customized offers and promotions.
* **Customer Segmentation:** Tailor marketing strategies to the three identified customer segments based on income and age.
* **General Recommendations:** Enhance loyalty programs, personalize offers, collect regular customer feedback, monitor competitor activities, and improve the in-store experience.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn (Logistic Regression, Random Forest, KMeans)

## Repository Structure

This repository contains the Jupyter Notebook with the complete analysis.
