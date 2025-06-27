# Barinrot Video Creator

This project is designed to create videos from Reddit posts, overlay them with text-to-speech audio, and add subtitles. It uses various libraries and APIs to fetch Reddit posts, process video and audio, and generate the final output.

## Features

- Fetch posts from a specified subreddit.
- Download and cut videos from YouTube.
- Convert text from Reddit posts to speech.
- Overlay audio onto video clips.
- Generate and burn subtitles into videos.
- Adjust video speed and pitch.

## Requirements

To run this project, you need to have Python installed along with the following libraries:

- `praw`
- `yt-dlp`
- `moviepy`
- `gTTS`
- `whisper`
- `librosa`
- `soundfile`

You can install these libraries using pip:

```bash
pip install praw yt-dlp moviepy gTTS git+https://github.com/openai/whisper.git librosa soundfile
