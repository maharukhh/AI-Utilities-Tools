# AI Password Strength Checker

A simple Python-based password strength checker that evaluates the security of a password using basic rules.

## About This Project

This project checks how strong a password is based on common security rules like length, character types, and complexity.

It is a beginner-friendly project demonstrating:

* Regular expressions
* Conditional logic
* Basic security concepts
* User input handling

## Features

* Checks password length (minimum 8 characters)
* Detects uppercase letters
* Detects lowercase letters
* Detects numbers
* Detects special characters
* Generates a simple strength score
* Classifies password as Weak, Medium, or Strong

## Technologies Used

* Python
* Regular Expressions (re module)

## How It Works

* User enters a password
* Program checks different conditions
* Score is calculated out of 5
* Final strength is displayed

## Project Structure

```text id="pass002"
password-strength-checker/
│
├── main.py      # Source Code
└── README.md    # Documentation
└── Output          
```

## How to Run

```bash id="pass003"
python main.py
```

## Example Usage

```text id="pass004"
Enter a password: MyPass123!

Password Strength: Strong
Score: 5 / 5
```

## Strength Criteria

| Score | Strength |
| ----- | -------- |
| 0-2   | Weak     |
| 3-4   | Medium   |
| 5     | Strong   |

## Limitations

* No entropy calculation
* No AI or machine learning
* No breach database check
* No pattern detection system
* Rule-based only

## Future Improvements

* Add entropy-based scoring
* Detect common patterns
* Add password breach checking
* Improve UI
* Add password generator

## Author

Mahrukh

Robotics & Intelligent Systems Student passionate about Artificial Intelligence, Cybersecurity basics, and Python programming.
