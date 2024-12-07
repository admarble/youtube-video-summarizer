# YouTube Video Summarizer

An application that transcribes, summarizes, and edits YouTube videos by removing unnecessary content.

## Implementation Steps

1. **Setup & Dependencies**
   - Create Python virtual environment
   - Install required packages (yt-dlp, youtube-transcript-api, moviepy, etc.)
   - Set up API keys (OpenAI/GPT for summarization)

2. **Video Processing**
   - Create video download functionality using yt-dlp
   - Extract audio from video
   - Implement URL validation and error handling

3. **Transcription**
   - Use youtube-transcript-api for captions if available
   - Implement fallback whisper-based transcription for videos without captions
   - Add timestamp preservation

4. **AI Processing**
   - Implement transcript cleaning/preprocessing
   - Create AI-based content summarization
   - Generate timestamped summary markers

5. **Video Editing**
   - Implement video cutting based on timestamps
   - Create video segment joining functionality
   - Add progress tracking

6. **Web Interface**
   - Create FastAPI/Flask backend
   - Build simple frontend for URL submission
   - Add video preview functionality
   - Implement download options

7. **Deployment**
   - Set up Docker configuration
   - Create deployment scripts
   - Add usage documentation

## Project Structure

```
./
├── app/
│   ├── api/            # API endpoints
│   ├── core/           # Core processing logic
│   ├── services/       # External services integration
│   └── utils/          # Helper functions
├── frontend/          # Web interface
├── tests/             # Test suite
└── docker/            # Docker configuration
```

## Requirements

- Python 3.8+
- FFmpeg
- OpenAI API key
- YouTube Data API key

## Usage

Detailed setup and usage instructions will be added as development progresses.