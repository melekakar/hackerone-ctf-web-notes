# IDOR – Insecure Direct Object Reference

## Platform
HackerOne / Hacker101 (Web CTF)

## Description
This vulnerability occurs when an application exposes internal
object identifiers without proper authorization checks.

## Observations
- Pages were assigned numeric IDs.
- IDs were predictable and sequential.
- Accessing different IDs revealed content
  that did not belong to the current user.

## Security Impact
- Unauthorized data access
- Data modification risk

## Key Lesson
Authorization must always be verified on the server side.
