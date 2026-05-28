Austo Automobiles – Data-driven Insights using Python
📌 Project Overview

This project analyzes customer and automobile purchase data for Austo Motor Company, a leading car manufacturer specializing in SUVs, Sedans, and Hatchbacks.

The goal is to perform exploratory data analysis (EDA) and generate business insights to improve marketing strategies and customer targeting.

The analysis is done using Python and focuses on understanding customer behavior, income patterns, loans, and automobile preferences.

🎯 Objective

The main objective of this project is to:

Understand customer demographics and purchasing behavior
Identify factors influencing automobile purchases
Analyze relationships between salary, loans, gender, marital status, and car preference
Provide data-driven recommendations for marketing strategy improvement
<img width="984" height="548" alt="1" src="https://github.com/user-attachments/assets/8da00030-c5a9-4c99-9f19-1fbd45c9a52b" />

<img width="987" height="551" alt="Capture" src="https://github.com/user-attachments/assets/0e1c402b-3dd7-48ad-bd79-b9b44d79c7a4" />


<img width="618" height="394" alt="image" src="https://github.com/user-attachments/assets/fbf2d380-6519-419d-9cb8-7706cb2a0d99" />


📊 Dataset Description

The dataset includes the following features:

Age: Age of the individual
Gender: Male or Female
Profession: Occupation type
Marital_status: Married or Single
Education: Graduate / Post Graduate
No_of_Dependents: Number of dependents
Personal_loan: Whether the customer has a personal loan (Yes/No)
House_loan: Whether the customer has a housing loan (Yes/No)
Partner_working: Whether partner is employed (Yes/No)
Salary: Individual income
Partner_salary: Partner income
Total_salary: Combined income
Price: Price of automobile purchased (in $)
Make: Type of automobile (SUV, Sedan, Hatchback)
🛠️ Tools & Technologies Used
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook / Google Colab


📈 Analysis Performed

The project includes:

🔹 Data Preprocessing
Handling missing values
Fixing incorrect gender entries
Outlier treatment using statistical methods (IQR)
Feature correction and cleaning
🔹 Exploratory Data Analysis (EDA)
✔️ Univariate Analysis
Distribution of age, salary, price
Frequency of gender, profession, car type
✔️ Bivariate Analysis
Gender vs Car type preference
Salary vs Price
Loan status vs Purchase behavior
✔️ Multivariate Analysis
Gender + Marital status + Purchase behavior
Partner working status vs car price
Combined salary vs automobile preference
📊 Business Questions Answered
Do men prefer SUVs more than women?
What is the likelihood of salaried individuals buying Sedans?
Does being a salaried male increase SUV purchases?
How does spending vary by gender?
Does having a personal loan affect car purchasing?
Does a working partner influence buying higher-priced cars?
Which customer segments should be targeted for marketing?
💡 Key Insights
Salary and total income strongly influence car price decisions
SUVs are more preferred among higher-income groups
Customers with working partners tend to purchase higher-priced vehicles
Gender and marital status significantly affect buying behavior
Personal loans reduce likelihood of high-value purchases
📌 Business Recommendations
Target high-income salaried males for SUV campaigns
Focus Sedan promotions on middle-income groups
Offer financing options for customers with loans
Create separate marketing strategies based on gender + marital status segments
Prioritize customers with dual incomes (working partner households)
Austo-Automobiles-EDA/
│
├── data/
│   └── dataset.csv
│
├── notebook/
│   └── analysis.ipynb
│
├── report/
│   └── business_report.pdf
│
├── README.md
