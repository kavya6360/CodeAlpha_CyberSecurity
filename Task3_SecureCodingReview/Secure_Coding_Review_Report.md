# Secure Coding Review Report

## Introduction
Secure coding is an important part of software development that helps
protect applications from security threats and vulnerabilities.
In this task, a simple login program was reviewed to identify insecure
coding practices and then improved using secure coding techniques.

## Description of Insecure Code
The initial login program contained several security weaknesses.
The username and password were directly written in the source code
and compared using plain text input.

### Issues Identified:
- Password was stored in plain text inside the code
- Anyone with access to the code could see the credentials
- Easy for attackers to guess or misuse login details
- No protection for sensitive user information

These issues can lead to unauthorized access and data breaches.

## Secure Coding Improvements
To improve security, the insecure login program was rewritten using
secure coding practices.

### Improvements Made:
- Password is not stored in plain text
- Password is converted into a hashed value using SHA-256
- User input password is also hashed before comparison
- Sensitive information is protected from direct exposure
Hashing ensures that even if someone sees the stored value, the
original password cannot be easily retrieved.

## Comparison Between Insecure and Secure Code
| Insecure Code | Secure Code |
|--------------|------------|
| Plain text password | Hashed password |
| Easy to read credentials | Protected credentials |
| High security risk | Reduced security risk |
| Not safe for real use | Safer for applications |

## Benefits of Secure Coding
- Protects sensitive user data
- Reduces chances of cyber attacks
- Prevents unauthorized access
- Improves reliability of applications
- Builds trust in software systems

## Learning Outcome
Through this task, I learned the importance of secure coding practices
and how small changes in code can significantly improve application security.
This task helped me understand how insecure coding can introduce
vulnerabilities and how to fix them using secure techniques.

## Conclusion
Secure coding plays a vital role in cybersecurity.
By identifying vulnerabilities and applying secure coding practices,
applications can be made safer and more reliable.
This task provided practical knowledge on improving code security.
