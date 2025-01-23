

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:15:33

This code defines a Mongoose schema and model for transaction orders in an e-commerce or affiliate marketing system. The main purpose and key functionality of this code include:

1. Schema Definition: It creates a detailed schema for transaction orders, including information about the transaction, partner, brand, campaign, and product details.

2. Relationships: The schema establishes relationships with other models such as Transactions, Partners, Brands, and Campaigns using references.

3. Order Details: It captures essential order information like product details, price, quantity, and total amount.

4. Commission Tracking: The schema includes fields for tracking commissions, including ratios for creators and the platform (Impression).

5. Order Status: It maintains the status of the order, with a default status of "Unfulfilled".

6. Timestamps: The schema automatically adds creation and update timestamps to each document.

7. Refund and Return Handling: It includes fields to track if an order has been returned or refunded.

8. Soft Delete: The schema includes an "is_deleted" field for soft deletion of records.

9. Model Creation: Finally, it creates a Mongoose model named "TransactionOrders" based on this schema, which can be used to interact with the corresponding MongoDB collection.

This model serves as a crucial component for managing and tracking orders, commissions, and related data in the system's backend.
