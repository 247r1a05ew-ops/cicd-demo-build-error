# Build Error Demo

This project demonstrates a BUILD failure.

## Error

The Python file contains a syntax error.

The closing parenthesis is missing from the print statement.

## Expected CI/CD Result

BUILD -> FAIL
TESTS -> SKIPPED

## Fix

Change:

print("Total:", calculate_total(10, 20)

to:

print("Total:", calculate_total(10, 20))
