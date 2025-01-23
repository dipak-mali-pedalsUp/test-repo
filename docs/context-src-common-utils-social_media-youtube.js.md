

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:21:16

This code file contains utility functions for interacting with the YouTube API. Its main purposes are:

1. To retrieve YouTube channel information and tokens:
   - The `getYouTubeChannelIdAndToken` function fetches a channel's name and profile image using a provided profile ID.
   - It uses the YouTube Data API v3 to get this information.

2. To fetch details about specific YouTube videos:
   - The `getYoutubeVideosDetail` function retrieves information about one or more YouTube videos using their video IDs.
   - It fetches snippet and statistics data for the videos.
   - The function also cleans up the response by removing unnecessary fields to reduce data size.

Key functionalities include:
- Making HTTP requests to the YouTube API using axios.
- Handling API responses and errors.
- Parsing and cleaning up API response data.
- Using environment variables for API key management.
- Logging errors for debugging purposes.

This module exports both functions, making them available for use in other parts of the application that need to interact with YouTube data.
