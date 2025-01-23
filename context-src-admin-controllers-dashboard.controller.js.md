

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:08:42

This code file contains controller functions for an admin dashboard, focusing on retrieving and presenting various analytics and chart data. The key functionalities include:

1. getDashboardData: Fetches top brands, top-selling products, and top creators based on specified date ranges.

2. getLinksChart: Generates data for a chart showing the number of links created over the last 6 months.

3. getSpendChart: Creates chart data for spending trends over the last 6 months.

4. getRevenueChart: Produces chart data for revenue trends over the last 6 months.

5. getBrandRegistrationChart: Generates chart data for brand registrations over the last 6 months.

6. getCreatorRegistrationChart: Creates chart data for creator registrations over the last 6 months.

7. getCampaignsChart: Produces chart data for campaign creation trends over the last 6 months.

8. getPostsChart: Generates chart data for post creation trends over the last 6 months.

Each function aggregates data from various models (e.g., BrandModel, TransactionModel, PartnerModel) and formats it for easy consumption by the frontend. The code uses MongoDB aggregation pipelines for efficient data processing and includes error handling to manage potential issues during data retrieval.
