

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:18:12

This code file contains functionality related to fetching and processing transaction data from Google Analytics for multiple brands. Here are the key purposes and functionalities:

1. Fetch transaction data:
   - Retrieves transaction data from Google Analytics for brands with integration enabled.
   - Uses the Google Analytics API to fetch data for each brand.
   - Filters and processes the retrieved data to extract relevant information.

2. Calculate commissions and store in database:
   - For each transaction, it calculates commissions for creators and impressions.
   - Creates new transaction records in the database.
   - Processes individual products within each transaction.
   - Determines commission rates based on campaign information or default brand settings.
   - Handles special cases like blacklisted partners.

3. Check and update order status:
   - Retrieves unfulfilled orders from the database.
   - Checks for refunds and updates order status accordingly.
   - Recalculates commission amounts based on the latest order status.
   - Updates transaction and order records in the database.

4. Helper functions:
   - Includes utility functions for finding product commissions and other details.

5. Integration with external services:
   - Uses Google Analytics API for data retrieval.
   - Interacts with various database models to store and retrieve data.

Overall, this code serves as a cron job to synchronize transaction data from Google Analytics, calculate commissions, and maintain up-to-date order statuses in the application's database.
