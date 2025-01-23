

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:12:34

This code file contains controller functions for a brand dashboard in a backend application. Its main purposes and key functionalities include:

1. Analytics and Metrics:
   - Fetching and calculating various analytics such as active campaigns, total revenue, and total spend.
   - Providing percentage changes compared to the previous month's data.

2. Top Performers:
   - Retrieving top creators based on their selling performance.
   - Fetching top-selling products.
   - Getting top-performing campaigns.
   - Listing top posts based on likes and views.

3. Chart Data:
   - Generating data for revenue charts.
   - Creating spend charts.
   - Producing charts for link creation.
   - Generating view count charts for posts.
   - Creating click charts for links.

4. Time-based Filtering:
   - Allowing data retrieval based on specified date ranges or defaulting to the current month.

5. Aggregation and Data Processing:
   - Using MongoDB aggregation pipelines to process and format data.
   - Joining data from multiple collections (e.g., transactions, campaigns, posts).

6. Error Handling:
   - Implementing try-catch blocks to handle errors and log them appropriately.

7. Response Formatting:
   - Structuring responses with consistent status codes and messages.

Overall, this controller file serves as the core of a brand's dashboard, providing comprehensive data and insights for brand performance analysis and decision-making.
