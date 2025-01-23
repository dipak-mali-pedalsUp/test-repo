

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:20:35

This code file provides utility functions for retrieving product and order information from e-commerce platforms, specifically focusing on Shopify integration. The main purposes and key functionalities include:

1. Product Information Retrieval:
   - findProductDetail: Fetches product details based on a brand ID and product link.
   - findProductDetailFromId: Retrieves product information using a brand ID and product ID.

2. Order Information Retrieval:
   - findOrderDetail: Obtains detailed order information for a specific transaction.
   - findOrderList: Retrieves a list of recent orders (within the last 15 minutes) for a given brand.

3. Platform Flexibility:
   The code is designed to work with different e-commerce platforms, though currently it only implements Shopify functionality.

4. UTM Parameter Tracking:
   The findOrderList function specifically looks for orders with UTM parameters related to "impression" campaigns, collecting relevant data for tracking and attribution.

5. Pagination Handling:
   The order list retrieval implements cursor-based pagination to fetch all relevant orders, even when they span multiple pages.

6. Data Transformation:
   The code extracts and formats specific fields from the raw API responses to create standardized output objects for products and orders.

Overall, this utility module serves as a bridge between the application and e-commerce platforms, abstracting the complexities of API interactions and data formatting.
