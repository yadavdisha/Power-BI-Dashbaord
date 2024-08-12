## 📊 Bank Loan Report Dashboard
## 🔍 Overview
Welcome to the Bank Loan Report Dashboard project! This repository showcases a comprehensive Power BI solution designed to visualize and analyze key metrics related to bank loan applications. The project is divided into three main dashboards: Summary, Overview, and Details. Each dashboard is carefully crafted to provide unique insights into different aspects of the bank's loan portfolio.

# 1️⃣ Summary Dashboard
The Summary Dashboard offers a high-level overview of the bank’s loan performance. Key features include:

📈 Total Loan Applications: Displays the total number of loan applications received, including Month-to-Date (MTD) and Month-over-Month (MoM) growth percentages.

💵 Total Funded Amount: Shows the total amount of loans funded, with MTD and MoM growth indicators.

💰 Total Amount Received: Reflects the total repayments received from loans, alongside MTD and MoM metrics.

📊 Average Interest Rate: Indicates the average interest rate across all loans, with a focus on MTD and MoM changes.

📉 Average Debt-to-Income Ratio (DTI): Highlights the average DTI ratio, a crucial metric for assessing borrower risk.

# Good vs. Bad Loans:


✅ Good Loan Issued: Shows the percentage and number of loans classified as 'Good,' along with their funded and received amounts.

❌ Bad Loan Issued: Focuses on 'Bad' loans, providing their count, funded amount, and received amount.

Loan Status:

A table categorizing loans into different statuses (e.g., Charged Off, Current, Fully Paid), providing a breakdown of their applications, amounts received, MTD/MoM metrics, and average interest rates.
![image](https://github.com/user-attachments/assets/2b00525a-e1c6-489b-ad32-37e50dad29f2)


## 2️⃣ Overview Dashboard

The Overview Dashboard provides a deeper dive into loan applications, offering insights into trends and distributions:

📅 Total Loan Applications by Month: A line chart illustrating monthly trends in loan applications, helping identify seasonality and growth patterns.

🗺️ Total Loan Applications by Address State: A map visualizing the geographic distribution of loan applications across states.

📆 Total Loan Applications by Term: A pie chart breaking down loan applications based on their term lengths (e.g., 36 months, 60 months).

👥 Total Loan Applications by Employee Experience: A bar chart showing how loan applications are distributed based on the experience of the bank employees handling them.

🏦 Total Loan Applications by Purpose: A bar chart detailing the various purposes for which loans were applied, such as debt consolidation, credit card refinancing, home improvement, and more.

🏠 Total Loan Applications by Home Ownership: A chart breaking down applications based on whether the applicant owns or rents their home, offering insights into borrower profiles.
![image](https://github.com/user-attachments/assets/880f4279-1bfc-4860-92ac-217da75a582c)


## 3️⃣ Details Dashboard
The Details Dashboard is designed for granular analysis at the individual loan level, allowing users to drill down into specific loans:

🔢 Loan Data Table: A detailed table listing individual loan applications, including:

🆔 Loan ID: A unique identifier for each loan.

🎯 Purpose: The reason for the loan, such as debt consolidation or home improvement.

🏡 Home Ownership: Indicates whether the borrower owns or rents their home.

🏅 Grade: The credit grade assigned to the loan, reflecting the borrower’s creditworthiness.

📅 Issue Date: The date the loan was issued.

💸 Total Funded Amount: The total amount of money funded for the loan.

📈 Sum of Interest Rate: The total interest rate applied to the loan.

💳 Sum of Installment: The total amount the borrower needs to repay in installments.

💵 Total Received Amount: The total amount the bank has received from the borrower to date.
![image](https://github.com/user-attachments/assets/f4618d04-146b-4b41-8c45-75fdf08d3e13)


## 🔎 Filters:

States, Grade, Purpose, Good vs. Bad Loan: These filters allow users to narrow down the data to specific criteria, making it easier to analyze particular segments of the loan portfolio.

## 💾 Data Sources
**SQL Database:** The data for this project was fetched from a SQL database, ensuring robust and reliable data processing.

**DAX (Data Analysis Expressions):** DAX was utilized to create calculated columns and measures, enabling deeper insights and complex calculations.
📊 Key Metrics Explained
**MTD (Month-to-Date):** Measures performance from the start of the current month up to the present day.

**MoM (Month-over-Month):** Compares the performance of one month to the previous month, highlighting growth or decline.
## 🛠️ Tools and Technologies Used
SQL: For data extraction and preparation.
DAX: For creating custom calculations and aggregations within Power BI.
Power BI: For building interactive dashboards and visualizing the data.
## 📝 Conclusion
This project demonstrates the powerful synergy between SQL, DAX, and Power BI in transforming raw financial data into actionable insights. Each dashboard is designed to serve a specific purpose, from high-level summaries to detailed loan-level analysis, helping financial professionals make informed, data-driven decisions.
