<p align="center">
  <strong># Automated Video Transcription & Subtitle Generator</strong>
</p>

## Overview
This project automates the process of extracting audio from a video file, transcribing the audio, and generating subtitle files in the SRT format. It allows you to add the subtitles back to the video either as soft (selectable) or hard-coded subtitles.

## Features
- Extracts audio from a video file (`.mp4`).
- Transcribes the extracted audio using the Whisper model.
- Generates subtitles in the `.srt` format.
- Adds subtitles back to the original video either as soft subtitles.

## Depdendencies

### 1. Install FFMPEG

You can download FFMPEG [here](https://www.ffmpeg.org/download.html). Once you have the FFMPEG executable, place it in the same directory as main.py.

### 1. Install Python Dependencies

Make sure you have Python installed (this script was tested with **Python 3.12.3**). Install the required Python libraries using `requirements.txt`.

```bash
pip install -r requirements.txt
