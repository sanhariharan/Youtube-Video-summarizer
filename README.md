# Youtube-Video-Summarizer

This project is a YouTube Video Summarizer powered by Gemini AI. It extracts transcripts from YouTube videos and provides a meaningful, structured summary including:

1. A brief introduction to the topic
2. Current facts and happenings related to the topic
3. Advantages and disadvantages discussed in the video
4. Additional links related to the video

## Features
- Paste a YouTube link to get a summary
- Uses Google Gemini AI for content generation
- Fetches video transcripts automatically
- Simple Streamlit web interface

## Setup Instructions

1. **Clone the repository**
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your environment variables in a `.env` file (e.g., Gemini API key)
4. Run the app:
   ```bash
   streamlit run app.py
   ```

## Requirements
See `requirements.txt` for all dependencies.

## Usage
- Open the app in your browser
- Paste a YouTube video link
- Click 'Summarize' to get the summary

## Example
![App Screenshot](http://img.youtube.com/vi/VIDEO_ID/0.jpg)

## License
MIT
