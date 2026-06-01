# QA Bug Hunt Answer Key

STOP HERE IF YOU HAVE NOT COMPLETED THE EXERCISE.












































































































































































































# Answers

## Bug 1

Short names are accepted.

Example:

A

Expected:

Name should be rejected because it is less than 2 characters.

Actual:

Account is created.

## Bug 2

Emails without a dot after the @ symbol are accepted.

Example:

test@email

Expected:

Email should be rejected.

Actual:

Account is created.

## Bug 3

Short passwords are accepted.

Example:

123

Expected:

Password should be rejected because it is less than 8 characters.

Actual:

Account is created.

## Bug 4

Duplicate email addresses are allowed.

Expected:

Duplicate accounts should be blocked.

Actual:

The same email can be added more than once.

## Bug 5

Password is displayed in the Created Accounts list.

Expected:

Password should not be shown.

Actual:

Password appears on screen.

## Bonus Observations

- Email validation is weak
- Password rules are not displayed clearly
- Required fields are not marked
- No accessibility labels are included