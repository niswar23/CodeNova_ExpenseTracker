# CodeNova Internship - Expense Tracker #

## Project Overview

The Expense Tracker is a simple Python application developed to help users record and manage their daily expenses. It allows users to add expenses, view saved records, calculate total expenses and search expenses by category.

## Features

- Add expenses with a date, category, description and amount.
- View all recorded expenses.
- Calculate the total expenses.
- Filter expenses by category.
- Save expense records in a CSV file.
- Validate expense amounts and date formats.
- Keep saved records available when the program is restarted.

## Technologies Used

- Python
- CSV module
- OS module
- Datetime module
- Visual Studio Code

## Requirements

- Python 3 installed on the computer.
- Visual Studio Code or another Python-compatible editor.

## How to Run

1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Open a terminal in the project folder.
4. Run the following command:

   `python ExpenseTracker.py`

5. Select an option from the menu and follow the instructions.

## Data Storage

Expense records are stored in `expenses.csv`. This file is created automatically when the first expense is added.

## Testing

The application can be tested by adding expenses, viewing records, calculating totals, filtering by category, entering invalid values and restarting the program to check data persistence.

## Limitations

- The application runs in a command-line interface.
- Expense records are stored locally in a CSV file.
- The application does not include user accounts or cloud synchronization.

## Internship Task

This project was developed as part of the CodeNova Python Programming Internship.