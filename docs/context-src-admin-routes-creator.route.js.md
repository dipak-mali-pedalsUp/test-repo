

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:09:59

This code file defines the routing for creator-related operations in the admin section of an Express.js application. Its primary purpose is to set up various API endpoints for managing creators and their transactions. Key functionalities include:

1. Importing necessary modules and middlewares, including authentication, role-based access control, and file upload utilities.

2. Defining routes for creator management, such as:
   - Retrieving creator lists and details
   - Accepting or rejecting creator requests
   - Deactivating creators
   - Sending verification and password reset emails
   - Blocking and unblocking users
   - Retrieving session logs and partner counts

3. Implementing role-based access control, restricting these routes to admin and superAdmin roles.

4. Setting up routes for creator transaction management, specifically for retrieving payout details.

5. Providing an "act as creator" functionality for administrators.

All routes are protected by authentication middleware and are designed to be used by administrative users to manage and oversee creator accounts and activities within the system.
