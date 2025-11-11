# 💰 Personal Finance Tracker (Python)

A smart **Personal Finance Tracker** built in Python to help users analyze, visualize, and optimize their spending habits.  
It automatically categorizes expenses, tracks monthly budgets, and provides personalized insights — enabling **data-driven financial decisions** similar to how companies like **IDFC First Bank** and **Sciative Solutions** use data analytics for customer and revenue optimization.

---

## 🚀 Features

✅ **Automatic Transaction Categorization**  
Classifies spending into categories (Food, Rent, Utilities, Entertainment, etc.) using keyword-based logic.  

✅ **Spending Analytics Dashboard**  
Displays total income, expenses, and savings using interactive visualizations (Matplotlib / Plotly).  

✅ **Monthly Budget Alerts**  
Compares your actual spending vs. planned budget, and highlights overspending categories.  

✅ **Savings Insights**  
Provides intelligent tips — e.g., *“Your entertainment expenses increased 22% this month.”*  

✅ **Data Import Support**  
Accepts `.csv` or `.xlsx` bank statement files and parses them automatically.  

✅ **Report Export**  
Generates summarized `.csv` or `.pdf` reports for personal records or sharing.

---

## 🧠 Tech Stack

| Layer | Technology Used |
|-------|------------------|
| Programming | Python 3.x |
| Libraries | Pandas, Matplotlib, NumPy, datetime |
| Visualization | Plotly / Matplotlib |
| Optional Frontend | Streamlit (for web-based dashboard) |
| Version Control | Git & GitHub |

---

## 🗂️ Project Structure

```plaintext
Personal-Finance-Tracker/
│
├── data/                     # Sample bank statement data
├── scripts/                  # Core logic files
│   ├── categorize.py         # Categorization logic
│   ├── analyze.py            # Spending analysis
│   ├── visualize.py          # Charts and graphs
│
├── app.py                    # Main Streamlit or CLI application
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
└── .gitignore

