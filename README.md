
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YogeshxSaini/YouTube-to-Google-Drive-Uploader/blob/main/YouTube_to_Drive.ipynb)

# YouTube to Google Drive Uploader

Easily download YouTube videos and upload them directly to your Google Drive using this Google Colab notebook.

## Features

## Getting Started (Google Colab)
1. **Open in Google Colab:**
   - Go to [Google Colab](https://colab.research.google.com/).
   - Upload or open `YouTube_to_Drive.ipynb` from this repository.
2. **Run the notebook cells in order:**
   - The notebook will automatically install required packages (`yt-dlp`, `ffmpeg`) using Colab commands.
   - It will mount your Google Drive for saving downloaded videos.
   - Paste your YouTube video URL when prompted.
   - Select your desired video resolution and let the notebook handle the rest!

**Note:** This notebook uses Colab-only features:
- `from google.colab import drive` for mounting Google Drive
- Shell commands like `!pip install` and `!apt-get install`
- File paths such as `/content/drive/MyDrive/`
It will not work as-is in standard Jupyter environments.

## Requirements
- Google Colab (recommended)
- Google account for Drive access

## License
This project is provided as-is for educational purposes.

## Author
[Yogesh Saini](https://github.com/YogeshxSaini)
