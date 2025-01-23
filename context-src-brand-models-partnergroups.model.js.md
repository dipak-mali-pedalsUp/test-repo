

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:15:04

This code defines a Mongoose schema and model for partner groups in a brand management system. The key functionality includes:

1. Schema Definition:
   - Defines a schema called 'partnergroupsSchema' with fields for group_id, brand_partner_id, is_deleted, createdAt, and updatedAt.
   - The group_id and brand_partner_id fields are references to other collections (groupModel and brandPartnersModel respectively).

2. Relationships:
   - Establishes relationships between partner groups and other entities (groups and brand partners) using ObjectId references.

3. Soft Delete:
   - Includes an 'is_deleted' field to support soft deletion of records.

4. Timestamps:
   - Automatically manages createdAt and updatedAt timestamps, storing them as Unix timestamps (seconds since epoch).

5. Model Creation:
   - Creates a Mongoose model named 'PartnersGroup' based on the defined schema.

6. Export:
   - Exports the PartnersGroup model for use in other parts of the application.

The purpose of this code is to provide a structured way to store and manage relationships between partner groups and brand partners, allowing for efficient querying and data management in the brand management system.
