


# GetTunes

GetTunes is a modern PyQt6 application for searching, listening to, and downloading YouTube videos as MP3 or MP4 files. It uses [yt-dlp](https://github.com/yt-dlp/yt-dlp) for extraction and download, and ffmpeg/ffplay for playback and conversion.

## Features

- Intuitive PyQt6 GUI
- Search YouTube directly from the app (top 5 results)
- Listen to audio before downloading
- Download audio (MP3) or video (MP4)
- Choose output directory (defaults to Music folder)
- Stop playback at any time

- Cancel downloads
- Real-time status and error messages
- Thread-safe UI updates

## Installation



1. Install Python dependencies:

  ```bash
  pip install -r requirements.txt
  ```

1. Install ffmpeg and ffplay (system dependencies):

  ```bash
  sudo apt-get install ffmpeg
  ```

## Usage



1. Run the app:

  ```bash
  python gettunes
  ```


1. Search for a song or paste a YouTube link.

1. Listen to audio, download audio/video, or stop playback as needed.

1. Choose your output directory or use the default Music folder.

## License

This project is licensed under the GNU GPL v3. See LICENSE for details.

## Future Improvements

- More yt-dlp options (quality, format)
- Edit output filename
- Progress bar
- Dark mode/theme support
- Custom app icon/logo
