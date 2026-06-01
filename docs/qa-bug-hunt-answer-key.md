# QA Bug Hunt Answer Key

Stop here if you have not completed the exercise.

























































































































































































































# Answers

## Bug 1

Short names are accepted.

Example:

A

Expected:

Name should be rejected because it is less than 2 characters.

Actual:

Account is created.

---

## Bug 2

Emails without a dot after the @ symbol are accepted.

Example:

test@email

Expected:

Email should be rejected.

Actual:

Account is created.

---

## Bug 3

Short passwords are accepted.

Example:

123

Expected:

Password should be rejected because it is less than 8 characters.

Actual:

Account is created.

---

## Bug 4

The same account can be created multiple times.

Expected:

Duplicate email addresses should probably be blocked.

Actual:

Duplicate accounts are added to the Created Accounts list.

---

## Bug 5

Password is shown in the Created Accounts list.

Expected:

Password should not be displayed.

Actual:

Password appears on screen.

---

## Bonus Observations

- Email validation is still basic
- There is no password strength guidance
- Required fields are not marked with *
- No confirmation screen exists
- No accessibility labels are included