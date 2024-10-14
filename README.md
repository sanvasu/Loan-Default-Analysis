# Loan-Default-Analysis
Analyze the factors contributing to loan defaults to improve risk management and loan approval strategies. This project provides an opportunity to enhance risk assessment strategies in lending institutions, leading to more informed decision-making and proactive default prevention measures.

**About Data**

The loan default dataset contains detailed information about loans that have either been repaid or defaulted. Each record represents an individual loan, with a variety of associated attributes, such as loan limit, loan purpose, loan amount, rate of interest, income, region of the borrower and more.

Features of the Loan Default Dataset

| Feature |	Description |
| ---------- | -------------- |
| Id |	Id for each row |
| Year	| Year when loan was taken |
| Loan limit	| If the loan limit is fixed or variable cf-confirm/fixed, ncf- not confirm/not fixed |
| Gender |	Gender of applicant |
| Loan type	| Type of loan (masked data) |
| Loan purpose	|Purpose of loan (masked data) |
| Business or Commercial	| Business or Personal loan |
| Loan amount	| Total loan amount |
| Rate of interest	| Interest on loan |
| Upfront Charges |	Down Payment |
| Property value |	Value of Property |
| Occupancy type |	Type of establishment |
| Income |	Income of applicant |
| Credit type |	'EXP' 'EQUI' 'CRIF' 'CIB' |
| Credit score |	Credit score of applicant |
| Co-applicant credit type |	Credit type of co-applicant |
| Age	| Age of applicant |
| LTV	| Lifetime value of applicant |
|Region	| Region of applicantStatus	Defaulter(1) or Compliant(0) |

**Exploratory Data Analysis (EDA)**

We will perform exploratory data analysis (EDA) to gain insights into the dataset, identify patterns, and understand the relationships between various features.

* There are total 148670 records presented in the provided dataset.
* Upfront charges column have 26% of null values and Rate of Interest column have 24% of null values. Some other columns have minor number of null values.
* For numerical columns the missing values are replaced with Mode and Median Values.

**Insights**
* Medium-Low Income band peoples are having more number of defaulters.
* Higher loan amount is having more number of defaulters.
* Male clients are having more number of defaulters.
* South and North Region peoples are higher number of defaulters
* Compared to Business loans people are getting more number of Personal loans.
* P3 type of loans are more number of defaulters.

**Recommendations**
* More loans to female customers: Since fewer female customers default, increase loan opportunities for women to reduce overall risk.
* Focus on the Central and Northeast regions: These regions show fewer defaults, so prioritize lending there for better loan performance.
* Target younger age group (25-44): Younger individuals (25-44) should be prioritized as they likely have more earning years ahead and lower default risks.
* Increase commercial loans: As commercial loans have a lower default rate, expand offerings in this category to support business growth.
* Diversify loan types: Instead of focusing on just one loan type (type1), ensure equal distribution across all loan types to reduce concentration risk.
