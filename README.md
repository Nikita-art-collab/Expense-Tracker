# Expense Tracker - README

## Project Overview

This is a simple **Expense Tracker** web application that allows users to track their expenses by adding and deleting individual expenses. The total expenses are dynamically updated as new items are added or removed. The application is built using HTML, CSS, and JavaScript and features an interactive user interface for easy use.

## Features

- **Add Expense**: Users can add a description and amount for each expense through a prompt.
- **Delete Expense**: Expenses can be removed from the list by clicking the delete button.
- **Real-Time Total Calculation**: The total expenses are automatically updated as expenses are added or removed.

## Project Structure

- **HTML (index.html)**: Contains the structure of the web page including the container for the expense tracker, the list of expenses, and the total expenses section.
- **CSS (style.css)**: Defines the styling for the expense tracker, ensuring a clean and modern layout with responsive design elements.
- **JavaScript (script.js)**: Provides the functionality for adding, deleting, and updating expenses in real time.

## Files

### 1. index.html
This is the main HTML file that includes the basic structure of the expense tracker UI.

Key Elements:
- Expense tracker container
- Button to add expenses
- Section to display the total expenses
- Script linked to JavaScript for functionality
- Linked to CSS for styling【6†source】

### 2. style.css
This file contains all the styles for the expense tracker. It provides layout and design for different elements such as the expense tracker container, expense items, buttons, and more.

Key Styles:
- Modern, clean design with beige background and green button for adding expenses
- Styled expense list with individual items and delete button【8†source】

### 3. script.js
This file contains the JavaScript logic for handling the expenses, including adding new expenses, deleting them, and updating the total.

Key Functions:
- `addExpense()`: Adds a new expense based on user input for description and amount.
- `deleteExpense()`: Removes the selected expense and updates the total.
- `renderExpenses()`: Dynamically renders the list of expenses and updates the total expenses on the screen【7†source】.

## How to Use

1. **Open `index.html` in a browser**: This will launch the expense tracker interface.
2. **Click "Add Expense"**: A prompt will ask for a description and an amount for the expense. After submitting, the expense will appear in the list, and the total expenses will be updated.
3. **Delete an expense**: Click on the red delete button next to any expense to remove it. The total expenses will be updated accordingly.

## Future Improvements

- Adding persistent storage to save expenses even after refreshing the page.
- Enhanced input validation and better user prompts.
- A more detailed breakdown of expenses by categories.
![Screenshot (1)](https://github.com/user-attachments/assets/7a15cfdd-8881-48f0-b4ef-0d9c9dea8718)


