
# HumanVision - Face Blurring Tool using MediaPipe

This project detects faces in images, videos, or webcam streams and applies a blur to each detected face using [MediaPipe](https://google.github.io/mediapipe/) and [OpenCV](https://opencv.org/).

## 🚀 Features

- Face detection using MediaPipe
- Blur applied to detected faces
- Supports:
  - Images (`--mode image`)
  - Videos (`--mode video`)
  - Real-time webcam (`--mode webcam`)

## 🛠️ Requirements

- Python 3.x
- OpenCV
- MediaPipe

## 📁 Project Structure
.
├── HumanVision2.py       # Main script

└── output                # Output directory (auto-created)

└──requirements.txt       # to install libraries that are needed for this project


## 📷 Usage


-Blur face in an image
    -python HumanVision2.py --mode image --filePath path/to/image.jpg
-Blur face in a video
    -python HumanVision2.py --mode video --filePath path/to/video.mp4
-Blur face from webcam (default)
    -python HumanVision2.py


Install dependencies:

```bash
pip install opencv-python mediapipe

    
