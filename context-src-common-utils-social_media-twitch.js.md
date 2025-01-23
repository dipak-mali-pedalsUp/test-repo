

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:21:08

This code file contains utility functions for interacting with the Twitch API. Its main purposes and key functionalities include:

1. Authentication:
   - Generating access tokens for the Twitch developer console
   - Creating user-specific access tokens for Twitch users

2. User Information:
   - Retrieving user details from Twitch, including profile information

3. Video Management:
   - Fetching a list of videos for a specific Twitch user
   - Retrieving detailed information about specific Twitch videos

The code utilizes axios for making HTTP requests to the Twitch API endpoints and handles error logging using a custom logger. It also uses the 'qs' library for stringifying query parameters.

Key functions in this file include:
- generateAccessToken: Creates an access token for the Twitch developer console
- generateUserAccessToken: Generates a user-specific access token and retrieves basic user information
- getUserDetails: Fetches detailed information about a Twitch user
- getTwitchVideoListFromUserId: Retrieves a list of videos for a specific Twitch user
- getTwitchVideoDetail: Gets detailed information about specific Twitch videos

These functions serve as a middleware layer between the application and the Twitch API, simplifying the process of authentication and data retrieval for Twitch-related operations.
