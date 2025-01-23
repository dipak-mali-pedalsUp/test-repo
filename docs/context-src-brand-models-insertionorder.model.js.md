

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:14:39

This code defines a Mongoose schema and model for an "Insertion Order" in a backend application. Here's a summary of its purpose and key functionality:

1. Purpose:
   - To create a structured data model for insertion orders, which are likely used in an advertising or marketing context.

2. Key Functionality:
   - Defines the structure of an insertion order with fields such as name, description, start and end dates, order type, price, and associated brand.
   - Uses Mongoose to create a schema and model for database interaction.
   - Includes fields for tracking the order's status, deletion state, and whether it's a default order.
   - Implements automatic timestamp creation for createdAt and updatedAt fields.

3. Notable Features:
   - References external constants for order types and statuses.
   - Links to a brand model using a reference to the brand's ObjectId.
   - Uses custom timestamp handling to store timestamps as Unix timestamps (seconds since epoch).

This model serves as the foundation for creating, retrieving, updating, and deleting insertion orders in the application's database, likely MongoDB.
