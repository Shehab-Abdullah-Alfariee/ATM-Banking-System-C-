ATM Banking System (C++)

A simple console-based ATM Banking System built in C++.
The program allows users to log in using an account number and PIN, then perform basic banking operations such as withdraw, deposit, and balance inquiry.
All client data is stored in a local text file (Clients.txt).

📌 Features
🔐 User Authentication
Login with Account Number + PIN Code
Validates client information from the data file

💸 Banking Operations
Quick Withdraw (Predefined amounts: 20, 50, 100, 200, 400, 600, 800, 1000)
Normal Withdraw (Any amount that is a multiple of 5)
Deposit Money
Check Balance
Logout

🗂️ Client Data Management
Structured data stored in Clients.txt
Each record includes:
Account Number
PIN
Name
Phone
Account Balance

💾 File Handling
Read and parse client data
Modify balances and save changes back to the file
Supports marking records for deletion (extendable)

📁 Project Structure
ATM-System/
│
├── main.cpp          # Source code
├── Clients.txt       # Client database
└── README.md         # Project documentation

🛠️ Technologies Used

C++ (OOP + file handling + standard library)
iostream
fstream
vector
iomanip
string

🚀 How It Works
User starts the program
Program loads client data from Clients.txt

User enters:
Account Number
PIN Code
If the credentials are correct → the main menu appears

User selects an operation:
Quick Withdraw
Normal Withdraw
Deposit
Check Balance
Logout

Any balance update is immediately saved back to the file

📄 Example Data Format (Clients.txt)

1234#//#0000#//#John Doe#//#555-1234#//#1500
5678#//#1234#//#Alice Smith#//#555-9876#//#2500

🔮 Possible Future Enhancements

Admin panel for managing clients
Encryption for PIN codes
Transaction history
Account creation & deletion
Multi-language support
Better UI (GUI or web interface)

📜 License
This project is free to use for learning and personal development




📷 Screenshots (Optional)

<img width="515" height="279" alt="Login Screen" src="https://github.com/user-attachments/assets/783f7525-7b4b-4477-b7e6-25e7de09bda2" />

<img width="528" height="313" alt= "ATM Main Menue Screen" src="https://github.com/user-attachments/assets/af2b262f-ddb6-4a77-9a10-f88650a78a49" />

<img width="690" height="525" alt="Quick Withdraw Screen" src="https://github.com/user-attachments/assets/9cf93417-a254-45f3-8d37-682343355e84" />

<img width="684" height="433" alt="Normal Withdraw Screen" src="https://github.com/user-attachments/assets/4755a36d-395a-4fde-8cde-abfa27aeed84" />

<img width="695" height="391" alt="Deposit Screen" src="https://github.com/user-attachments/assets/d9e2c3b3-a1b4-4858-b071-ae5e17fe89f5" />

<img width="592" height="261" alt= "Check Balance Screen" src="https://github.com/user-attachments/assets/a1e55202-bb30-49ae-8194-43880cdbfc59" />





You can add terminal screenshots here
