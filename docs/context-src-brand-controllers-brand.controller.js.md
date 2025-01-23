

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:12:11

This code file contains a set of controller functions for managing brand-related operations in a backend application. The key functionalities include:

1. User Management:
   - Brand signup
   - Sending invitations to brand members
   - Getting a list of brand members
   - Removing and activating brand members
   - Updating user profiles
   - Deleting user accounts

2. Brand Management:
   - Retrieving brand profile details
   - Updating brand profiles
   - Changing brand account types (private/public)
   - Adding and managing brand store technical details

3. Hashtag Management:
   - Retrieving a list of hashtags used by brands and campaigns

4. Integration with E-commerce Platforms:
   - Adding and storing brand store technical details (e.g., for Shopify integration)

The code uses various models (Brands, BrandUsers, Users, etc.) to interact with the database and includes error handling and logging. It also integrates with external services like email sending for invitations and password resets. The controller functions handle HTTP requests, process data, interact with the database, and send appropriate responses back to the client.
