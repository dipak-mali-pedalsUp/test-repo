

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:08:21

This code file contains controller functions for managing brands and campaigns in an admin panel. Key functionalities include:

1. Managing brands:
   - Retrieving a list of brands with pagination and filtering options
   - Setting commission ratios for brands
   - Activating and deactivating brands
   - Setting default commissions for brands

2. Managing campaigns:
   - Retrieving all campaigns for a specific brand
   - Setting commission ratios for campaigns
   - Getting detailed analytics for campaigns

3. Analytics and reporting:
   - Generating revenue charts for campaigns
   - Generating spend charts for campaigns
   - Generating charts for link creation and clicks
   - Calculating and comparing analytics data between current and previous months

4. User management:
   - Sending invitation emails to brand users

The code interacts with various models (Brand, Campaign, TransactionOrder, MyLinks) to fetch and manipulate data. It also uses utility functions for common operations like pagination, date calculations, and email sending. The controller functions handle HTTP requests, process data, and return appropriate responses with status codes and messages.
