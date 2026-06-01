# QA Bug Hunt Challenge 🕵️‍♀️

## Goal

Test the account creation page like a QA Engineer.

Open:

code-examples/qa-bug-hunt.html

using Live Server.

Your job is to check whether the page follows the requirements below.

---

## Requirements

The form should allow a user to create an account only when:

1. Name is not empty
2. Name is at least 2 characters long
3. Email is not empty
4. Email contains an @ symbol
5. Email contains a dot after the @ symbol
6. Password is not empty
7. Password is at least 8 characters long

---

## Expected Behaviour

If all details are valid:

- show: Account created successfully
- add the account to the Created Accounts list on the page

If details are invalid:

- show a clear error message
- do not add the account to the Created Accounts list

If Reset is clicked:

- clear all fields
- clear the message
- keep the Created Accounts list visible

---

## What To Test

Try:

- empty fields
- short names
- invalid emails
- short passwords
- valid account details
- reset button
- creating multiple accounts

---

## Record Your Bugs

Create this file:

docs/qa-bug-hunt-results.md

Use this format:

## Bug Title

Severity:
Priority:

Steps to Reproduce:

1.
2.
3.

Expected Result:

Actual Result:

Notes:

---

## Do Not Open Yet

Do not open:

docs/qa-bug-hunt-answer-key.md

until you finish testing.