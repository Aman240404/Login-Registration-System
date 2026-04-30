# Login-Registration-System
A simple console-based Login and Registration System built in C++ that stores user credentials in a local file and supports basic authentication.

📌 Features

User Registration with username and password
User Login with credential verification
Persistent storage using a local text file (users.txt)
Simple and clean menu-driven interface
Handles invalid menu choices gracefully


🛠️ Tech Stack
ComponentDetailsLanguageC++File I/Ofstream (ifstream, ofstream)StoragePlain text file (users.txt)InterfaceConsole / Terminal

📂 Project Structure
login-registration-system/
│
├── main.cpp          # Main source file
├── users.txt         # Auto-generated file storing registered users
└── README.md         # Project documentation

🚀 Getting Started
Prerequisites

A C++ compiler (g++, MSVC, or Clang)
Terminal / Command Prompt

Compilation
bashg++ main.cpp -o login_system
Run
bash./login_system        # Linux / macOS
login_system.exe      # Windows

💻 Usage
Once you run the program, you'll see:
1. Register
2. Login
3. Exit
Enter your choice:

Option 1 — Register: Enter a new username and password. Credentials are saved to users.txt.
Option 2 — Login: Enter your credentials. The system verifies them against stored records.
Option 3 — Exit: Closes the application.


📸 Sample Output
1. Register
2. Login
3. Exit
Enter your choice: 1

Enter a username: john_doe
Enter a password: mypassword123
Registration successful!

Enter your choice: 2

Enter username: john_doe
Enter password: mypassword123
Login successful!

⚠️ Limitations & Future Improvements

This project is built for learning purposes. The following improvements can be made for production use:


 Password hashing (e.g., SHA-256) instead of plain text storage
 Input validation (empty fields, special characters)
 Duplicate username check during registration
 Encrypted file storage
 GUI interface using Qt or a web front-end
 Database integration (MySQL / SQLite)


🧠 Concepts Covered

File handling in C++ (fstream, ifstream, ofstream)
Functions and modular code design
Loops and switch-case control flow
Basic authentication logic

