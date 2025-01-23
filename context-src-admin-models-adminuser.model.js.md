

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:09:19

This code defines a Mongoose schema and model for an admin user in a backend application. Here's a summary of its purpose and key functionality:

1. Purpose:
   - To create a structured data model for admin users in a MongoDB database using Mongoose.
   - To define the properties and data types of an admin user object.

2. Key Functionality:
   - Defines an AdminUser schema with the following fields:
     - firstname and lastname (String, optional)
     - email (String, required, converted to lowercase)
     - profile (String, optional)
     - added_by (ObjectId, optional, likely referencing another user)
     - is_reset_password_required (Boolean, optional)
     - is_deleted (Boolean, default: false)
     - createdAt and updatedAt (Number, automatically managed)
   - Uses timestamps option to automatically update createdAt and updatedAt fields
   - Converts timestamps to Unix timestamp (seconds since epoch)
   - Creates a Mongoose model named "admin_user" based on the defined schema
   - Exports the AdminUser model for use in other parts of the application

This model can be used to create, read, update, and delete admin user documents in the MongoDB database, ensuring consistent data structure and types for admin user information.
