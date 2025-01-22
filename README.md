# Postcode Financial Analysis Project 📊📍

This project analyzes an ATO dataset containing tax and income details across Australian postcodes. The goal is to explore patterns in income, deductions, rent, and business activity while identifying key factors influencing financial outcomes. Advanced data analysis, clustering, and machine learning techniques are applied to uncover insights.

## Techniques and Methodology

### 1. **Exploratory Data Analysis**
- Explored relationships between income, deductions, rent, and financial metrics.
- Cleaned the dataset and handled missing values to ensure accuracy.
- Conducted univariate and bivariate visualizations to identify patterns and relationships.

### 2. **Clustering with K-Means**
- Categorized postcodes into distinct financial groups based on income levels, business activity, and deductions.
- Used scatter plots to visualize clusters and interpret group characteristics.

### 3. **Machine Learning**
- Built a linear regression model to predict total income using socio-economic features.
- Applied Recursive Feature Elimination (RFE) to refine the model by selecting the most influential features.
- Scaled the data for improved performance and feature reduction.

### 4. **Visualization**
- Created various visualizations to highlight key trends and insights:
  - Scatter plots to display clusters and relationships.
  - Predicted vs. actual values for regression results.

## Key Questions Answered
1. **Clustering Analysis:** 
   - How many distinct financial groups exist across postcodes based on income, deductions, and other metrics?
2. **Feature Importance:** 
   - What factors most influence financial outcomes such as taxable income, total income, and deductions?

## Tools and Technologies
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Project Highlights
- Identified meaningful clusters of postcodes based on financial metrics using K-Means.
- Built a refined linear regression model through RFE to predict total income accurately.
- Generated clear and insightful visualizations for better understanding of financial trends.
