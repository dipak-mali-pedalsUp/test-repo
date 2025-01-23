

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:20:44

This code file, located at /home/pedalsup/Documents/Projects/impression-backend/src/common/utils/social_media/meta.js, provides utility functions for interacting with Meta (Facebook) APIs, specifically for Instagram business accounts. The main purposes and key functionalities of this code are:

1. Generate Long-Lived Access Tokens:
   - The `generateLongLivedToken` function exchanges a short-lived access token for a long-lived one using the Facebook Graph API.
   - It uses the app's credentials (ID and secret) to make this exchange.

2. Fetch Instagram Username:
   - After obtaining the long-lived token, it calls `getUserInstagramUserName` to retrieve the associated Instagram business account username.

3. Error Handling:
   - The code includes comprehensive error handling for API requests, logging errors, and providing user-friendly error messages.

4. Instagram Business Account Retrieval:
   - The `getUserInstagramUserName` function fetches the user's Facebook pages, identifies the one with an associated Instagram business account, and retrieves the Instagram username.

5. API Interaction:
   - The code uses axios for making HTTP requests to the Facebook Graph API.
   - It handles API versioning and constructs appropriate API endpoints.

6. Configuration:
   - The code relies on a configuration file for sensitive information like API versions, app IDs, and secrets.

Overall, this module serves as a crucial component for authenticating and identifying Instagram business accounts, likely as part of a larger system for social media management or analytics.
