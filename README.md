# Personal Finance Tracker

A simple CLI application to track your daily expenses. Data is saved locally in `expenses.json`.

## Usage

### Add an Expense
```bash
python tracker.py add <amount> <category> <description>
```
Example:
```bash
python tracker.py add 15.50 Food "Lunch at cafe"
```

### List Expenses
```bash
python tracker.py list
```
This will display a table of all recorded expenses.
