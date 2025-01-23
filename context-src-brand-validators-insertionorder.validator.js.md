

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:16:49

This code defines validation rules for insertion orders in a backend system, likely for a brand or advertising management platform. The file 'insertionorder.validator.js' contains an object called 'insertionOrderValidations' with two main sections:

1. insertOrder: Defines validation rules for creating a new insertion order.
2. updateOrder: Defines validation rules for updating an existing insertion order.

Key functionality:

1. It ensures that required fields are not empty when creating or updating an insertion order.
2. It provides custom error messages for each field when validation fails.
3. The validation rules cover essential information such as name, description, order type, and order price.
4. Some fields are commented out, suggesting that they may be optional or handled differently in the current implementation.
5. The validation rules are exported as a module, likely to be used by other parts of the application for form validation or data integrity checks.

This validator helps maintain data consistency and provides user-friendly error messages when submitting or updating insertion orders in the system.
