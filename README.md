# C Name Validator

A simple C program that validates a user's name and formats it for display.

## What It Does

The program takes a name as input and checks whether it follows the defined validation rules.

If the input is valid, it capitalizes the first letter of each word and displays a greeting.

## Features

- Accepts uppercase and lowercase letters
- Allows spaces between words
- Rejects digits and special characters
- Detects input that is too long
- Removes leading and trailing spaces
- Rejects repeated spaces between words
- Rejects empty or spaces-only input
- Capitalizes the first letter of each word

## Validation Rules

A name is considered valid when:

- It contains only English letters (`A-Z`, `a-z`) and spaces
- It is not empty
- It does not contain only spaces
- It does not contain consecutive spaces
- It fits within the input buffer

Leading and trailing spaces are removed before the final validation.

## Sample Input/Output

### Valid Input

**Input:** `surya raj subba`

**Output:**
- `Valid input`
- `Hello Surya Raj Subba!`

### Invalid Input

**Input:** `Surya123`

**Output:** `Invalid input!`

### Repeated Spaces

**Input:** `Surya  Raj`

**Output:** `Invalid input!`

### Input Too Long

**Input:** `abcdefghijklmnopqrst`

**Output:** `Input is too long!`

## How to Compile and Run

### Using GCC

Compile the program:

`gcc name_validator.c -o name_validator`

Run it:

`./name_validator`

### Windows

If using GCC/MinGW:

`gcc name_validator.c -o name_validator.exe`

`name_validator.exe`

## Concepts Practiced

- Character arrays and strings
- `fgets()`
- `strlen()`
- `strchr()`
- `strcspn()`
- Loops
- Conditional statements
- Input validation
- String manipulation
- Input buffer handling

## Author

**Surya Raj Subba**
