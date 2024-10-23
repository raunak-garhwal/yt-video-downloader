# YouTube Video Downloader

A tool to download YouTube videos using Python. This tool uses **FFmpeg** for video processing, so you'll need to install it before running the script.

## Prerequisites

1. **Python**: Make sure you have Python installed.
2. **FFmpeg**: Follow the instructions below to install FFmpeg.

## Installing FFmpeg

### For Windows:

1. **Download FFmpeg**:
   - Visit the official [FFmpeg website](https://ffmpeg.org/download.html).
   - Download the latest **static build** for Windows.

2. **Extract FFmpeg**:
   - Extract the downloaded `.zip` file to a folder of your choice, for example: `C:\ffmpeg`.

3. **Add FFmpeg to System Path**:
   - Open **Control Panel** → **System** → **Advanced system settings** → **Environment Variables**.
   - Under **System variables**, find the variable `Path` and click **Edit**.
   - Click **New** and add the path to the `bin` folder inside the extracted FFmpeg directory, e.g., `C:\ffmpeg\bin`.
   - Click **OK** to save and close the dialogs.

4. **Verify FFmpeg Installation**:
   - Open **Command Prompt** and type:
     ```bash
     ffmpeg -version
     ```
   - If installed correctly, you should see FFmpeg's version information.
