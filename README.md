# ATM Banking System (C++)

A simple console-based ATM Banking System built in C++.
The program allows users to log in using an account number and PIN, then perform basic banking operations such as withdraw, deposit, and balance inquiry.
All client data is stored in a local text file (Clients.txt).

## 🚀 Features

✅ 🔐 User Authentication

✅ Login with Account Number + PIN Code

✅ Validates client information from the data file

✅ Quick Withdraw money (with balance validation)

✅ Normal Withdraw money (with balance validation)

✅ Deposit money

✅ View total bank balances

✅ Persistent storage using a text file (Clients.txt)

---
<br>

## 🧠 What I Learned

✅ Building structured data models using C++ structs.

✅ Handling files (loading, saving, updating records) using fstream.

✅ Implementing login authentication with Account Number & PIN.

✅ Creating core ATM features: Quick Withdraw, Normal Withdraw, Deposit, and Balance Inquiry

✅ Validating user input and preventing invalid transactions.

✅ Splitting and parsing text data to build a simple file-based database.

✅ Structuring the project using modular functions for cleaner and maintainable code.

✅ Designing a simple, clear, and user-friendly console interface.

## 🧬 Data Structure
Each client consists of:
- Account Number
- PIN Code
- Full Name
- Phone Number
- Account Balance
- 
---
<br>

## 💸 Banking Operations,
Quick Withdraw (Predefined amounts: 20, 50, 100, 200, 400, 600, 800, 1000)<br>

Normal Withdraw (Any amount that is a multiple of 5)<br>

Deposit Money<br>

Check Balance<br>

Logout<br>


## 🗂️ Client Data Management
Structured data stored in Clients.txt<br>

Each record includes:<br>

Account Number<br>
PIN<br>
Name<br>
Phone<br>
Account Balance<br>

## 💾 File Handling<br>
Read and parse client data<br>
Modify balances and save changes back to the file<br>
Supports marking records for deletion (extendable)<br>

📁 Project Structure<br>
ATM-System/<br>
│<br>
├── main.cpp          # Source code<br>
├── Clients.txt       # Client database<br>
└── README.md         # Project documentation<br>


## 🚀 How It Works<br>
User starts the program<br>
Program loads client data from Clients.txt<br>

## User enters:<br>
Account Number<br>
PIN Code<br>
If the credentials are correct → the main menu appears<br>

## User selects an operation:<br>
Quick Withdraw<br>
Normal Withdraw<br>
Deposit<br>
Check Balance<br>
Logout<br>

Any balance update is immediately saved back to the file<br>

## 📄 Example Data Format (Clients.txt)<br>

- AccountNumber#//#PinCode#//#Name#//#Phone#//#Balance<br>
- A200#//#1235#//#Shehab Abdullah#//#0536242467#//#9000<br>

## 🔮 Possible Future Enhancements<br>
Admin panel for managing clients<br>
Encryption for PIN codes<br>
Transaction history<br>
Account creation & deletion<br>
Multi-language support<br>
Better UI (GUI or web interface)<br>

## 🧑‍💻 Author<br>
Developed as a practice project for learning and personal development.<br>

## 🖥 Interface (Menu Preview)<br>

<img width="515" height="279" alt="Login Screen" src="https://github.com/user-attachments/assets/783f7525-7b4b-4477-b7e6-25e7de09bda2" />
<br>
<br>
<img width="528" height="313" alt= "ATM Main Menue Screen" src="https://github.com/user-attachments/assets/af2b262f-ddb6-4a77-9a10-f88650a78a49" />
<br>
<br>
<img width="690" height="525" alt="Quick Withdraw Screen" src="https://github.com/user-attachments/assets/9cf93417-a254-45f3-8d37-682343355e84" />
<br>
<br>
<img width="684" height="433" alt="Normal Withdraw Screen" src="https://github.com/user-attachments/assets/4755a36d-395a-4fde-8cde-abfa27aeed84" />
<br>
<br>
<img width="695" height="391" alt="Deposit Screen" src="https://github.com/user-attachments/assets/d9e2c3b3-a1b4-4858-b071-ae5e17fe89f5" />
<br>
<br>
<img width="592" height="261" alt= "Check Balance Screen" src="https://github.com/user-attachments/assets/a1e55202-bb30-49ae-8194-43880cdbfc59" />
<br>
<br>

✅ *Simple, clean, and efficient C++ project for beginners learning file-based ATM Banking systems.*
