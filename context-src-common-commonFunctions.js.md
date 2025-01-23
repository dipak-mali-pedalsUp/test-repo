

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:17:12

This code file, commonFunctions.js, serves as a utility module containing various helper functions used throughout the impression-backend project. The key functionalities include:

1. Date and time manipulation:
   - Converting dates to Unix timestamps
   - Formatting epoch timestamps to various date formats (YMD, Date, DateTime)
   - Calculating time differences between dates

2. User authentication and management:
   - Checking if an email exists in the database
   - Generating password creation and reset links
   - Creating JWT tokens for password-related actions

3. Pagination:
   - Calculating pagination details for API responses

4. URL shortening and analytics:
   - Shortening URLs using an external API
   - Retrieving click counts and analytics for shortened URLs
   - Calculating total clicks and click percentages for multiple URLs

5. Random string generation:
   - Creating random strings for various purposes

6. Date range calculations:
   - Getting timestamps for previous months, current month, and custom date ranges
   - Calculating date ranges for analytics purposes

These functions are designed to be reusable across different parts of the application, providing common functionality for tasks such as user management, data formatting, and analytics calculations. The module imports necessary dependencies and exports the functions for use in other parts of the project.
