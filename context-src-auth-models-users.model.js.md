

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:11:21

This code defines a Mongoose schema and model for user credentials in a MongoDB database. Here's a description of its purpose and key functionality:

1. Purpose:
   - To create a structured schema for storing user account information and authentication details.
   - To provide a model for interacting with the user data in the database.

2. Key Functionality:
   - Defines a schema (userCredentialsSchema) with various fields for user information, including:
     - Basic user details (username, email, name)
     - Authentication credentials (password, accessToken, refreshToken, adminToken)
     - Password reset functionality (password_token, password_token_created_time)
     - User type and deletion status
     - Timestamps for creation and updates

   - Uses Mongoose to create a model named "user" based on the schema.
   - Implements automatic timestamp handling for createdAt and updatedAt fields.
   - Allows for flexible field types, including strings, numbers, booleans, and ObjectId references.
   - Provides default values for several fields and enforces lowercase for email addresses.

3. Notable Features:
   - Includes fields for both access and refresh tokens, supporting a token-based authentication system.
   - Incorporates an adminToken field, suggesting different levels of user access.
   - Supports password reset functionality with dedicated token and timestamp fields.
   - Tracks the last modification date of the username.
   - Uses a custom timestamp function to store creation and update times as Unix timestamps.

This model serves as the foundation for user management and authentication in the application, providing a structured way to store and retrieve user-related data.
