# Stored XSS / HTML Injection

## Platform
HackerOne / Hacker101 (Web CTF)

## Description
Stored XSS occurs when user input is saved and later
rendered without proper output encoding.

## Observations
- Input fields accepted raw HTML.
- Injected content appeared in multiple pages.
- HTML event handlers worked without <script> tags.

## Security Impact
- Persistent JavaScript execution
- User session compromise

## Key Lesson
Filtering input is not enough.
Context-aware output encoding is required.

