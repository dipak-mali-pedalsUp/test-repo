

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:19:42

This code file contains utility functions for interacting with the Shopify API. Its main purposes and key functionalities include:

1. Fetching product details:
   - The `getProductDetailFromLink` function retrieves product information based on a given product link.
   - It paginates through all products to find the matching product using the extracted product slug.

2. Retrieving order details:
   - The `getOrderDetail` function fetches specific order information using a transaction ID.

3. Fetching order lists:
   - The `getOrderList` function retrieves a list of orders with pagination support and filtering by update time.
   - It uses a GraphQL query to fetch order data, including customer journey information.

4. Getting product details by ID:
   - The `getProductDetailFromId` function retrieves product information using a specific product ID.

5. Helper functions:
   - `getTotalCountOfProducts` fetches the total number of products in the Shopify store.
   - `extractProductSlug` extracts the product slug from a given URL.

The code uses axios for making HTTP requests to the Shopify API and includes error handling and logging. It's designed to work with Shopify's REST and GraphQL APIs, handling authentication through access tokens.
