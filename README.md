# multimodal_bot
Creating a multimodal bot that identifies locations and gets geographic facts from images or text. You upload a photo (e.g., a landmark) or ask a question about a country, region, or destination. The bot returns clean, readable insights using Groq’s LLaMA model.

## Why It’s Useful
- Handles both image-based and text-based geographic queries
- Identifies landmarks and regions from photos
- Formats responses for clarity


## Tools Used
- Gradio (UI)
- Groq API (LLaMA 4 Scout model)
- PIL + base64 (image encoding)
- Python requests (API calls)

