

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:14:05

This code defines a Mongoose schema and model for a "Campaign Target" in a MongoDB database. The purpose of this model is to represent and manage campaign target data for a brand or marketing system. Key functionalities include:

1. Schema Definition:
   - Defines the structure for campaign target documents with fields such as partners_type, commision_percentage, campaign_id, is_deleted, createdAt, and updatedAt.
   - Uses Mongoose's Schema constructor to create the schema.

2. Field Types and Validations:
   - partners_type: A required String field (commented code suggests it might have been an ObjectId reference previously).
   - commision_percentage: A required Number field with a default value of 10.
   - campaign_id: A required ObjectId field referencing the Campaign model.
   - is_deleted: A Boolean field with a default value of false.
   - createdAt and updatedAt: Number fields for timestamp tracking.

3. Timestamps:
   - Automatically manages createdAt and updatedAt fields using Unix timestamp (seconds since epoch).

4. Model Creation:
   - Creates a Mongoose model named "campaign_target" based on the defined schema.

5. Relationship:
   - Establishes a relationship with the Campaign model through the campaign_id field.

This model can be used to create, read, update, and delete campaign target documents in the MongoDB database, providing a structured way to manage campaign targeting information within the application.
