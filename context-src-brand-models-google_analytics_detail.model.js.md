

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:14:22

This code defines a Mongoose schema and model for Google Analytics details associated with a brand. The main purposes and key functionalities of this code are:

1. Schema Definition:
   - It creates a schema (`gaAnalyticsSchema`) for storing Google Analytics details.
   - The schema includes fields for brand_id, properties, is_deleted flag, and timestamps.

2. Brand Association:
   - The `brand_id` field references the Brand model, establishing a relationship between Google Analytics details and a specific brand.

3. Required Fields:
   - Both `brand_id` and `properties` are marked as required fields, ensuring that these crucial pieces of information are always provided.

4. Soft Delete:
   - An `is_deleted` flag is included, allowing for soft deletion of records without permanently removing them from the database.

5. Timestamps:
   - The schema includes `createdAt` and `updatedAt` fields, which are automatically managed using the `timestamps` option.
   - Timestamps are stored as Unix timestamps (seconds since epoch) for consistency and ease of use.

6. Model Creation:
   - The schema is used to create a Mongoose model named "google_analytics_details".

7. Export:
   - The model is exported, making it available for use in other parts of the application for querying and manipulating Google Analytics detail data.

This code provides a structured way to store and manage Google Analytics information related to specific brands within a MongoDB database using Mongoose.
