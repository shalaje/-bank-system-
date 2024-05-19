# Bank Management System

## Overview

The Bank Management System is a simple Java-based application that simulates basic banking operations such as creating accounts, depositing money, withdrawing money, and transferring funds between accounts. This project demonstrates using Object-Oriented Programming (OOP) principles such as inheritance, encapsulation, and polymorphism.

## Features

- Create a new bank account
- Deposit money into an account
- Withdraw money from an account
- Transfer money between accounts
- Display all accounts
- Display all transactions for a specific account

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- A Java IDE (e.g., IntelliJ IDEA, Eclipse) or a text editor (e.g., VS Code)

### Installation

1. **Clone the Repository**
   ```sh
   git clone https://github.com/shalaje/bank-system.git
   cd bank-system

2. **Compile the code**
 If you're using a command line:
 javac -d bin src/com/bank/*.java
 If you're using an IDE, you can just open the project and build it using the IDE's build tools.

**Running the Application**
Once the application starts, you can interact with it through the console by following the prompts. Here are the basic operations you can perform:

1. Create an Account

Follow the prompt to enter the account ID, user name, and initial balance.

2. Deposit Money

Follow the prompt to enter the account ID and deposit amount.

3. Withdraw Money

Follow the prompt to enter the account ID and withdrawal amount.

4. Transfer Money

Follow the prompt to enter the originating account ID, resulting account ID, transfer amount, and whether to use a flat fee.

5. Show All Accounts

The application will display all existing accounts with their IDs, user names, and balances.

6. Show Transactions

Follow the prompt to enter the account ID, and the application will display all transactions related to that account.


**Example Usage**
Here is a sample interaction with the application:

Welcome to the Bank Management System!
Available commands: createAccount, deposit, withdraw, transfer, showAccounts, showTransactions, exit.
   
Enter command: 

createAccount
Enter account ID: 11111
Enter user name: jetmir.sh
Enter initial balance: 500
Account created successfully.
Enter command: exit (Displays again, you can choose from the available commands)


**Code Structure**
Test.java: The entry point of the application. Contains the main method and user interaction logic.
Bank.java: Singleton class that manages accounts and transactions.
Account.java: Represents a bank account.
Transaction.java: Abstract class representing a transaction.
Deposit.java: Class representing a deposit transaction.
Withdrawal.java: Class representing a withdrawal transaction.
Transfer.java: Class representing a transfer transaction.

**Contributing**
Contributions are welcome! Please fork the repository and submit a pull request with your changes.


   

