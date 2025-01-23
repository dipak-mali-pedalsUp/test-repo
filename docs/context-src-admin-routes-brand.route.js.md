

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:09:51

This code file defines the routing for brand-related operations in an admin panel of a backend application. Here's a summary of its purpose and key functionality:

1. Purpose:
   - To define and manage API routes for brand-related operations
   - To handle authentication and authorization for these routes
   - To connect routes with appropriate controller functions

2. Key Functionality:
   - Imports necessary modules, middlewares, and controllers
   - Sets up an Express router
   - Defines various routes for brand management, including:
     * Getting a list of brands
     * Retrieving brand analytics
     * Activating and deactivating brands
     * Setting commission ratios for brands and campaigns
     * Retrieving campaign-related charts and details
     * Sending invitation emails to brands
     * Getting brand invoice details

3. Authentication and Authorization:
   - Uses the 'auth' middleware to protect routes
   - Restricts access to admin and superAdmin roles

4. Data Validation:
   - Implements validation for the invitation email route using the 'validates' middleware

5. Route Organization:
   - Groups related routes together (e.g., campaign-related routes)
   - Provides a clear structure for managing brand-related API endpoints

This file serves as a central location for defining and organizing all brand-related routes in the admin section of the application, ensuring proper authentication, authorization, and data flow between the client and the server.
