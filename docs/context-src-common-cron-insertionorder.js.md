

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:18:19

This code file implements a cron job to automatically update the status of insertion orders in a backend system. Here are the key points:

1. Purpose: To periodically check and update the status of insertion orders based on their start and end times.

2. Key functionality:
   - Uses node-cron to schedule a task that runs every minute.
   - Retrieves insertion orders that are not in 'draft' or 'completed' status.
   - For each retrieved insertion order:
     a. If the current time is past the start time and the order is not paused, it updates the status to 'live'.
     b. If the current time is past the end time, it updates the status to 'completed'.

3. Error Handling: Logs any errors that occur during the execution of the cron job.

4. Modularity: The updateInsertionOrderStatus function is exported, allowing it to be used in other parts of the application.

This code ensures that insertion orders are automatically managed and their statuses are kept up-to-date without manual intervention, improving the efficiency and accuracy of the system.
