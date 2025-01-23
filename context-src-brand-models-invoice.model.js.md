

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:14:49

This code defines a Mongoose schema and model for an Invoice in a Node.js application. The purpose of this file is to create a structured representation of invoice data in the MongoDB database. Key functionalities include:

1. Schema Definition: It defines an invoiceSchema with various fields such as payable_amount, actual_amount, type, forUser, brand_id, partner_id, and others. These fields represent different attributes of an invoice.

2. Field Types and Validation: Each field in the schema is defined with a specific data type (e.g., Number, String, Boolean) and may include additional properties like default values and required flags.

3. Enum Values: The 'type' and 'forUser' fields use enum to restrict the possible values, ensuring data consistency.

4. References: The schema includes references to other models (brand and partner) using mongoose.Schema.Types.ObjectId, allowing for relational data structure.

5. Timestamps: The schema is configured to automatically add createdAt and updatedAt timestamps, stored as Unix timestamps in seconds.

6. Model Creation: The schema is used to create a Mongoose model named "Invoice", which can be used to interact with the 'invoice' collection in the MongoDB database.

7. Export: The Invoice model is exported, making it available for use in other parts of the application for CRUD operations on invoice data.

This code serves as the data model for invoices in the application, providing a structured way to store, retrieve, and manipulate invoice-related information in the database.
