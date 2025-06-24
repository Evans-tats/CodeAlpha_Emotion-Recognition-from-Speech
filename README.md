# CodeAlpha_Emotion-Recognition-from-Speech

Recognize human emotions (e.g., happy, angry, sad) from speech audio.

# Emotion Detection Using CNN on Ravdess Dataset

This project focuses on recognizing human emotions from speech using machine learning and deep learning techniques.

## 📌 Overview
This project implements a Convolutional Neural Network (CNN) to extract features and detect emotions from the RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) dataset. The model effectively classifies emotions from audio files, achieving high accuracy and performance.

## Features

- Preprocessing of audio files (e.g., noise removal, feature extraction)
- MFCC, ZCR, RMSE feature extraction
- CNN based feature Extraction
- Emotion classification and prediction
- Evaluation metrics (accuracy, confusion matrix)

## Tech Stack

- **Python**
- **Librosa** for audio processing
- **Scikit-learn** for classical ML models
- **TensorFlow / Keras** or **PyTorch** for deep learning
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn** for data handling and visualization

## Emotions Detected

- Anger
- Sadness
- Happiness
- Neutral
- Fear
- Surprise
- Disgust

## Dataset

The RAVDESS Dataset contains 24 professional actors (12 male, 12 female) vocalizing two lexically-matched statements in a neutral North American accent. The dataset includes:

- 8 Emotions: Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, Surprised
- Speech and Song modalities
- High-quality audio recordings

| Metric           | Value      |
| ---------------- | ---------- |
| Accuracy         | **88.26%** |
| Loss             | **0.3634** |
| Compiled Metrics | **87.67%** |


## Future Work
- Explore more complex models like LSTM or hybrid CNN-LSTM
- Extend to multi-modal emotion recognition (audio + video)
- Serve the trained model using FastAPI to provide a simple REST API for real-time emotion detection from audio files.
- Experiment with data augmentation for improved robustness
