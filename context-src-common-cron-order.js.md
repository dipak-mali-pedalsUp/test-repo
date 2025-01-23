

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:18:37

This code file contains functionality for managing orders and transactions in an e-commerce system. The main purposes and key functionalities include:

1. Fetching order lists from integrated brands (likely Shopify stores).
2. Processing and storing transaction data, including calculating commissions for creators and the platform (Impression).
3. Handling refunds and creating credit memos when necessary.
4. Updating order statuses and recalculating commissions based on fulfillment status.
5. Determining product commissions based on campaign settings, partner groups, and brand default commissions.
6. Adding detailed product information to transactions, including commission calculations.

The code includes two main cron jobs:
1. fetchOrderListCron: Retrieves new orders from integrated stores, processes them, and stores the data in the database.
2. checkOrderStatus: Updates the status of existing orders and recalculates commissions if necessary.

Additionally, there are helper functions for finding product commissions and adding product details to transactions. The code interacts with various models, including BrandModel, TransactionModel, and CampaignModel, to manage the complex relationships between brands, orders, products, and campaigns.
