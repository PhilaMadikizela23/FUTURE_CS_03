# FUTURE_CS_03 - API Security Risk Analysis Report

Task 3 - API Security Risk Analysis Report completed as part of the Future Interns Cyber Security Internship Program.

## Target API
JSONPlaceholder Public API (jsonplaceholder.typicode.com)

## Tools Used
- Postman
- Browser DevTools

## Endpoints Tested
- GET /users - Returns all user data
- GET /users/1 - Returns individual user data
- GET /posts - Returns all posts

## Security Risks Found
- Sensitive Data Exposure - HIGH
- Broken Object Level Authorization (BOLA) - HIGH
- No Rate Limiting - MEDIUM
- Missing Authentication - MEDIUM

## Recommendations
- Implement API key or Bearer token authentication
- Add authorization controls per user
- Enable rate limiting on all endpoints
- Minimize data returned in API responses

## Intern
- Name: Phila Madikizela
- Track: CS
- Program: Future Interns Cyber Security Internship
- Date: 27 May 2026
