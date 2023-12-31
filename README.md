# Generate and ADD subtitles to the video without any Video Editor
auto-generate subtitles and add to video without any other video editor

## WSL GUI
Python GUI to easily generate and add subtitles to Video, you can also generate SRT file only 

![Sample](media/sample.gif)

## Output
auto subtitle added to video, 

![GIF](media/output.gif)


## Installation

```bash
# update the WSL to support GUI (only wsl2 supports gui)
wsl --update
# you need to restart WSL for the update to take effect
wsl --shutdown
```

To get started, you'll need Python 3.7 or newer. Clone the Repo and Install the binary by running the following command:

    pip install git+https://github.com/bilalahmed14/auto-subtitle.git

You'll also need to install [`ffmpeg`](https://ffmpeg.org/), which is available from most package managers:

```bash
# on Ubuntu or Debian
sudo apt update && sudo apt install ffmpeg

# on MacOS using Homebrew (https://brew.sh/)
brew install ffmpeg

# on Windows using Chocolatey (https://chocolatey.org/)
choco install ffmpeg
```

## Usage

The following command will run the GUI

```bash
    $python3 main.py
```



## License

This script is open-source and licensed under the MIT License. For more details, check the [LICENSE](LICENSE) file.
