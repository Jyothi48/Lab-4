# Bank Account Management System
This project demonstrates a simple bank account management system in Java using HashMap.
Each bank account is identified by a unique account number.
The system allows creating accounts, depositing money, withdrawing money, and checking balances.
Account details (account number and balance) are stored using a HashMap<Integer, Double> for fast access.

# Bank Class
Stores account details in a HashMap<Integer, Double> where:
Key → Account Number (int)
Value → Account Balance (double)
createAccount(int accNo, double balance)
Adds a new account with an initial balance.
deposit(int accNo, double amt)
Adds money to the specified account.
withdraw(int accNo, double amt)
Subtracts money if sufficient balance is available.
Displays an error message if the balance is insufficient.
checkBalance
Displays the current balance of the account.

# Main Class
Creates 2 accounts.
Performs deposits and withdrawals.
Displays the updated balances.
