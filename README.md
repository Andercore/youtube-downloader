<p align="center">
  <img src="https://raw.githubusercontent.com/Andercore/youtube-downloader/main/docs/logo.svg" alt="YouTube Downloader logo" width="160">
</p>

# 🎬 YouTube Downloader

I created YouTube Downloader as a Windows executable and distribute it through
the [Releases](../../releases) page.

YouTube Downloader is a menu-driven utility for downloading video and audio
from YouTube links. It uses `yt-dlp` for downloads and `FFmpeg` for media
processing and format conversion.

> ⚠️ **Disclaimer:** I provide this project **as-is**. I wrote the original
> code, but I am not responsible for account actions, copyright violations,
> data loss, damage, or any other consequence resulting from its use. Use it
> only for content you are legally allowed to download and at your own risk.

## ✅ Requirements

- 🪟 Windows
- 🔗 A YouTube video URL
- 📦 The `.exe` file downloaded from a release of this repository

The application checks for the required tools and downloads them when they are
missing. The `tools` directory may contain `yt-dlp`, `FFmpeg`, and their
supporting files after the first run.

## 🚀 How to use

### 1️⃣ Download the application

1. Open the [latest release](../../releases/latest).
2. Download the executable asset attached to that release.
3. Save it in a folder where the application can create its `tools` and output
   files.

🔒 Please download executable files only from releases published in this
repository. Windows or antivirus software may show a warning for unsigned
files, so review the release information before deciding whether to continue.

### 2️⃣ Choose an operation

Run the executable and select one of the available menu options:

- **Download Video** — save a YouTube video as a supported video file.
- **Download Audio** — extract audio in a supported audio format.
- **Update Tools** — update the bundled download and media-processing tools.
- **Exit** — close the application.

Paste the YouTube URL when requested and follow the progress shown in the
console window. Downloaded files are saved according to the application's
current output configuration.

## 🧰 Tools

This project relies on third-party tools maintained by their respective
authors:

- [yt-dlp](https://github.com/yt-dlp/yt-dlp) for retrieving media
- [FFmpeg](https://ffmpeg.org/) for processing and converting media

Their licenses and terms remain applicable to the files distributed with the
application.

## 📦 Releases

I distribute executable files only through GitHub Releases. I do not commit
prebuilt binaries or downloaded third-party tools to the main branch.

## 🚫 No modification or support promise

I publish the source code and release files for this project only. Please do
not modify, repackage, redistribute, or claim authorship of them. I do not
provide a warranty, maintenance commitment, or support promise.

## 📄 License

All rights reserved. See [LICENSE](LICENSE).
