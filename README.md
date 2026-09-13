# C Name Validator

A simple C program that validates a user's name and formats it for display.

## What It Does

The program takes a name as input and checks whether it follows the defined validation rules.

If the input is valid, it capitalizes the first letter of each word and displays a greeting.

## Features

- Accepts letters and spaces
- Rejects numbers and special characters
- Detects input that is too long
- Removes leading and trailing spaces
- Rejects repeated spaces
- Rejects empty or spaces-only input
- Capitalizes the first letter of each word

## Example

### Valid Input

**Input:**
    
    Enter your name:   surya raj subba

**Output:**

    Valid input
    Hello Surya Raj Subba!

### Invalid Input

**Input:**

    Enter your name: Surya123

**Output:**

    Invalid input!

## Validation Rules

A name is considered valid when:

- It contains only letters (`A-Z`, `a-z`) and spaces
- It is not empty
- It does not contain only spaces
- It does not contain consecutive spaces
- It fits within the input buffer

Leading and trailing spaces are removed before the final validation.

## Concepts Practiced

- Character arrays and strings
- `fgets()`
- `strlen()`
- `strchr()`
- `strcspn()`
- Loops and conditional statements
- Input validation
- String manipulation
- Input buffer handling

## How to Run

Compile using GCC:

    gcc name_validator.c -o name_validator

Run:

    ./name_validator

## Author

**Surya Raj Subba**
