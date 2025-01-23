

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:09:00

This code file contains controllers for managing order-related operations in an admin panel. The key functionalities include:

1. getOrderAnalytics: Retrieves and calculates order analytics, including total order value, total impression value, and total creator value for a specified date range or the current month.

2. getOrderList: Fetches a paginated list of orders with filtering options. It includes details about transactions, associated brands, and partners.

3. getOrderDetail: Retrieves detailed information about a specific order, including transaction details, brand information, and partner data.

4. calculateOrderPercentage: A helper function that calculates percentage changes in order values, creator take-home, and impression take-home between the current month and the previous month.

The code interacts with various models (Partners, Users, TransactionModel, TransactionOrderModel, BrandModel) to fetch and aggregate data. It also uses common utilities for pagination, date range calculations, and error handling.

The controllers are designed to provide data for an admin dashboard, allowing administrators to view and analyze order-related information, track performance metrics, and access detailed order information.
