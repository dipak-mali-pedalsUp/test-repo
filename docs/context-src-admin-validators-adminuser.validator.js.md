

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:10:28

This code file defines validation rules for admin user authentication, specifically for the login process. The main purpose and key functionality are:

1. It exports an object called `authValidations` containing validation rules.

2. The `login` property within `authValidations` defines the validation rules for the login process.

3. It specifies validation rules for two fields: `username` and `password`.

4. For the `username` field:
   - It should be trimmed of whitespace.
   - It cannot be empty.
   - If empty, it will return the error message "Please enter username."

5. For the `password` field:
   - It cannot be empty.
   - If empty, it will return the error message "Please enter password."

6. These validation rules can be imported and used in other parts of the application to ensure that admin login attempts meet the specified criteria before processing.

This code helps maintain data integrity and provides clear feedback to users when input requirements are not met during the admin login process.
