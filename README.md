# Project Description

This project involves the analysis of data about bank customers, including information about the number of children, employment duration, age, education, marital status, gender, income type, debt status, total income, and loan purpose.

## Project Goal

The goal of this study is to identify relationships between various customer parameters and the likelihood of loan repayment on time. This analysis enables the bank to make more informed decisions regarding loan approvals and interest rates.

## Tools and Libraries

The following tools and libraries were used for this project:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Steps

### Step 1: Explore General Data Information

- Import the Pandas library and read data from a CSV file.
- Display the first 20 rows of data.

### Step 2: Data Preprocessing

- Remove missing values.
- Handle anomalous values.
- Change data types.
- Handle duplicates.
- Categorize data.

### Step 3: Explore Data and Answer Questions

- Analyze the relationship between the number of children and loan repayment on time.
- Examine the impact of marital status on loan repayment on time.
- Investigate the influence of income level on loan repayment on time.
- Explore how different loan purposes affect timely loan repayment.

### Step 4: Conclusion

Summarize the results and conclusions regarding the reliability of borrowers. Provide recommendations for the bank.

## Findings

- The presence of children affects the probability of loan repayment on time: borrowers without children are more reliable.
- Marital status also influences borrower reliability: widows/widowers and divorced individuals are more reliable compared to single individuals.
- Income level has an impact on the probability of loan repayment: clients with higher incomes are more reliable.
- The purpose of the loan also matters: loans for real estate transactions have the lowest default rate, while loans for car transactions have the highest.

## Possible Reasons for Data Gaps

Data gaps may be due to human error, technical issues during data transfer, or the absence of certain information from clients.

## Why Filling Missing Values with Medians Is the Best Solution for Scale Variables

Filling missing values with median values is the best solution for scale variables because the median is a robust metric that is not influenced by extreme values, making it preferable for smoothing the impact of outliers on the overall dataset.

## General Conclusion

The analysis of bank customer data has revealed important factors influencing the likelihood of loan repayment on time. These findings can be utilized by the bank to implement a more effective loan strategy and risk management.
