

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:15:42

This code file defines the routing for analytics-related endpoints in an Express.js application, specifically for brand users. The main purpose and key functionalities include:

1. Setting up an Express router for handling analytics routes.

2. Implementing authentication middleware to ensure only authorized brand users can access these routes.

3. Defining various GET routes for different analytics endpoints, including:
   - Campaign analytics (overall and detailed)
   - IO (Insertion Order) analytics (overall and detailed)
   - Revenue, spend, and click charts for both campaigns and IOs

4. Utilizing a controller (analyticsController) to handle the logic for each route.

5. Organizing routes into logical groups (campaign-related and IO-related) for better maintainability.

6. Implementing role-based access control using the 'roles.branduser' configuration.

7. Providing endpoints for retrieving various types of analytics data, such as revenue charts, spend charts, click charts, and detailed information for both campaigns and IOs.

Overall, this file serves as a central hub for routing analytics-related requests to the appropriate controller functions, ensuring that only authenticated brand users can access this sensitive data.
