# QA Bug Hunt Requirements

## Account Creation

A user should only be able to create an account when all fields are valid.

## Name Rules

- Name is required
- Name must be at least 2 characters long

## Email Rules

- Email is required
- Email must contain an @ symbol
- Email must contain a dot after the @ symbol

## Password Rules

- Password is required
- Password must be at least 8 characters long

## Created Accounts List

When a valid account is created:

- The account appears in the Created Accounts list
- The password should not be displayed
- Duplicate email addresses should not be allowed

## Reset Button

When Reset is clicked:

- Name field clears
- Email field clears
- Password field clears
- Message clears
- Created Accounts list remains visible