

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:19:24

This code file, token.service.js, is a service module for handling token generation and verification in an authentication system. Its main purposes and key functionalities are:

1. Token Generation:
   - The `generateTokens` function creates JWT tokens for users based on their role and payload.
   - It handles two scenarios: admin tokens and regular user tokens.
   - For admin users, it generates an admin token with a specific expiry time.
   - For regular users, it generates both an access token and a refresh token.
   - The generated tokens are stored in the user's document in the database along with their expiry time.

2. Token Verification:
   - The `verifyToken` function checks the validity of a given token for a user.
   - It verifies if the token exists in the database for the specified user.
   - It checks if the token has expired based on the stored expiry time.
   - It compares the provided token with the stored access token or admin token.
   - If any verification fails, it clears the token information from the user's document.

3. Database Integration:
   - The module interacts with a MongoDB database using the Users model to store and retrieve token information.
   - It updates user documents with new token information and expiry times.

4. Configuration:
   - The module uses configuration settings for JWT secrets and expiry times, allowing for easy customization.

Overall, this module provides essential functionality for managing authentication tokens, ensuring secure access to protected resources, and maintaining token validity over time.
