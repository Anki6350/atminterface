ATM Interface in Java

Introduction
This is a simple Java-based ATM interface that allows users to register, log in, and perform various banking operations such as withdrawing, depositing, transferring money, checking balance, and viewing transaction history.

Features
User Registration: Users can register by providing their name, username, password, and account number.
Login System: Secure login system requiring username and password.
Deposit Money: Users can deposit up to 10,000 at a time.
Withdraw Money: Users can withdraw funds if the balance is sufficient.
Transfer Money: Users can transfer up to 50,000 at a time to other accounts.
Check Balance: Displays the current balance in the account.
Transaction History: Displays the history of all transactions made by the user.
User-friendly Menu: Console-based menu system for easy navigation.


Technologies Used
Java: Core language for the implementation.
Scanner Class: Used for user input handling.


How to Run the Program
Clone the repository:
git clone https://github.com/yourusername/ATM-Interface.git
Navigate to the project directory:
cd ATM-Interface
Compile the Java program:
javac atminterface.java
Run the program:
java atminterface
Usage
Select Register to create an account.
Log in using your username and password.
Choose from the available banking options:

Withdraw Money
Deposit Money
Transfer Money
Check Balance
Transaction History
Exit


Limitations & Future Enhancements

Currently, the system does not use a database to store user details permanently.
User data is lost once the program is terminated.
Future improvements can include:
Database integration for persistent storage.
GUI-based ATM interface for better user experience.
Improved security features such as encryption.
