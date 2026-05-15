# Secure Login System

A Python-based secure login system designed to demonstrate basic application security concepts such as password hashing, authentication, account lockout, and secure user data storage.

## Features

- User Registration
- Secure Password Hashing using SHA-256
- Hidden Password Input
- Password Strength Validation
- User Authentication
- Failed Login Attempt Tracking
- Account Lockout after 3 Failed Attempts
- Persistent User Data Storage using JSON

## Technologies Used

- Python 3
- hashlib
- json
- os
- getpass

## Project Structure

```plaintext
SecureLoginSystem/
│── main.py
│── users.json
│── README.md
```

## How It Works

### Registration
Users create an account with:
- Unique username
- Strong password (minimum 8 characters and at least one number)

Passwords are securely hashed before storage.

### Login
Users log in using their credentials.

The system:
- Verifies password authenticity
- Tracks failed login attempts
- Locks account after 3 unsuccessful attempts

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/SecureLoginSystem.git
```

Navigate to the project folder:

```bash
cd SecureLoginSystem
```

Run the program:

```bash
python main.py
```

## Example Menu

```plaintext
--- Secure Login System ---
1. Register
2. Login
3. Exit
```

## Security Concepts Demonstrated

- Password Hashing
- Authentication
- Account Lockout Mechanism
- Input Validation
- Data Persistence
- Basic Access Control

## Limitations

This project is built for educational purposes.

Current limitations:
- Uses SHA-256 without salting
- No password reset feature
- No database integration

## Future Improvements

- Implement salted hashing using bcrypt
- Add password reset functionality
- Use SQLite/MySQL database
- Add email verification
- Multi-factor authentication

## Author

Charles V. Duo

## License

This project is for educational and learning purposes.
