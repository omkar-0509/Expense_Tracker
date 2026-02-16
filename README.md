# 🧾 Python Expense Tracker

A **console-based Python application** to track daily expenses, generate reports, and analyze spending patterns. It uses **SQLite** as the database and **Pandas** for data handling and reporting.

---

## Features
- Add daily expenses with category, amount, and description  
- View all expenses in a table format  
- Category-wise expense analysis  
- Monthly expense report  
- Simple console-based menu for easy interaction  

---

## Technologies Used
- Python 3  
- SQLite3 (lightweight database)  
- Pandas (for reporting and analysis)  
- Datetime module (for handling dates)  

---

## Project Structure
- `expenses.db` – SQLite database file  
- `expense_tracker.py` – Main Python script containing all functions  

---

## How It Works (Workflow)

1. **Connect to Database**  
   The program connects to `expenses.db`. If the table `expenses` does not exist, it is created automatically.

2. **Add Expense**  
   Users enter the category, amount, and description. The current date is recorded automatically.

3. **View Expenses**  
   Displays all expenses in a tabular format using Pandas.

4. **Category-wise Analysis**  
   Calculates total expenses per category and displays a summary.

5. **Monthly Expense Report**  
   Summarizes total expenses for each month.

6. **Menu Interaction**  
   Users can choose options from the menu: Add Expense, View Expenses, Category Analysis, Monthly Report, or Exit.

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/expense-tracker.git
