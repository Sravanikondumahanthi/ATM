ATM Simulation
This project simulates a simple ATM (Automated Teller Machine) system where users can log in with their username and password, and then perform various banking operations such as withdrawing money, depositing money, checking their balance, and changing their password.

Table of Contents
•	Features
•	Installation
•	Usage
•	Code Overview
•	Contributing

Features
•	Login System: Users can log in using their username and password.
•	Withdraw Money: Users can withdraw money from their account.
•	Deposit Money: Users can deposit money into their account.
•	Check Balance: Users can check their account balance.
•	Change Password: Users can change their account password.
•	Security: Accounts get blocked after three consecutive failed login attempts.

Installation
To run this project, you need to have Python installed on your system. You can download Python from the official Python website.
1.	Clone the repository or download the code files.
2.	Open a terminal and navigate to the directory where the code files are located.

Usage
To start the ATM simulation, run the following command in the terminal:

python atm.py

You will be prompted to enter your username and password. After successful login, you can choose from the available options to perform banking operations.


Code Overview
The code is implemented in Python and consists of a single class ATM with various methods to handle different functionalities.

Class and Methods
•	__init__: Initializes the class with predefined usernames, passwords, PINs, balance, and calls the Login method.
•	Login: Prompts the user to enter their username and checks the validity.
•	UsernameCheck: Validates the user's password and handles login attempts.
•	Option: Displays the main menu and prompts the user to choose an option.
•	withdraw: Handles money withdrawal after validating the PIN.
•	Deposit: Handles money deposit after validating the PIN.
•	Balance: Displays the user's account balance after validating the PIN.
•	Change_password: Allows the user to change their password after validating the PIN and current password.
•	default: Handles invalid menu options.
•	Exit: Exits the application.

Sample Usage
1.	Run the program.
2.	Enter your username (e.g., sravani).
3.	Enter your password (e.g., abc123).
4.	Choose an option from the menu to perform banking operations.

Contributing
Contributions are welcome! If you have any suggestions or improvements, please open an issue or create a pull request.


