# C Name Validator

A beginner-friendly C program that validates and formats a user's name using string handling and input validation.

## Features

* Accepts uppercase and lowercase letters
* Allows spaces between words
* Rejects digits and special characters
* Detects input that is too long
* Removes leading and trailing spaces
* Rejects repeated spaces between words
* Rejects empty or spaces-only input
* Capitalizes the first letter of each word

## Validation Rules

The input is considered valid if:

* It contains only English letters (`A-Z`, `a-z`) and spaces
* It is not empty
* It does not contain only spaces
* It does not contain repeated consecutive spaces
* Its length fits within the input buffer

Leading and trailing spaces are removed before the final validation.

## Sample Input/Output

### Valid Input

**Input:** `surya raj subba`

**Output:** `Valid input`
`Hello Surya Raj Subba!`

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

Compile:

`gcc name_validator.c -o name_validator`

Run:

`./name_validator`

### Windows

Compile:

`gcc name_validator.c -o name_validator.exe`

Run:

`name_validator.exe`

## Concepts Practiced

* Character arrays and strings
* `fgets()`
* `strlen()`
* `strchr()`
* `strcspn()`
* Loops
* Conditional statements
* Input validation
* String manipulation
* Input buffer handling

## Author

**Surya Raj Subba**
