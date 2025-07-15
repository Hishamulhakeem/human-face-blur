
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

Install dependencies:

```bash
pip install opencv-python mediapipe
