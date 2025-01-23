

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:15:23

This code defines a Mongoose schema and model for transactions in an e-commerce or affiliate marketing system. The main purpose and key functionalities are:

1. Schema Definition: It creates a schema for transactions with fields such as transaction ID, partner ID, brand ID, basket value, creator and impression take-home amounts, order status, and timestamps.

2. Relationships: It establishes relationships with other models (Partners and Brand) using references.

3. Order Status Tracking: It includes an order_status field with a default value of "Unfulfilled", allowing for order status management.

4. Financial Information: It stores important financial data like basket value, creator take-home, and impression take-home amounts.

5. Refund Handling: It includes fields for refund ID and actual transaction ID, enabling refund processing and tracking.

6. Soft Delete: An is_deleted field is included for soft delete functionality.

7. Timestamps: It automatically manages creation and update timestamps in Unix timestamp format.

8. Model Creation: Finally, it creates a Mongoose model named "Transaction" based on the defined schema, which can be used for database operations related to transactions.

This model serves as the backbone for managing and storing transaction data in the application, likely used for financial tracking, order management, and reporting purposes.
