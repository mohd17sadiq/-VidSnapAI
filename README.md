# VidSnapAI – AI-Powered Short Video Generator

VidSnapAI is a Python-based web application that helps users generate short-form videos by combining images, text descriptions, AI-generated voice narration, and video processing.

## Features

- Upload images for video creation
- Generate voice narration from text descriptions
- Text-to-Speech integration using ElevenLabs
- Automated video generation using FFmpeg
- Vertical-format video creation for short-form content
- Gallery for generated videos

## Tech Stack

- Python
- Flask
- ElevenLabs API
- FFmpeg
- HTML, CSS, JavaScript

## Workflow

1. Upload images through the web interface.
2. Provide text descriptions for narration.
3. Generate audio using the Text-to-Speech API.
4. Combine images and audio using FFmpeg.
5. Generate and view the final short video.

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/VidSnapAI.git
cd VidSnapAI

pip install -r requirements.txt
```

Configure your API key using environment variables before running the application.

## Environment Variables

Create a `.env` file:

```env
ELEVENLABS_API_KEY=your_api_key_here
```

Never commit your actual API keys to GitHub.

## Future Improvements

- AI-generated image captions
- Automatic subtitles
- Background music integration
- More video templates and customization options
