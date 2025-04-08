💳 ATM Interface (Console-Based Java Project)
This project is Task 2 of my Java Development Internship at Oasis Infobyte.
It is a console-based ATM simulation system developed using core Java concepts. The goal of this project is to build a simple, interactive, and user-friendly interface that allows users to perform essential banking operations directly through the terminal.

📌 Project Overview
In the real world, ATMs are everywhere, and this project replicates the basic functions of an ATM through Java programming. The system is designed with an emphasis on object-oriented programming, and is divided into five different Java classes to separate concerns and keep the code modular.

When the system starts, users are prompted to enter their User ID and PIN. After successful login, the ATM menu is displayed, offering the user several banking functionalities.

🔧 Functionalities
Once the user logs in, the following operations can be performed:

Transaction History
Displays a list of all the past transactions (withdrawals, deposits, transfers) done by the user during the session.

Withdraw
Allows the user to withdraw a specified amount from their account, provided sufficient balance is available.

Deposit
Enables the user to deposit money into their account, updating their current balance accordingly.

Transfer
Lets the user transfer money to another user's account, simulating a basic peer-to-peer transaction.

Quit
Ends the session and exits the ATM interface.

🧠 Key Highlights
Designed with a focus on user experience through clear prompts and logical flow.
Clean separation of concerns using multiple Java classes for better maintainability.
Demonstrates the use of encapsulation, inheritance, and data handling in Java.
Reinforces core programming concepts like conditionals, loops, methods, arrays/lists, and string operations.
Handles edge cases such as insufficient balance, invalid inputs, and incorrect login details.
🧩 Project Structure
The program is divided into five Java classes, each with its own responsibility:

Main Class – Entry point of the program; handles login and navigation.
Account Class – Manages user data, including balance and transaction history.
Transaction Class – Stores and processes transaction data (deposit, withdraw, transfer).
ATMOperations Class – Contains the logic for performing operations like withdraw, deposit, etc.
User Class – Handles user authentication and account linkage.
🎓 What I Learned
Working on this project has helped me:

Gain confidence in writing modular, readable code in Java.
Practice real-world logic building using core Java constructs.
Understand the importance of user input validation and error handling.
Improve my ability to break down a large problem into smaller, manageable components.
📸Output
