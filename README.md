# Spreadsheet Application using Javascript and CSS

## Problem Statement
Create a Spreadsheet application in Javascript.

## Requirements
- User should be able to ADD row/column(s) using + button.
- User should be able to DELETE row/column(s) using - button.
- User should be able to perform basic algebraic operations (+,-,*,/) with cell references.
- User should be able to select multiple rows or columns and display their sum in a row. 
  Any changes to the cell content should update the sum.
- User should be able to able to export the spreadsheet in CSV format.
- Should use ES6 syntax for the project including exports and imports.
- Should use webpackjs for building the project.
 
## Implementation
- The project uses ES6 syntax for implementing the Spreadsheet Application.
- Features such as Class, variable declartions using let/const, import/export of constants, functions and .js or .css files are used.
- WebpackJS is used building the project and running the application.
- Basic table with predefined rows/columns are displayed on the browser with the flexibitity to add/delete rows/columns on the table.
- Each table cell is dynamically assigned a unique ID to be able to identify the cell contents while performing arithmetic operations.
- The expression is evaluated using REGEX Pattern Matching and obtaining the last updated celll values to display the latest results in the cell.
- Algebraic operations are performed by first converting the infix expression to postfix expression and then evaluating the postfix expression.
- The contents of the spreadsheet can be downloaded or exported in a CSV format.
    
## Instructions to run the project:
- Download the project zip from the github and Run 'npm init' to initalize npm project.
- Once the initialization is complete, run the 'npm run start' command on the console.
- The WebpackJS will build the project and create /dist folder in the project structure which consists the bundled script of all the JS files.
- Open the index.html page on the browser to view the Spreadsheet Application and perform the necessary operations.
