

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:11:46

This code file defines a set of validation rules for various authentication-related operations in a backend application. The main purpose is to ensure data integrity and security by validating user inputs before processing them. Key functionalities include:

1. Password Creation Validation:
   - Ensures email and user type are provided
   - Enforces password complexity rules (length, uppercase, lowercase, special characters, digits)
   - Requires password confirmation

2. Login Validation:
   - Validates username, password, and user type are provided

3. Password Reset Link Request Validation:
   - Validates email format and ensures type is provided

4. Link Availability Check:
   - Ensures a token is provided for checking password reset link validity

5. Current Password Check:
   - Validates that the current password is provided for password change requests

6. Password Change Validation:
   - Reuses the password complexity rules from password creation
   - Requires password confirmation

These validations can be used with a validation middleware (like express-validator) to ensure that incoming requests meet the specified criteria before being processed by the application's main logic.
