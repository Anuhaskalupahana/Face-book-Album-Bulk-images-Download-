<div align="center">
Facebook Album Bulk Image Downloader
A simple Python tool to download available photos from a Facebook album.
<p>
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Tool-gallery--dl-green" alt="gallery-dl" />
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey" alt="Platforms" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="MIT License" />
</p>
</div>
---
📌 Topic
Facebook Album Bulk Image Downloader using Python
📝 Description
Facebook Album Bulk Image Downloader is a small Python project that helps users download the photos that are available from a Facebook album. It uses `gallery-dl` to handle the download process.
The script asks for a Facebook album URL, checks that it is a Facebook link, asks for confirmation, and then starts downloading the available images into a folder on your computer.
> **Important:** A public album is not guaranteed to be downloadable without logging in. Facebook may block automated or anonymous access. This project does not bypass Facebook login, privacy settings, or access restrictions.
✨ Features
Download multiple available images from a Facebook album.
Simple command-line interface.
Checks that the supplied URL belongs to Facebook.
Lets you choose an output folder.
Uses `gallery-dl` for downloading.
Works on Windows, Linux, and macOS where Python and `gallery-dl` are supported.
🧰 Requirements
Python 3.8 or newer
Internet connection
`gallery-dl` Python package
A Facebook album URL that you are allowed to access
🚀 Step-by-Step Installation and Usage
Step 1 – Download the project
Open this GitHub repository.
Click Code.
Select Download ZIP.
Extract the downloaded ZIP file to a folder on your computer.
Alternatively, clone the repository using Git:
```bash
git clone https://github.com/anuhas443/Face-book-Album-Bulk-images-Download-.git
```
Step 2 – Check Python
Open Command Prompt (Windows) or a terminal (Linux/macOS), and run:
```bash
python --version
```
On Windows, you can also use:
```bash
py --version
```
If Python is not installed, download it from python.org.
Step 3 – Open the project folder
Open the extracted project folder. In that folder, open a terminal or Command Prompt.
Step 4 – Install the required package
Run:
```bash
py -m pip install -r requirements.txt
```
If the `py` command is not available, try:
```bash
python -m pip install -r requirements.txt
```
Step 5 – Start the downloader
Run the Python script:
```bash
py fb_album_downloader.py
```
If you use `python` instead of `py`, run:
```bash
python fb_album_downloader.py
```
Step 6 – Enter the Facebook album URL
When the program asks, paste the Facebook album URL and press Enter.
The program displays the URL and output folder, then asks for confirmation. Type `y` and press Enter to continue, or type `n` to cancel.
Step 7 – Find your downloaded images
By default, downloaded images are saved in a folder named:
```text
Facebook_Photos
```
The folder is created inside the current project directory if it does not already exist.
⚙️ Optional: Choose an output folder
You can provide the album URL and output folder directly:
```bash
py fb_album_downloader.py "https://www.facebook.com/your-album-link" --output "My_Facebook_Photos"
```
Replace the example URL with the album URL you are allowed to access. You can also use `-o` instead of `--output`.
🗂️ Project Structure
```text
Facebook-Album-Bulk-images-Download/
│
├── fb_album_downloader.py   # Main Python downloader script
├── requirements.txt         # Required Python packages
├── README.md                # Project documentation
├── LICENSE                  # MIT License
└── .gitignore               # Git ignore rules
```
🛠️ Technologies Used
<p align="left">
  <a href="https://www.python.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="42" height="42" />
  </a>
  <a href="https://github.com/mikf/gallery-dl" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/gallery--dl-downloader-2ea44f?style=for-the-badge" alt="gallery-dl" />
  </a>
</p>
Python – runs the downloader script.
gallery-dl – handles the album image download process.
🧩 Troubleshooting
1. `py` or `python` command is not recognised
Check that Python is installed and added to your system PATH. On Windows, try the `py` command.
2. `gallery-dl` is not installed
Install the requirements again:
```bash
py -m pip install -r requirements.txt
```
3. Facebook blocks the download or asks you to log in
Some albums cannot be downloaded anonymously. The script cannot bypass Facebook authentication, privacy controls, or other access restrictions. Only use content you have permission to download.
4. No images are downloaded
Check that the album URL is correct and that you can open the album in your browser. The album may not be supported for anonymous downloading.
⚠️ Disclaimer
This project is provided for educational and personal use. Download only photos that you own or have permission to download. Respect the rights, privacy, and terms of service of Facebook and the content owners. This project is not affiliated with or endorsed by Meta or Facebook.
📄 License
This project is licensed under the MIT License.
---
<div align="center">
  <b>Made with Python</b>
  <br />
  If you find this project useful, consider giving the repository a ⭐.
</div>
