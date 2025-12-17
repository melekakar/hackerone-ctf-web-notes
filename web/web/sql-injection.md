# SQL Injection (SQLi)

## Platform
HackerOne / Hacker101 (Web CTF)

## Description
SQL Injection occurs when user input is directly included
in database queries without proper sanitization.

## Observations
- Numeric parameters were tested for input handling.
- Special characters caused unexpected behavior.
- Edit and update functions were more vulnerable.

## Security Impact
- Database exposure
- Data manipulation
- Authentication bypass risks

## Key Lesson
Use parameterized queries and strict input validation.
