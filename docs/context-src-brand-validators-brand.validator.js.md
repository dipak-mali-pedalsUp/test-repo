

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:16:33

This code file defines a set of validation rules for various brand-related operations in the Impression backend project. The main purpose of this code is to ensure data integrity and enforce proper input validation for different API endpoints related to brand management.

Key functionality:

1. It exports an object called `brandValidations` containing validation rules for different operations.

2. The validation rules are grouped by specific operations, such as "brand-register", "sendUserInvite", "updateProfile", "changeBrandAccountType", and "addstoredetails".

3. For each operation, it defines validation rules for various fields like brand_name, brand_website, email, name, is_private, plateform, access_token, and storebaseurl.

4. Common validation rules include:
   - trim: Removes whitespace from the beginning and end of strings
   - notEmpty: Ensures the field is not empty
   - isEmail: Validates that the input is a valid email address
   - isBoolean: Checks if the input is a boolean value

5. Each validation rule includes an errorMessage that will be displayed if the validation fails.

6. This validation schema can be used with a validation middleware (like express-validator) to automatically validate incoming requests for the corresponding API endpoints, ensuring that the data meets the specified criteria before processing it further.
