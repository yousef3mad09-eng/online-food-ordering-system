# Login Page Test Cases

- **Project:** DEPI Mini Project, Manual Software Testing
- **Team:** Group Server
- **Supervisor:** Eng. Mahmoud Raslan
## Team
Hatem Amin, Youssef Emad, Omar Shawky, Basmala Ali, Mariam Ahmed

## Project Idea
Write test cases for a login form covering valid input, invalid input,
empty fields and long input, with positive and negative scenarios
and expected results.

## Files
| File | Description |
|---|---|
| Mini Project.xlsx | 20 test cases (ID, Title, Pre.conditions, Steps, Expected results, Status) |
| login_test_cases_presentation.pptx | Project presentation |
| user_story_secure_login.pdf | User story and acceptance criteria (AC1 to AC10) |

## Coverage
The test cases cover acceptance criteria AC1 to AC10:
- AC1/AC4: valid login, password case, offline login, show/hide icon
- AC2/AC3: empty and wrong credentials, error messages
- AC5/AC7: SQL injection and account lockout
- AC6/AC8: length limits and script injection
- AC9/AC10: HTTPS and Forgot Password

## Assumptions
- Test account: user@example.com
- Maximum length: 100 characters
- Lockout: 5 failed attempts for 15 minutes
- Email is not case-sensitive, password is case-sensitive
