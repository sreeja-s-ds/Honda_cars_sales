# Honda_cars_sales

🚗 **Honda Car Dataset – Statistical Hypothesis Testing**

This project performs a comprehensive statistical analysis on a Honda car sales dataset, focusing exclusively on hypothesis testing techniques.

📌 **Objective**

To apply inferential statistics on a real-world car dataset using:

T-tests for comparing two numeric groups

ANOVA (F-tests) for comparing multiple numeric groups

Chi-Square tests for relationships between categorical variables

🔍 **Dataset Overview**

The dataset contains features such as:

Price

kms Driven

Fuel Type

Suspension

Car Model

Year

🧼 **Data Preparation**

The script includes:

Cleaning and converting Price (from Lakhs) and kms Driven (from text) to numeric values

Removing duplicates

Label encoding categorical variables: Fuel Type, Suspension, and Car Model

📊 **Statistical Tests Applied**

No.	Hypothesis Question	Test Type

1	Do automatic cars have higher prices than manual cars?	T-test

2	Do petrol vs diesel cars show a difference in kilometers driven?	T-test

3	Is there a relationship between fuel type and suspension type?	Chi-Square

4	Does price differ significantly across different fuel types?	ANOVA

5	Is car model associated with suspension type?	Chi-Square

6	Do newer cars (2015+) cost significantly more than older ones?	T-test

7	Do cars from different years show different average kilometers driven?	ANOVA

8	Is car model associated with fuel type?	Chi-Square

9	Is there a price difference among the top 3 car models?	ANOVA

10	Do cars with more than 50,000 kms have lower prices than those below?	T-test

✅ **Output**

Each test returns:

A p-value

A binary answer (Significant or Not) based on a 0.05 alpha level

📦**Libraries Used**

pandas

numpy

scipy

sklearn

📚 **Learning Highlights**

Real-world application of hypothesis testing

Proper data preprocessing techniques

Interpretation of statistical significance in business context

📌 **Author Notes**

This project was created as part of a Data Science learning path, with a focus on exploratory and inferential analysis.
