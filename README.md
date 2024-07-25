# Chunking
Chunking the audio file to usable size, says 25 MB.

# Audio Chunking with Pydub

This repository contains a Jupyter notebook for chunking audio files using the Pydub library in Python. The script allows you to split an audio file into multiple parts and save them as MP3 files.

## Features

- **Input Format**: The script currently supports `.m4a` audio files.
- **Output Format**: The output audio chunks are saved as `.mp3` files.
- **Customizable Splits**: You can specify the number of parts to split the audio file into.
- **Timestamped Output**: Each output file is named with a timestamp to avoid overwriting.

## Requirements

- Python 3.x
- Pydub
- ffmpeg or libav

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name

