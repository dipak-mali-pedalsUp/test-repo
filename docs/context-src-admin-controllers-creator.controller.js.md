

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:08:32

This code file, creator.controller.js, is part of an admin controller for managing creators in a backend system. Its main purposes and key functionalities include:

1. Managing creator lists and details:
   - Retrieving a list of creators with various filtering and sorting options
   - Fetching individual creator details

2. Creator approval process:
   - Accepting or rejecting creator requests
   - Sending verification emails to creators

3. User management:
   - Blocking and unblocking users
   - Deactivating creators

4. Session management:
   - Retrieving user session information
   - Allowing admins to act as creators (impersonation)

5. Analytics and reporting:
   - Calculating percentages of creator growth
   - Providing counts for different creator statuses (applied, approved, rejected)

6. Email communication:
   - Sending reset password emails to creators

The code uses various models (Partners, Users, BrandPartners, etc.) and integrates with external services like email sending. It also implements pagination, filtering, and sorting functionalities for efficient data retrieval and display in the admin interface.

Overall, this controller serves as a central point for admin operations related to creator management in the system.
