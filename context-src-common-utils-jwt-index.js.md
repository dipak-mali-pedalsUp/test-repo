

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:19:50

This code file provides utility functions for JSON Web Token (JWT) operations in a Node.js application. The main purposes and key functionalities are:

1. Token Creation:
   - `createToken`: Creates a JWT with a specified secret, expiration time, and payload.
   - `createPasswordToken`: Creates a JWT specifically for password-related operations, without an expiration time.

2. Token Verification:
   - `verifyPasswordToken`: Verifies a password-specific JWT using the provided secret.
   - `validateToken`: Validates a given JWT, handling both regular and admin tokens. It also supports the "Bearer" token format.

3. Error Handling:
   All functions use try-catch blocks and return Promises, allowing for proper error handling in asynchronous operations.

4. Flexibility:
   The code allows for different secrets to be used for regular and admin tokens, enhancing security and separation of concerns.

5. Module Exports:
   The file exports four main functions: validateToken, createToken, createPasswordToken, and verifyPasswordToken, making them available for use in other parts of the application.

This utility module centralizes JWT operations, promoting code reuse and consistent token handling across the application.
