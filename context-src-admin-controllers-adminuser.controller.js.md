

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:08:11

This code file contains controller functions for managing admin user operations in a backend application. The key functionalities include:

1. Admin Login:
   - The `login` function authenticates admin users.
   - It verifies the provided username and password against the database.
   - If successful, it generates and returns authentication tokens.

2. Admin Logout:
   - The `logout` function handles admin user logout.
   - It clears the user's authentication tokens from the database.

3. Change Password:
   - The `changePassword` function allows admin users to change their passwords.
   - It verifies the old password, ensures the user exists, and updates the password if everything is correct.

The code uses various utilities and services, such as:
- JWT for token generation and management
- Crypto for password hashing
- HTTP status codes for standardized responses
- Logging for error tracking

Overall, this controller manages the authentication and password-related operations for admin users in the system.
