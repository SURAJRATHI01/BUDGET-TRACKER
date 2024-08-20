# BUDGET-TRACKER

The above code is a sample implementation of a budget tracker in Java. The BudgetTracker class keeps track of a user’s expenses and incomes, and calculates the current budget balance.

The class has a constructor BudgetTracker(), which initializes two ArrayList objects, one for expenses and one for incomes, as well as a double variable balance which is set to zero.

The class has three methods:

addExpense(double expense): This method takes in a double value as an argument, representing an expense, and adds it to the expenses ArrayList. It also subtracts the expense from the balance.
addIncome(double income): This method takes in a double value as an argument, representing an income, and adds it to the incomes ArrayList. It also adds the income to the balance.
getBalance() : This method returns the current balance
printExpenses() : This method prints out all the expenses stored in the expenses ArrayList
printIncomes() : This method prints out all the incomes stored in the incomes ArrayList
It’s worth noting that this is just a basic example, and you might want to add more features such as handling categories, displaying the balance in a specific currency
