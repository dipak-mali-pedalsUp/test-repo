

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:12:22

This code file contains a set of controller functions for managing campaigns in a brand-focused application. The key functionalities include:

1. Creating campaigns: The `createCampaign` function allows brands to create new campaigns, including setting various parameters like start and end dates, budget, and associated products.

2. Saving campaigns as drafts: The `saveAsDraft` function allows brands to save incomplete campaigns for later editing.

3. Editing campaigns: The `editCampaign` function enables brands to modify existing campaigns.

4. Deleting campaigns: The `deleteCampaign` function allows brands to remove multiple campaigns at once.

5. Pausing and unpausing campaigns: The `pauseUnpauseCampaign` function toggles the active state of campaigns.

6. Changing campaign mode: The `changeCampaignMode` function updates the status of a campaign (e.g., from draft to live).

7. Retrieving campaign details: The `getCampaignDetail` function fetches detailed information about a specific campaign.

8. Listing campaigns: The `getCampaigns` function retrieves a paginated list of campaigns with optional filtering and searching capabilities.

9. Managing categories: The `getCategory` and `addCategory` functions allow for retrieving and adding campaign categories.

The code also includes error handling, logging, and integration with various models such as CampaignModel, BrandModel, and InsertionOrderModel. It uses MongoDB aggregation pipelines for complex data retrieval and manipulation.
