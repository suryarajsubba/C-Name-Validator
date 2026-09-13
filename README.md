# C Name Validator

A beginner-friendly C program that validates and formats a user's name using string handling and input validation.

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

The input is considered valid if:

- It contains only English letters (`A-Z`, `a-z`) and spaces.
- It is not empty.
- It does not contain only spaces.
- It does not contain repeated consecutive spaces.
- Its length fits within the program's input buffer.

Leading and trailing spaces are removed before the final validation.

## Sample Input/Output

### Valid Input

```text
Enter your name:   surya raj subba
Valid input
Hello Surya Raj Subba!
