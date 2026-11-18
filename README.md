# Facebook Album Bulk Images Downloader

A simple Python-based tool for downloading multiple images from Facebook albums in bulk using [gallery-dl](https://github.com/mikf/gallery-dl).

Instead of downloading photos one by one, this tool allows users to download available album images into a local folder.

## Features

- Bulk image downloading
- Download images from Facebook album URLs
- Custom download directory
- Simple command-line usage
- Skip already downloaded files where supported
- No Facebook account details hardcoded in the project
- No personal Page names, album IDs, or access tokens stored in the source code

## Requirements

- Windows 10 / Windows 11
- Python 3.8 or newer
- Internet connection
- gallery-dl

## Installation

**1. Install Python**

Download Python from:

https://www.python.org/downloads/

**2. Install gallery-dl**

Open Command Prompt and run:

```bash
python -m pip install -U gallery-dl
```

## Usage

**1. Test an album URL**

```bash
python -m gallery_dl --simulate "FACEBOOK_ALBUM_URL"
```

**2. Download album images**

```bash
python -m gallery_dl -D "Facebook_Photos" "FACEBOOK_ALBUM_URL"
```

Replace `FACEBOOK_ALBUM_URL` with the Facebook album URL you want to download.


IF not you can use this 

**3.Save to Desktop** 
```bash
python -m gallery_dl -D "C:\Users\YourName\Desktop\Facebook_Photos" "FACEBOOK_ALBUM_URL"
```
## Download Location

Downloaded images will be saved in the selected folder.

Example:

```text
Facebook_Photos/
├── image_001.jpg
├── image_002.jpg
├── image_003.jpg
└── image_004.jpg
```

## Important Notes

- Download access depends on Facebook's availability and access restrictions.
- Facebook extraction may require browser cookies for authentication.
- Public visibility does not guarantee anonymous downloading.
- Never share your Facebook password, access token, or session cookies.
- Respect copyright, privacy, and the original content owner's permissions.
- This project does not bypass Facebook privacy restrictions.

## Credits

This project uses [gallery-dl](https://github.com/mikf/gallery-dl), an open-source command-line image gallery downloader.

## Disclaimer

This project is an independent tool and is not affiliated with, endorsed by, or officially connected to Facebook or Meta Platforms, Inc.

Use this tool responsibly and only download content you have permission to save.
