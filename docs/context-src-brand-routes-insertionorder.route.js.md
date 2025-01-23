

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:16:11

This code file defines the routes for handling Insertion Order operations in an Express.js application. Its main purpose is to set up API endpoints for managing insertion orders, likely in the context of a brand management system. Key functionalities include:

1. Importing necessary dependencies, including Express, validation middleware, authentication middleware, and the insertion order controller.

2. Defining routes for various insertion order operations:
   - Creating a new insertion order
   - Creating a draft insertion order
   - Retrieving all insertion orders
   - Getting a list of insertion orders with only names and IDs
   - Retrieving details of a specific insertion order
   - Deleting an insertion order
   - Pausing an insertion order
   - Changing the mode of an insertion order
   - Updating an existing insertion order

3. Implementing authentication for all routes, restricting access to users with the 'branduser' role.

4. Applying validation middleware to the creation and update routes to ensure data integrity.

5. Routing requests to appropriate controller functions for handling business logic.

This file serves as a central point for managing insertion order-related API endpoints, ensuring proper authentication, validation, and routing of requests to the correct handlers.
