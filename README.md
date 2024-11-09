# Visa_Approval_EDA 🛫

## Overview
This project focuses on exploring and analyzing the visa approval dataset to uncover insights into various factors influencing visa approval outcomes. The dataset contains information about applicants, including details such as wage, region, job experience, education, and more, along with their visa approval status.

The main goal of the project is to provide a comprehensive exploratory data analysis (EDA) using Python to reveal patterns, correlations, and trends in visa approval data. The insights from this analysis will help us understand factors that may affect visa approval or denial.


# Key Libraries Used
This project relies on the following Python libraries:

Pandas: For data manipulation and aggregation.
Seaborn: For creating statistical plots and visualizations.
Matplotlib: For plot customization, styling, and display.
NumPy: For numerical operations and array manipulations.
SciPy/Statsmodels: For statistical tests and hypothesis testing.

# Data Description
The dataset used for this project contains multiple columns representing various features of the applicants. Some key features in the dataset include:

case_status: Status of visa application (Certified or Denied).
unit_of_wage: Wage type used in the application (hourly, weekly, monthly, or yearly).
education_of_employee: Education level of the employee (e.g., High School, Bachelor's, Master's, etc.).
prevailing_wage: The wage that is expected or mandated by law for the job.
requires_job_training: Whether the employee requires job training (yes/no).
region_of_employment: Region where the employee is employed.
yr_of_estab: Year the company was established.


# Steps in the Analysis

1. Data Preprocessing:
Cleaning and handling missing or invalid data.
Feature engineering: extracting meaningful columns for analysis.

2. Exploratory Data Analysis (EDA):

Univariate analysis: Investigating the distribution of individual features such as prevailing_wage, education_of_employee, etc.
Bivariate analysis: Exploring relationships between features such as how education_of_employee affects visa_status or how region_of_employment influences visa_status.
Visualization: Using various plots (box plots, histograms, bar charts) to identify trends and distributions in the data.

3. Statistical Analysis:
Performing hypothesis testing (e.g., Chi-square tests) to understand relationships between categorical variables and visa approval status.

# Key Insights
1. Effect of Education on Visa Status: We found that applicants with a higher education level (e.g., Master’s or Doctorate) were more likely to have their visa certified, while applicants with lower education levels had a higher denial rate.

2. Impact of Prevailing Wage on Visa Status: The analysis revealed that higher prevailing wages were generally associated with visa certifications, while lower wages had a higher correlation with visa denials.

3. Job Experience: Applicants with job experience were more likely to have their visas certified. This trend shows the importance of work experience in the visa approval process.

4. Year of Establishment: Companies established later (after 1900) tended to have higher approval rates, possibly indicating a relationship between company maturity and approval rates.

# Steps to Run:
1. Clone or download the project folder.
2. Place the visadataset.csv in the same directory as the notebook.
3. Open the visa_analysis.ipynb file in Jupyter Notebook or any IDE of your choice.
4. pip install pandas matplotlib seaborn numpy scipy (install necessary libraries if not)
5. Run the cells sequentially to see the exploratory analysis and visualizations.

# Conclusion
This project highlights the power of Exploratory Data Analysis (EDA) in deriving actionable insights from data. The analysis can be extended further by applying machine learning models to predict visa approvals based on the features explored in this EDA.

