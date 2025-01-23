

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:13:54

This code defines a Mongoose schema and model for campaign products in a brand-related application. The main purpose and key functionalities are:

1. Schema Definition: It creates a mongoose schema called `campaignProductsSchema` that defines the structure and properties of campaign products.

2. Product Information: The schema includes fields for product details such as link, title, image, ID, and vendor.

3. Campaign and Brand Association: It associates each product with a specific campaign and brand using their ObjectId references.

4. Soft Delete: Includes an `is_deleted` field for soft deletion of products.

5. Timestamps: Automatically adds `createdAt` and `updatedAt` fields, storing Unix timestamps in seconds.

6. Model Creation: Creates a Mongoose model named "CampaignProducts" based on the defined schema.

7. Exports: The model is exported for use in other parts of the application.

This code serves as the data model for campaign products, allowing the application to interact with the database to create, read, update, and delete campaign product entries while maintaining associations with campaigns and brands.
