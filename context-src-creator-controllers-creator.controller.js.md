

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:21:44

This code file contains a set of controller functions for managing creator-related operations in a backend application. The key functionalities include:

1. Creator Sign Up: Allows new creators to register, creates user credentials, and sends a welcome email with a password creation link.

2. Content Types and Social Media Platforms: Provides APIs to fetch lists of content types and social media platforms.

3. Payment Methods: Offers an API to retrieve available payment methods.

4. Creator Onboarding: Handles the onboarding process for creators, updating their profile information and creating a store for them.

5. Creator Profile Management: Includes functions to get and update creator profile details, including social media accounts and payment methods.

6. Account Deletion: Allows creators to delete their accounts (soft delete).

7. Waiting List Management: Provides functionality for creators to join a waiting list and check their waiting list status.

8. Username Management: Offers an API to retrieve all existing usernames to prevent duplicates.

The code interacts with various models (Partners, Users, SocialMediaPlatforms, PaymentMethods, etc.) and utilizes services for token generation, email sending, and logging. It also handles error cases and returns appropriate HTTP status codes and messages.
