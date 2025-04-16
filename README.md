# Violence Detection in Videos

This project uses a deep learning model to automatically detect violence in video files. The model is implemented using TensorFlow and processes video frames to classify whether a video contains violent content.

## Project Overview

The notebook performs the following tasks:
- Installs and configures required dependencies.
- Loads a trained deep learning model (likely based on MobileNetV2 or a custom CNN).
- Processes input video files by extracting frames.
- Makes predictions on the presence of violence using the trained model.
- Displays the result (violent or non-violent) to the user.

## Requirements

The project uses the following main packages:
- `tensorflow==2.15.0`
- `telepot` (for optional bot integration)
- `numpy`
- `opencv-python`
- `ml-dtypes`, `tensorflow-text`, `jax`, `grpcio-status`

> **Note:** Some uninstall commands are included to ensure compatibility, especially for TensorFlow and Keras versions.

## How to Run

1. Open the notebook: `violenceprediction.ipynb`
2. Ensure your Python environment has access to the internet for dependency installation.
3. Upload the video file you want to test.
4. Run all cells sequentially.
5. The notebook will output whether the video contains violence or not.

## Model Information

- The model is likely trained on a labeled dataset of violent vs non-violent video clips.
- The input frames are resized and normalized before prediction.
- The output is a binary classification.

## Notes

- If using `telepot`, ensure you set up a Telegram bot token.
- Model accuracy depends on training data quality and preprocessing consistency.

---

