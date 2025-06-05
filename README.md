# Expenses_in_SouthZone_Detailed
A simple Python project to track and categorize personal trip expenses in the South Zone. It generates a detailed CSV report with total and remaining budget calculations.

# South Zone Expense Report 📊
This project contains a detailed breakdown of expenses for a trip in the South Zone.

## Files Included
- `generate_expenses.py` – Python script to generate the expense report and CSV.
- `Expenses_in_SouthZone_Detailed.csv` – The final CSV file with categorized expense data.

## What's Inside
- 💰 Expense types: Transport, Food, Personal, Other
- 💳 Payment methods: Price (Cash), Online, Mixed
- 📉 Budget: ₹4000
- 📈 Summary: Total spent and remaining balance

## How to Run
1. Clone this repository or download the files.
2. Make sure you have `pandas` installed:
   ```bash
   pip install pandas

3.(Optional) – .gitignore
Since I'm working on this using Git in VS Code, I added a .gitignore file to avoid pushing unnecessary files. Here's what I included:
__pycache__/
*.pyc
This keeps the repo clean by skipping compiled Python files and cache folders.

4. (Optional) – requirements.txt
Since I'm using the pandas library in my script, I created a requirements.txt file with:
pandas
This makes it easy for those who want to install the needed packages by running:
pip install -r requirements.txt

Output
The script will create a file called Expenses_in_SouthZone_Detailed.csv with:
Itemized expenses
Categories
Payment methods
Total spent and remaining balance

How to use the project. 
## How to Run
Make sure you have Python and pandas installed. Then run:
```bash
python generate_expenses.py
