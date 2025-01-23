

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:12:43

This code file contains controller functions for managing Insertion Orders (IOs) in a brand management system. The key functionalities include:

1. Getting a list of Insertion Orders with filtering and pagination
2. Retrieving Insertion Orders with only name and ID
3. Creating new Insertion Orders
4. Fetching details of a specific Insertion Order
5. Updating existing Insertion Orders
6. Deleting Insertion Orders
7. Pausing and resuming Insertion Orders
8. Changing the mode (status) of Insertion Orders

The code interacts with the insertionOrder and campaignModel models to perform CRUD operations and manage the relationships between Insertion Orders and Campaigns. It handles various status changes based on start and end dates, and ensures that Insertion Orders cannot be deleted if they have associated active campaigns.

The controller functions implement error handling, input validation, and proper HTTP status code responses. They also use logging for tracking errors and important operations.

Overall, this code file serves as the backend logic for managing Insertion Orders within a larger advertising or marketing platform, allowing brands to create, modify, and control their advertising orders and associated campaigns.
