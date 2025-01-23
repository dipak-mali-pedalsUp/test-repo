

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:12:01

This code file contains a set of controller functions for handling analytics-related operations for a brand in an e-commerce or affiliate marketing system. The key functionalities include:

1. Retrieving campaign analytics:
   - getAllCampaigns: Fetches a list of campaigns with various metrics like total spend, revenue, ROI, and clicks.
   - getCampaignDetail: Retrieves detailed information about a specific campaign.

2. Insertion Order (IO) analytics:
   - getAllIO: Fetches a list of IOs with associated campaign data and metrics.
   - getIODetail: Retrieves detailed information about a specific IO.

3. Analytics charts:
   - getCampaignRevenueChart, getCampaignSpendChart: Generate revenue and spend data for campaigns over a 6-month period.
   - getIORevenueChart, getIOSpendChart: Generate revenue and spend data for IOs over a 6-month period.
   - getCampaignClickChart, getIOClickChart: Generate click data for campaigns and IOs over a 6-month period.
   - getIOLinksChart: Generate data on generated links for IOs over a 6-month period.

4. Analytics percentage calculations:
   - Functions like getCampaignAnalyticsPercentage, getIOAnalyticsPercentage, getCampaignDetailAnalyticsPercentage, and getIODetailAnalyticsPercentage calculate percentage changes in metrics like ROI, revenue, and spend between the current month and the previous month.

The code interacts with various models (Campaigns, Transactions, MyLinks, etc.) to fetch and process data. It also uses utility functions for common operations like pagination and date calculations. The controller functions handle request parameters, perform necessary data processing, and send formatted responses back to the client.
