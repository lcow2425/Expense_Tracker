
# Expense Tracker Application

## Overview
The **Expense Tracker Application** is a user-friendly tool designed to help manage personal and professional finances by tracking daily expenses. Developed using Python and Tkinter for the graphical user interface, this application allows users to input, store, and view their expenses in a structured format. The data is securely stored in an SQLite database, ensuring easy access and retrieval.

## Features
- **Add New Expenses:** Input details such as the date, name, title, and amount for each expense.
- **View Expenses:** Display all recorded expenses in a table format within the application.
- **Persistent Storage:** Expenses are stored in an SQLite database (`expenseTracker.db`) for easy access and retrieval.

## Prerequisites
Before you can run the application, ensure that you have the following installed:
- **Python 3.x**
- **Tkinter** (usually included with Python installations)
- Additional Python libraries:
  - `tkcalendar`
  - `sqlite3` (comes pre-installed with Python)

You can install any required libraries using `pip`:
```bash
pip3 install tkcalendar
```

## Installation and Running the Application
1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Run the Application:**
   Navigate to the project directory and run the following command to start the application:
   ```bash
   python3 expense_tracker.py
   ```

3. **Using the Application:**
   - **Date:** Use the calendar widget to select the date of your expense.
   - **Name:** Enter your name in the provided text field.
   - **Title:** Provide a brief description of the expense in the title field.
   - **Expense:** Enter the amount spent in the expense field.
   - **Submit:** Click the "Submit" button to save the entry in the database and display it in the table.
   - **View Expenses:** Click the "View Expenses" button to display all recorded expenses.

## Project Structure
- **expense_tracker.py:** The main script that runs the application.
- **expenseTracker.db:** The SQLite database file where all expense data is stored.

## Contributors
This project was a collaborative effort by the following contributors:
- **Jagdeep Singh**
- **Dhaval Gajjar**
- **Mohammad Mahendi Sabbirali Sunasara**
- **Rahul Tripathi**

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
We would like to express our gratitude to our mentors and colleagues who provided guidance and support throughout the development of this project.
