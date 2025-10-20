# Password Requirements Project

Password Requirements Project is a Python-based program that evaluates password strength based on basic security rules such as minimum length and numeric inclusion. This project demonstrates fundamental control flow, list management, and conditional logic using Python.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content
* The dataset for this project is a simple Python list containing sample passwords:
passwords = ["hello123", "cat", "secure2024", "password"]

## Business Requirements
* Evaluate whether each password meets basic security standards.
* Filter passwords that are at least 8 characters long.
* Introduce additional security rules to simulate real-world password policies.

## Hypothesis and how to validate?
* Hypothesis:
Most user-created passwords fail to meet minimal length and numeric requirements.
* Validation:
Run the program and compare how many passwords pass or fail the checks.

## Project Plan
* Project Plan

1.) Create a password list.

2.) Check each password’s length.

3.) Verify the inclusion of numbers.

4.) Store and print passwords that pass all checks.

5.) Extend functionality by defining a custom password policy.

* Code Implementation:

passwords = ["hello123", "cat", "secure2024", "password"]

pass_pass = []
pass_fail = []

for password in passwords:
    if len(password) >= 8:
        pass_pass.append(password)
    else:
        pass_fail.append(password)

print(pass_pass)

This ensures each password:

Has at least 8 characters

Includes uppercase, lowercase, and numeric characters

Contains a special symbol

## Ethical considerations
* No real user data was used. The passwords are purely synthetic examples to avoid privacy issues.

## Development Roadmap
* Add integration with user input for live password validation.
* Incorporate regex for advanced password strength scoring.
* Build a simple Tkinter or web interface.

## Main Python Libraries Used

* re – for regular expression–based pattern matching (optional for future improvements).
* Built-in functions: len(), any(), isalpha(), isdigit().

## Content:
* Inspired by Python control flow and list management exercises from Code Institute.

## Media:
* No external media or datasets used.


## Acknowledgements (optional)
* Thank the people who provided support through this project.
