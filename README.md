# SpendWise Budget Tracker

## Project Description

SpendWise is a personal budget and expense tracker designed to help users keep track of their budget and spending. The Week 6 version introduces JavaScript to make the application perform basic budget calculations and process user input.

## JavaScript Concepts Implemented

The project uses several basic JavaScript concepts, including:

* Variables
* User input with `prompt()`
* Number conversion using `Number()`
* Functions
* Arithmetic calculations
* Conditional statements using `if...else`
* Console output using `console.log()`

## How Variables Are Used

Variables are used to store important budgeting information. The project uses variables such as `budget`, `expense`, and `remainingBalance`.

For example:

javascript
let budget = 0;
let expense = 0;
let remainingBalance = 0;


These variables allow the application to store and process the user's budgeting information.

## How User Input Is Collected

The application uses JavaScript's `prompt()` function to ask the user for their total budget and total expenses.

javascript
budget = Number(prompt("Enter your total budget:"));
expense = Number(prompt("Enter your total expenses:"));


The `Number()` function converts the input into a number so that mathematical calculations can be performed.

## How Calculations Are Performed

SpendWise calculates the remaining balance by subtracting the total expenses from the total budget.
javascript
remainingBalance = budget - expense;


For example, if the budget is KSh 50,000 and expenses are KSh 18,000, the remaining balance is KSh 32,000.

## How Functions Organize the Code

A reusable function is used to calculate the remaining balance:

javascript
function calculateBalance(budget, expense) {
    return budget - expense;
}


The function receives the budget and expense values and returns the calculated remaining balance. Using a function makes the calculation reusable and keeps the application logic organized.

## Displaying Results

The calculated results are displayed in the browser console using `console.log()`.

The console displays:

* Total budget
* Total expenses
* Remaining balance
* Budget status

## Project Files

The project contains:

* `index.html` - Contains the structure of the SpendWise webpage.
* `style.css` - Contains the styling and layout of the webpage.
* `script.js` - Contains the JavaScript logic and budget calculations.
* `README.md` - Explains the project and JavaScript concepts used.

## Conclusion

The Week 6 version of SpendWise provides a JavaScript foundation for processing budgeting information. Users can enter their budget and expenses, and the application calculates and displays their remaining balance in the browser console.
