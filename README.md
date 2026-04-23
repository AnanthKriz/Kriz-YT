🚀 KRIZ YT

⚡ Fast, lightweight YouTube video & audio downloader powered by Python

📌 Overview

KRIZ YT is a powerful and easy-to-use YouTube downloader built with Python.
It allows users to download videos, playlists, and extract audio in high quality directly from the terminal.

Designed for speed, simplicity, and automation.

✨ Features
🎥 Download YouTube videos in multiple resolutions
🎵 Extract high-quality audio (MP3)
📂 Playlist support
⚡ Fast and lightweight
🖥️ CLI-based (simple commands)
🔧 Easy integration into bots / automation scripts
🛠️ Tech Stack
Python 3
yt-dlp / youtube-dl backend
FFmpeg (for audio/video processing)
📦 Installation
1️⃣ Clone the repository
git clone https://github.com/AnanthKriz/ytdl-py.git
cd ytdl-py
2️⃣ Create virtual environment (recommended)
python -m venv venv

Activate it:

Windows

venv\Scripts\activate

Linux / Mac

source venv/bin/activate
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Install FFmpeg (Required)

Download and install FFmpeg:

Windows → https://ffmpeg.org/download.html
Linux:
sudo apt install ffmpeg
▶️ Usage
Download a video
python ytdl.py <video_url>
Download audio only (MP3)
python ytdl.py <video_url> --audio
Download playlist
python ytdl.py <playlist_url> --playlist
⚙️ Example
python ytdl.py https://youtube.com/watch?v=example
📁 Project Structure
ytdl-py/
│── ytdl.py           # Main script
│── requirements.txt  # Dependencies
│── README.md
🧪 Development Setup
pip install -e .

Run:

python ytdl.py
🛡️ Disclaimer

This project is for educational purposes only.
Downloading copyrighted content without permission may violate YouTube's terms of service.

🤝 Contributing

Pull requests are welcome!

Fork the repo
Create a new branch
Commit your changes
Open a PR
📄 License

MIT License

👨‍💻 Author

KRIZ BOT INC.
GitHub: https://github.com/AnanthKriz

⭐ Support

If you like this project, give it a ⭐ on GitHub!
