

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:08:51

This code file contains controllers for managing members in an admin panel. Its key functionalities include:

1. Adding new admin and super admin members:
   - Checks if the email already exists
   - Creates an admin user and a corresponding user in the database
   - Generates a random password and sends a welcome email with login credentials

2. Retrieving a list of managed members:
   - Implements pagination and sorting
   - Allows filtering by name
   - Aggregates data from multiple collections to get detailed user information
   - Includes information about who added each member

3. Changing a member's role:
   - Updates the user_type of a specified user

4. Sending welcome emails to new admin members:
   - Reads an HTML template
   - Replaces placeholders with actual data (email, username, password, login link)
   - Sends the email using a nodemailer utility

The code handles error logging and appropriate HTTP status responses for each operation. It also uses various utility functions and models from other parts of the application.
