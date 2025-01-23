

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:09:42

This code file defines the routes for admin user operations in an Express.js application. Its main purpose is to set up the endpoints for admin-related functionalities. Key functionalities include:

1. Importing necessary modules and middleware:
   - Express for routing
   - Validation middleware
   - Authentication middleware
   - File upload utility
   - Role configuration

2. Defining routes for admin user operations:
   - POST /login: Handles admin user login with input validation
   - POST /logout: Handles admin user logout (requires authentication)
   - POST /change-password: Allows admins to change their password (requires authentication)

3. Applying middleware to routes:
   - Input validation for the login route
   - Authentication checks for logout and change-password routes
   - Role-based access control (admin and superAdmin roles)

4. Connecting routes to their respective controller functions:
   - adminUserController.login
   - adminUserController.logout
   - adminUserController.changePassword

This file serves as a central point for managing admin user-related routes, ensuring proper authentication, validation, and access control for admin operations.
