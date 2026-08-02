# Fork notice
This is a fork by me because the og forces ALSA Audio when not all systems use that. (like Bazzite) All credits go the og maker.

# Bad Apple For Terminal

This repository contains a set of scripts to convert the "Bad Apple" video into ASCII art representation and display it on terminal.
![Demo](media/demo.gif)
## Dependencies

- [FFmpeg (optional)](https://ffmpeg.org/): convert video to image frames.
- [Python](https://www.python.org/) (version 3.x) or bash.
- [Mpv](https://mpv.io/): A media player play audio background.
- [Ascii-image-converter (optional)](https://github.com/TheZoraiz/ascii-image-converter): convert image frame to text file.

## Usage

### 1. Clone this repo

```
git clone https://github.com/GoboVR/bad-apple-ascii-fixed-audio.git
```

### 2. CD into the folder

```
cd bad-apple-ascii-fixed-audio
```

### 3. Converting the Video to ASCII Text (optional)

To convert the "Bad Apple" video (`bad_apple.mp4`) into ASCII art and save it into `frames-ascii` folder, run the following command:

```bash
sh make-ascii.sh
```

### 4. Running the ASCII Art

#### Bash

```bash
sh run.sh
```

#### Python

```bash
python3 run.py
```

## Acknowledgments

Idea from [this video](https://www.youtube.com/watch?v=B49nQu4L2O4)
