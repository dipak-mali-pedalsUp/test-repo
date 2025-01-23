

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:18:27

This code file, 'invoice.js', is part of a backend system that handles invoice generation and payout calculations for both brands and creators. Its main purposes are:

1. Generate invoices for brands on a monthly basis
2. Calculate payouts for creators based on their revenue and any returned orders

Key functionalities include:

1. generateBrandInvoiceCron(): This function generates monthly invoices for brands. It calculates total revenue and credit balance for each brand, then creates an invoice if one doesn't already exist for the current month.

2. generateCreatorPayoutCron(): This function calculates monthly payouts for creators. It considers the total revenue from orders, adjusts for any returned orders, and creates a payout record if one doesn't exist for the previous month.

3. Helper functions for calculations:
   - getTotalRevenue(): Calculates total revenue for a brand within a given date range.
   - getTotalCreditBalance(): Calculates total credit balance for a brand within a given date range.
   - getTotalCreatorRevenue(): Calculates total order amount and revenue for a creator within a given date range.
   - getTotalCreatorReturnedAmount(): Calculates total returned order amount and deducted amount for a creator within a given date range.

The code uses MongoDB aggregation pipelines for efficient data processing and calculation. It also employs Promise.all() for concurrent processing of multiple brands or creators, improving overall performance.
