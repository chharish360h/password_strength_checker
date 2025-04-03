Password Strength Checker

Overview

This Python script evaluates the strength of a user-inputted password based on various criteria. It provides a strength score and feedback on how to improve the password.

Features

Checks for the presence of lowercase and uppercase letters

Ensures the password contains numbers

Verifies the length of the password (minimum 9 characters)

Requires at least one special character

Provides feedback based on the password's strength

Usage

Run the script in a Python environment.

Enter a password when prompted.

The script will evaluate the password and display a score along with improvement suggestions.

Strength Criteria

Criteria

Points Awarded

Contains at least one lowercase letter

+1

Contains at least one uppercase letter

+1

Contains at least one number

+1

Password length is at least 9 characters

+1

Contains at least one special character

+1

Scoring System

1 Point: Very weak password, must be changed.

2 Points: Weak password, consider improving.

3 Points: Okay password, but could be stronger.

4 Points: Strong password, but could still be improved.

5 Points: Very strong password, difficult to crack.

Requirements

Python 3.x

No external dependencies (uses built-in string module)
