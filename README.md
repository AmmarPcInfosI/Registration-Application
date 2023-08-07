# Registration System

This project is a simple registration and login system developed as a task by Ammar Al Hasani for Code Academy Oman.

## Description

The Registration System allows users to register their email, phone number, name, and password. Users can then use their registered email and password to log in to the system.

## How to Use

1. Run the program and you will be prompted with the following message:
   ```
   Enter 1 to register & 2 to Login
   ```

2. If you want to register, enter `1`, and the system will guide you through the registration process.

   - Enter your email: The system will validate the email format using regular expressions.
   - Enter your phone number: The system will validate the phone number format using regular expressions.
   - Enter your name: Provide your name.
   - Enter your password: Set your desired password.

3. If you want to log in, enter `2`, and the system will prompt you to enter your registered email and password.

4. After successful registration or login, appropriate messages will be displayed accordingly.

## Validation Rules

- Email format: The system validates the email format using the regular expression `^[a-zA-Z0-9_!#$%&'*+/=?`{|}~^.-]+@[a-zA-Z0-9.-]+$`.
- Phone number format: The system validates the phone number format using the regular expression `^(\\+968|968)[79][0-9]{7}$`.

## Note

This project serves as a basic example of a registration and login system. In real-world applications, security and additional features like encryption, database integration, and user authentication would be necessary.

**Author:** Ammar Al Hasani

**Disclaimer:** This project is intended for educational purposes and may not be suitable for production use without further development and security enhancements.