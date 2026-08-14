# Expense-Tracker-API

Roadmap.sh project for learning purposes
https://roadmap.sh/projects/expense-tracker-api

## Data model and relational model.
[DB diagram](https://dbdiagram.io/d/Expense-Tracker-6a7d1b9cc6a866c9075886dc)

User: Tracks its expenses.
  * username
  * password
  * creation time

Expense: Cost or charge that the user keeps track of.
  * creation_time
  * expense type
  * current status
  * cost
  
Enums:

Expense_cathegories:
 * Groceries
 * Leisure
 * Electronics
 * Utilities
 * Clothing
 * Health
 * Others
  
Expense_status: 
* Completed
* In_Progress

 User might contain one or more tasks
 
 Every task must be related to at least one user


