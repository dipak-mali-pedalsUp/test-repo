

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:12:55

This code file contains controller functions for managing partner groups in a brand management system. Its main purposes and key functionalities include:

1. Managing partners and partner groups for brands
2. Creating, updating, and deleting partner groups
3. Retrieving lists of partners and partner groups
4. Filtering and sorting partners based on various criteria

Key functionalities:

1. getPartnersList: Retrieves a list of brand partners with detailed information, including social media profiles and performance metrics.

2. createPartnersGroup: Creates a new partner group and assigns partners to it.

3. deletePartnersGroup: Deletes a partner group, considering any active campaigns using the group.

4. getPartnerGroups: Retrieves a paginated list of partner groups with details about the partners in each group.

5. updatePartnersGroup: Updates a partner group's name and its associated partners.

6. getPartnerGroupDetails: Retrieves detailed information about a specific partner group.

7. getPartnerListByGroupId: Retrieves a list of partners belonging to a specific group, with options for filtering and sorting.

The code uses MongoDB aggregation pipelines to fetch and process complex data structures, including related information from multiple collections. It also implements error handling and logging for better debugging and maintenance.
