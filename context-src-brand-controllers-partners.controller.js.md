

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:13:05

This code file contains controllers for managing partners in a brand-related application. The key functionalities include:

1. Approving or disapproving partner follow requests
2. Retrieving a list of brand partners with various filtering options
3. Fetching individual partner details
4. Blacklisting or whitelisting partners
5. Managing partner groups
6. Adding partners to groups
7. Retrieving partner counts based on different criteria (all, active, loyal, requests, blacklisted)

The code interacts with multiple MongoDB collections (Partners, BrandPartners, Users, Groups, PartnerGroups, PartnerSocialMedia, SocialMediaPlatform, MyLinks, Posts) to fetch and manipulate data.

Key features include:
- Pagination support for partner lists
- Filtering partners based on various criteria (e.g., active, loyal, blacklisted)
- Searching partners by name
- Filtering partners by social media platform
- Calculating total clicks and views for partners
- Managing partner groups and their associations

The code also includes error handling and logging for better debugging and maintenance.
