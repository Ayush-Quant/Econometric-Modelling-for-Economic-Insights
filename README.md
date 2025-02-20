**Title  - Econometric Modelling for Economic Insights: Predicting GNI Using Financial Inclusion Indicators.**

This project analyzes the relationship between financial inclusion indicators and a country's Gross National Income (GNI) using econometric modeling. By leveraging regression techniques, the project identifies key predictors of GNI, providing insights into how financial access contributes to economic growth.

🚀 **Project Overview**

Objective: To explore whether financial inclusion indicators such as account ownership, income distribution, and education levels can significantly predict GNI.

**Key Features**:

Data cleaning and imputation using KNN.

Exploratory data analysis with visualizations.

Regression modeling with statistical diagnostics.

Feature selection using stepwise regression.

Analysis of residuals, multicollinearity, and heteroscedasticity.

📊 **Dataset**

**Source**: The dataset is sourced from the World Bank DataBank.

https://docs.google.com/spreadsheets/d/1nF5tMBvimmPv3_4b9BFQ4YdkDwRIciGK/edit?usp=sharing&ouid=117408249352149101367&rtpof=true&sd=true


**Variables:**
**Dependent Variable**: Gross National Income (GNI).

**Independent Variables**: Financial inclusion indicators such as:
Account ownership by gender, labor force status, and income group.
Educational attainment levels.
Labor force dynamics.

📂 **Project Structure**

ecotrix_final.py: Python script containing the code for data preprocessing, regression analysis, and visualization.

Econometric-Modelling-for-Economic-Insights.pdf: Detailed report documenting the methodology, findings, and conclusions.

Python Libraries Used:

pandas, numpy, seaborn, matplotlib for data handling and visualization.

statsmodels for regression analysis.

scikit-learn for imputation and scaling.

**Result and Findings:**

Financial inclusion metrics like labor force participation and primary education strongly influence GNI.

Gender disparities and income inequalities impact financial access and, consequently, economic outcomes.

The regression model highlights significant variables but acknowledges limitations due to low R-squared values.


📋 **Setup and Usage**

**Prerequisites:**

Python 3.8 or above.

Required libraries: Install using pip install -r requirements.txt (generate this file if needed).

Run the Script:

Upload the dataset to your working directory or modify the script for your dataset path.
Execute ecotrix_final.py to run the analysis.
