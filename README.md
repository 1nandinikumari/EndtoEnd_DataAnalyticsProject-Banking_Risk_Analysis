# 🏦 Banking Data Analytics

---

## 📘 Project Overview
This project focuses on building a complete **Banking Data Analytics Dashboard** to analyze and understand **risk analytics** in banking and financial services.  
The main goal of this project is to understand how **data can be used to minimize the risk of losing money while lending to customers** and to help banks identify potential high-risk segments through data insights.

---

## 🧱 Step 1: Database Creation (MySQL)
I started the project by designing and creating a **relational database** in **MySQL**.  
I created multiple tables such as:
- **Client-Banking**
- **Banking Relationship**
- **Investment Advisor**
- **Gender**

This database served as the foundation for all further analytics and visualizations.

---

## 🐍 Step 2: Connecting MySQL to Python (Jupyter Notebook)
Once the database was ready, I connected MySQL to **Python (Jupyter Notebook)** using the `mysql.connector` library.  
This allowed me to import the data directly from MySQL into Python for **data manipulation, data cleaning, and exploratory data analysis (EDA).**

---

## 🧹 Step 3: Data Cleaning & Preprocessing
In Python, I performed extensive **data cleaning** and **data preparation** before moving to visualization.  
The major cleaning tasks included:

- Removing **extra spaces** or unwanted characters from column names and string fields.  
- Checking and handling **null values** or **negative values** in numerical fields.  
- Replacing **impossible ages** (for example, negative or unrealistically high ages).  
- Creating a **Total Balance** column to calculate total available funds for each customer.  
- Ensuring all numerical columns had the correct data types.  
- Standardizing categorical values for consistency.

---

- **Risk Category by Estimated Income:**  
Segmented customers into different **income bands** and linked them to their **risk exposure** levels.

- **Occupation-based Risk Analysis:**  
Categorized customers by their **occupation** and analyzed the **count of occupations vs. risk weighting**.

- **High-Risk Flag:**  
Added a flag column to identify customers considered **high risk** based on their DTI and income levels.

---

## 🔍 Step 4: Exploratory Data Analysis (EDA)
I performed detailed **EDA (Exploratory Data Analysis)** to uncover patterns, distributions, and relationships in the data.  
The following analyses were performed:

### 1️⃣ Income Band Distribution
- Visualized the **distribution of customers based on income levels** using a pie chart.
- **Insight:**  
The **majority of customers belong to the medium-income group**, followed by the low-income group.  
Only a few customers fall into the high-income category.  
This indicates that the bank **primarily deals with average-income customers**, who might have **higher lending risks** compared to high earners.

### 2️⃣ Numerical and Categorical Distributions
- Checked the spread of numerical variables (e.g., deposits, loans, credit balances) using histograms and summary statistics.
- Analyzed categorical variables (e.g., occupation, gender, risk level) using bar charts and frequency counts.

### 3️⃣ Estimated Income by Risk Category
- Compared the **average estimated income** across different **risk categories**.
- Found that **high-risk customers generally have lower income levels**, confirming that income and risk are inversely related.

### 4️⃣ Occupation vs. Risk Weighting
- Grouped data by **occupation** and analyzed how risk varies across professions.
- Created a **count of occupation vs. risk weighting** visualization to observe which professions fall under high or low risk.

### 5️⃣ Risk Weighting Distribution by Loyalty Classification
- Examined how **risk weighting** varies with different **loyalty categories** (e.g., Gold, Platinum, Silver, Jade).
- This helped identify whether loyal customers tend to have lower risk or not.

### 6️⃣ Income Band Distribution by Pie Chart
- Created a pie chart to visually represent how the customer base is distributed across different income bands (Low, Medium, High).

---

## 📈 Step 5: Dashboard Creation (Power BI)
After completing the data preparation and EDA, I exported the cleaned data from Python and imported it into **Power BI**.  
Using Power BI, I built an interactive **Banking Dashboard** divided into multiple analytical sections:

- **Banking Risk Analysis-Dashboard**
- **Loan Analysis**
- **Deposit Analysis**

### The dashboard includes:
- **KPIs:** Total Loan, Total Deposit, Business Lending, Checking Accounts, Savings Accounts, Total Cities.
- **Slicers:** Year and Gender (Gender shown as button-style slicers arranged horizontally).
- **Visuals:**
- Loan and Deposit trend comparison.
- Deposits by Gender.
- Deposits by Account Type.
- Loan by Banking Relationship.
- City-wise deposit analysis.
- Risk weighting vs Loyalty classification.

---

## 💡 Key Insights Generated
- The **majority of customers** belong to the **medium income group**, followed by the low-income group.  
- The **bank’s major client** consists of **average-income customers**, who may carry **higher lending risks** compared to high earners.  
- **High-risk customers** often have **lower estimated income** and **higher debt-to-income ratios**.  
- Certain **occupations** show consistent high-risk patterns, useful for risk profiling.  
- **Loyalty analysis** reveals that high-loyalty customers (e.g., Platinum, Gold) tend to have **lower risk weighting**.  
- The **dashboard helps visualize deposits, loans, and risks together**, enabling the bank to make more data-driven lending decisions.

---

## 🛠️ Tools & Technologies Used
- **Database:** MySQL  
- **Data Analysis:** Python (Jupyter Notebook)  
- **Libraries:** pandas, numpy, matplotlib,seaborn, mysql.connector  
- **Visualization:** Power BI  
- **Other Skills Applied:** Data Cleaning, Data Transformation, EDA, Risk Analysis, Dashboard Design  

---

## 🚀 Summary
This project demonstrates how **data from multiple sources** can be integrated, cleaned, and analyzed to extract actionable insights in the **banking sector**.  
By combining **MySQL**, **Python**, and **Power BI**, I was able to create a complete workflow — from data storage to visualization — and generate meaningful insights into **risk exposure, customer behavior, and income distribution**.

The final dashboard provides a **comprehensive view of banking performance, customer segmentation, and lending risk**, helping decision-makers take smarter actions.

---


