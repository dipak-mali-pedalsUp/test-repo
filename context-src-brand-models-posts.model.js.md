

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:15:13

This code defines a Mongoose schema and model for posts in a social media management system. The main purpose and key functionalities are:

1. Schema Definition: It creates a schema for posts with various fields such as post_id, post_url, post_title, post_description, total_likes, total_views, etc.

2. Relationships: The schema establishes relationships with other models:
   - brand_id links to the brand model
   - partner_id links to the partner model
   - social_media_platform_id links to the social media platforms model

3. Timestamps: It includes automatic timestamp fields (createdAt and updatedAt) using Unix timestamps.

4. Default Values: Many fields have default values, mostly set to null or 0.

5. Soft Delete: The schema includes an is_deleted field, allowing for soft deletion of posts.

6. Model Creation: It creates a Mongoose model named "Post" based on the defined schema.

7. Export: The model is exported for use in other parts of the application.

This code serves as the data model for posts, providing a structured way to store and manage post-related information in the database, including metadata and relationships to brands, partners, and social media platforms.
