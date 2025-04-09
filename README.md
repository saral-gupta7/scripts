# 📜 Overview of My Scripts

## 🎧 1. `audio`

> _"I named it `audio` because it originally just downloaded audio… and I was too lazy to rename it later. 😂"_

This script is a lightweight, fun CLI tool that uses `yt-dlp` under the hood to download audio (and optionally video) from YouTube links. It also includes a slick menu powered by `fzf` for an interactive experience.

---

### 🛠 Dependencies

Before using the script, make sure you have these installed:

- **yt-dlp** – Used for downloading and converting YouTube content.  
  Install via pip:
  ```bash
  pip install yt-dlp
  ```
- **fzf** – A fuzzy finder used to create a dropdown-style selection menu.
  If you’re on macOS, install with:
  ```bash
  brew install fzf
  ```
- Or use the package manager appropriate for your OS.

#### 🚀 How to Use the Script

Once dependencies are installed:

1. Run the script.
2. Select whether you want to download Audio or Video using the dropdown.
3. Enter the output file name.
4. Paste the YouTube URL. 
5. Sit back and let the magic happen. 🪄
