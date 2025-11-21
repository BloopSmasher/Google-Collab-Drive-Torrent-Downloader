# Google Collab Drive Torrent Downloader
Download torrents at high speed directly to google drive using google high speed servers.  This notebook uses aria2 as a downloader.

**Disclaimer**: Downloading copyrighted materials without permission is illegal. This project is intended for educational purposes only. Please ensure you have the necessary rights to download any torrent files you use.

# Usage 

### 🔧 Cell 1 - Install Dependencies / Preparation

Cell 1 install all dependencies and prepare the environment.
This will automatically:

🔗 Mount your Google Drive to Google Colab
📁 Create a directory named CollabTorrents in your Drive root
⬇️ Download and install the Aria2 downloader


### 🔧 Cell 2 — Download Torrent through Mangent Link

In Cell 2, enter the magnet link of the torrent you want to download.
Then simply wait for the download to complete.

### Notes:

❌ Ignore this error if encountered (Not Fatal)
> [ERROR] IPv6 BitTorrent: failed to bind TCP port 6903  
> Exception: [SocketCore.cc:312] errorCode=1 Failed to bind a socket, cause: Name or service not known



❌ This will not seed the torrent
