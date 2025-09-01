

# GetTunes

GetTunes is a modern Tkinter front-end for downloading and converting YouTube videos to MP3 using [yt-dlp](https://github.com/yt-dlp/yt-dlp) and ffmpeg.

## Features

- Simple, intuitive GUI (Tkinter)
- Paste a YouTube link and download as MP3
- Choose output directory
- Real-time status and error messages
- Uses yt-dlp (actively maintained)
- Requires ffmpeg for conversion

## Installation

1. Install dependencies:

  ```bash
  pip install -r requirements.txt
  sudo apt-get install ffmpeg
  ```

1. Run the script:

  ```bash
  python gettunes
  ```

## Usage

- Paste a YouTube link in the field
- (Optional) Choose where to save the MP3
- Click "Get Mp3" to download and convert

## License

This project is licensed under the GNU GPL v3. See LICENSE for details.

## Future Improvements

- More yt-dlp options (quality, format)
- Search YouTube from the app
- Edit output filename
- Progress bar
- Dark mode/theme support
