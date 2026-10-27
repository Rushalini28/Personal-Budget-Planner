# 💰 Personal Budget Planner Using Python

## 📌 About the Project

The Personal Budget Planner is a beginner-friendly Python application that helps users track their income and expenses, calculate their remaining balance, and understand their spending habits.

The application allows users to record financial transactions, view a budget summary, check all saved transactions, and analyze expenses by category. All transaction records are stored in a CSV file for future use.

## ✨ Features

- Add income and expense transactions.
- Calculate total income.
- Calculate total expenses.
- Display the remaining balance.
- View all recorded transactions.
- View category-wise expenses.
- Sort expense categories by spending amount.
- Validate user input.
- Save transaction records automatically in a CSV file.
- Preserve transaction history between program sessions.

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Modules:** `csv`, `pathlib`, `datetime`
- **Storage:** CSV file
- **Code Editor:** Visual Studio Code

## 📂 Project Structure

```text
Personal Budget Planner/
│
├── main.py
├── budget_data.csv
└── README.md
```

**Note:** `budget_data.csv` is created automatically when the first transaction is added.

## ⚙️ Requirements

- Python 3.x
- Visual Studio Code or another Python editor

No additional libraries are required.

## 🚀 How to Run the Project

### Step 1: Install Python

Download Python from https://www.python.org/downloads/ if it is not already installed.

### Step 2: Download the Project

Download the repository or clone it to your computer.

### Step 3: Open the Project

Open the `Personal Budget Planner` folder in VS Code.

### Step 4: Open the Terminal

Select **Terminal → New Terminal** in VS Code.

### Step 5: Run the Application

Execute the following command:

```bash
python main.py
```

### Step 6: Use the Application

Select an option from the menu:

1. Add Income or Expense
2. View Budget Summary
3. View All Transactions
4. View Category-wise Expenses
5. Exit

Follow the prompts to enter transaction details and view your financial summary.

## 💻 Sample Usage

### Adding Income

```text
Enter your choice: 1

1. Income
2. Expense
Choose transaction type: 1
Enter category (e.g. Salary, Food): Salary
Enter amount (₹): 20000
Enter description: Monthly income

Income recorded successfully!
```

### Adding an Expense

```text
Enter your choice: 1

1. Income
2. Expense
Choose transaction type: 2
Enter category (e.g. Salary, Food): Food
Enter amount (₹): 500
Enter description: Groceries

Expense recorded successfully!
```

### Budget Summary

```text
========== BUDGET SUMMARY ==========
Total Income:   ₹20000.00
Total Expenses: ₹500.00
Remaining Balance: ₹19500.00
====================================
```

*The sample output uses example transactions.*

## 🧮 How It Works

### 1. Transaction Management
Users enter the transaction type, category, amount, and description.

### 2. Data Storage
The `csv` module saves transaction records to `budget_data.csv`.

### 3. Budget Calculation
The application calculates:

**Remaining Balance = Total Income − Total Expenses**

### 4. Expense Categorization
Expenses are grouped by category, such as Food, Travel, Shopping, and Bills.

### 5. Data Persistence
Saved transactions can be loaded again when the application is restarted.

## 📚 Python Concepts Learned

- Variables and data types
- Functions
- Loops and conditional statements
- Lists and dictionaries
- File handling
- CSV data storage
- Exception handling
- Sorting and aggregation
- Date and time handling
- Basic financial calculations

## 🔮 Future Improvements

- Add a graphical user interface using Tkinter.
- Set monthly budgets for different categories.
- Display spending charts using Matplotlib.
- Add monthly and yearly reports.
- Allow editing and deleting transactions.
- Export budget summaries to PDF or Excel.
- Add password-protected access.

## 🔐 Privacy Notice

Do not publish real financial records in a public repository. Use sample transactions when sharing the project on GitHub.

## 👨‍💻 Author

Created as a beginner-friendly Python project to practise file handling, data management, and financial calculations.
