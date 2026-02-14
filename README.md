📊 Customer Sales & Churn Analysis
📌 Project Overview

This project analyzes customer purchasing behavior and churn patterns using Python and Pandas. The objective is to identify valuable customers, understand sales trends, analyze churn behavior, and generate business insights through data visualization and aggregation techniques.

The project includes:

Data cleaning and preprocessing

Customer value analysis

Sales pattern analysis

Churn rate evaluation

Customer segmentation using KMeans

Professional dashboard visualizations

Business recommendations

🎯 Project Objectives

Analyze customer lifetime value

Identify high-risk churn customers

Understand contract and payment behavior

Perform sales aggregation and summarization

Create professional visual dashboards

Provide business insights and recommendations

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

📂 Project Structure
Customer-Sales-Analysis/
│
├── customer_analysis.ipynb
├── customer_data.csv
├── requirements.txt
└── README.md

⚙️ Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/your-username/Customer-Sales-Analysis.git

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run Jupyter Notebook
jupyter notebook


Open customer_analysis.ipynb

📊 Key Analysis Performed
🔹 Data Cleaning

Converted TotalCharges to numeric

Handled missing values using median imputation

Created calculated column: CustomerValue

🔹 Aggregations (Using Pandas GroupBy)

Total Revenue Calculation

Average Monthly Charges by Contract

Churn Rate by Contract

Revenue by Payment Method

Revenue by Region

🔹 Data Merging

Merged customer dataset with simulated regional dataset for regional sales analysis.

🔹 Pivot Tables

Created pivot tables to analyze churn rate by:

Contract Type

Payment Method

🔹 Customer Segmentation (Machine Learning)

Applied KMeans clustering to segment customers into:

High Value

Medium Value

Low Value

📈 Dashboard Visualizations

The dashboard includes:

Tenure vs Monthly Charges (Scatter Plot)

Churn Rate by Contract (Bar Chart)

Payment Method Distribution (Pie Chart)

Revenue by Region (Bar Chart)

Churn Heatmap (Pivot Table Visualization)

Customer Segmentation Scatter Plot

📌 Key Business Insights

Month-to-month contracts show highest churn rate.

Customers using electronic payment methods churn more frequently.

Higher tenure customers generate greater lifetime value.

Retention strategies should focus on short-term contract customers.

Offering long-term contract discounts may reduce churn.

📊 Sample Metrics

Total Revenue: Calculated from TotalCharges

Total Customers: Unique Customer IDs

Average Monthly Charge

Retention Rate

Top 10 High-Value Customers

🧠 Advanced Analysis

KMeans clustering used for customer segmentation.

Retention rate calculated using churn distribution.

Heatmap used for contract vs payment churn visualization.

🧪 Testing & Validation

Verified missing value handling

Validated aggregation outputs

Cross-checked pivot table summaries

Confirmed segmentation cluster assignments

📄 Documentation Included

Full analysis notebook

PDF business report

Visual dashboard outputs

Requirements file for reproducibility

🚀 Future Improvements

Build churn prediction model (Logistic Regression / Random Forest)

Deploy as interactive dashboard (Streamlit)

Add real regional dataset

Integrate RFM analysis

👩‍💻 Author

Aishwarya Selvakumar
B.E. Artificial Intelligence & Machine Learning
2nd Year Engineering Student

⭐ Why This Project Matters

This project demonstrates:

✔ Data Cleaning
✔ Exploratory Data Analysis
✔ Aggregation & Pivot Tables
✔ Data Merging
✔ Business Insight Generation
✔ Machine Learning Application
✔ Professional Visualization
