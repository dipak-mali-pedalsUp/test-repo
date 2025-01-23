

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:15:48

This code file defines the routing for brand-related operations in an Express.js application. Its main purpose is to set up various API endpoints for brand management. Key functionalities include:

1. User authentication and authorization using middleware.
2. Brand registration and user invitation.
3. Member management (listing, removing, and activating members).
4. Profile management (viewing and updating).
5. Brand account type changes and deletion.
6. Hashtag retrieval.
7. Store details management.
8. Invoice retrieval.

The file uses Express Router to define these routes, integrating various middlewares for validation and authentication. It also links each route to specific controller functions that handle the business logic for each operation. The use of role-based authentication ensures that only authorized users can access certain endpoints.
