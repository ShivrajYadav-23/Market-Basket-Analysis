Market Basket Analysis Using Apriori Algorithm

📌 Project Overview
This project implements Market Basket Analysis (MBA) using the Apriori algorithm to identify frequently purchased product combinations from retail transaction data. The goal is to uncover hidden buying patterns and convert them into actionable business insights.

🎯 Objectives
Analyze customer purchase behavior
Identify products frequently bought together
Generate association rules using support, confidence, and lift
Provide insights useful for retail decision-making

📂 Dataset
Source: Grocery Store Dataset (Kaggle)
Transactions: ~9,800
Products: 169 unique items
Each row represents a single customer’s basket

⚙️ Methodology
Data cleaning and preprocessing
Transaction formatting
One-hot encoding (binary representation)
Applying Apriori algorithm
Generating and filtering association rules

📈 Key Concepts Used
Support: Frequency of itemsets
Confidence: Likelihood of co-purchase
Lift: Strength of association (>1 indicates strong rule)

🔍 Results
Identified frequently purchased items like Whole Milk
Discovered strong rules such as Butter → Whole Milk
Lift values between 1.5–2, indicating meaningful relationships
🧠 Business Use Cases
Product placement optimization
Combo offers and cross-selling
Inventory and demand planning

🛠️ Tech Stack
Python
Pandas
mlxtend (Apriori & association rules)

👤 Author
Shivraj Yadav
Data Analyst Intern Hackveda
