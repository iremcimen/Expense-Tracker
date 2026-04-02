# Expense Tracker

A simple Flutter expense tracker app that helps users manage their income and expenses.

## Features

- Add new income and expense transactions
- View a list of recorded transactions
- Organize personal financial records easily
- Clean and simple user interface
- Built with Flutter and Dart

## Screens Used in the Project

- `main.dart` → app entry point
- `expenses.dart` → main expense tracker screen and app structure
- `new_expense.dart` → form for adding a new expense
- `expenses_list.dart` → displays the list of expenses
- `expense_item.dart` → reusable widget for a single expense item
- `expense.dart` → expense model and category definitions

## How It Works

The app starts with the main expense tracking screen.  
When the user adds a new expense, the entered data is processed and displayed in the expense list on the screen.

## Technologies

- Flutter
- Dart

## Getting Started

To run this project locally:

```bash
git clone https://github.com/iremcimen/Expense-Tracker.git
cd Expense-Tracker
flutter pub get
flutter run
