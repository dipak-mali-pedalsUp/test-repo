

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:21:22

This code file contains utility functions for parsing URLs from popular video platforms. The main purpose of this module is to extract unique identifiers from URLs for YouTube, Twitch, and TikTok videos. Here's a breakdown of the key functionality:

1. youtube_parser:
   - Extracts the video ID from a YouTube URL
   - Uses a regular expression to match various YouTube URL formats
   - Returns the video ID as a string

2. twitch_parser:
   - Extracts the video ID from a Twitch video URL
   - Splits the URL by ".tv/videos/" and returns the second part as the video ID

3. tiktok_parser:
   - Extracts the video ID from a TikTok video URL
   - Uses a regular expression to match the video ID pattern
   - Returns the video ID as a string, or null if no match is found

These functions are likely used in a larger application to process and handle video links from different platforms, possibly for embedding, analyzing, or tracking purposes.
