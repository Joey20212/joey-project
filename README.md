# joey-project
Password strength che# Password Strength Checker

This is a Python project that checks the strength of a user's password based on several criteria including length, use of uppercase and lowercase letters, numbers, and special characters.

## Features

- Checks if the password contains:
  - At least 6 characters
  - Both uppercase and lowercase letters
  - Numbers
  - Special characters (e.g., @, $, !, %, *, #, etc.)
- Classifies passwords as **Weak**, **Moderate**, or **Strong** based on these criteria.

## How It Works

1. The user inputs a password.
2. The program evaluates the password based on:
   - Length (minimum 6 characters)
   - Use of uppercase letters
   - Use of lowercase letters
   - Use of digits
   - Use of special characters
3. The program outputs the strength of the password:
   - **Weak**: If it does not meet basic criteria.
   - **Moderate**: If it meets most criteria but lacks some security.
   - **Strong**: If it meets all criteria and is sufficiently long.

## Requirements

- Python 3.x
- No external libraries required.

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/password-strength-checker.git
   cd password-strength-checker
2. python password_strength_checker.py
$ python password_strength_checker.py
3. Enter a password: P@ssw0rd!
Password strength: Strong
