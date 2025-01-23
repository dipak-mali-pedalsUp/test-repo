

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:13:39

This code defines a Mongoose schema and model for brand users in a backend application. Here's a description of its purpose and key functionality:

1. Purpose:
   - To create a structured data model for brand users in a MongoDB database.
   - To establish relationships between brand users and their associated brands.

2. Key Functionality:
   - Defines a schema (brandUsersSchema) with fields for name, email, brand_id, added_by, is_deleted, createdAt, and updatedAt.
   - Uses Mongoose to create a model called "BrandUser" based on this schema.
   - Establishes a relationship with the brand model using the brand_id field.
   - Implements automatic timestamp handling for creation and update times.
   - Provides a structure for storing and managing brand user data in the application.

3. Notable Features:
   - Email field is set to lowercase and required.
   - brand_id field references the brand model, creating a relationship between users and brands.
   - Includes an is_deleted flag for soft deletion.
   - Uses Unix timestamp (seconds since epoch) for createdAt and updatedAt fields.

This model can be used to create, read, update, and delete brand user records in the MongoDB database, as well as to establish relationships between users and brands in the application.
