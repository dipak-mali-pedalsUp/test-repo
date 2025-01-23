

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:09:26

This code defines a Mongoose schema and model for an "Invitation" in a MongoDB database. The key functionality includes:

1. Defining the structure of an invitation document with the following fields:
   - email: A string to store the invitee's email address
   - sender_id: A string to store the ID of the user sending the invitation
   - createdAt: A number representing the creation timestamp
   - updatedAt: A number representing the last update timestamp

2. Utilizing Mongoose's timestamp feature to automatically update the createdAt and updatedAt fields, using Unix timestamp (seconds since epoch) instead of the default Date object.

3. Creating a Mongoose model named "invitation" based on the defined schema, which can be used to interact with the invitation documents in the database.

4. Exporting the Invitation model for use in other parts of the application, allowing for CRUD operations on invitation data.

The purpose of this code is to provide a structured way to store and manage invitation data in the application, likely used for features such as user invitations or referral systems.
