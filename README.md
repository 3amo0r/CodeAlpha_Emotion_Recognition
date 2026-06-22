# CodeAlpha_Emotion_Recognition

This project is the second task of my Machine Learning internship at **CodeAlpha**. It focuses on **Speech Emotion Recognition (SER)** using Deep Learning techniques.

## Project Overview
- **Objective:** Classify human emotions (e.g., Happy, Angry, Sad) from speech audio files.
- **Data:** Used the [RAVDESS Dataset](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio).
- **Key Techniques:**
    - Audio signal processing using `librosa`.
    - Feature extraction: **Mel-Spectrograms**.
    - Model: **Convolutional Neural Network (CNN)** built with TensorFlow/Keras.
- **Performance:** Achieved ~78% accuracy on the test set.

## How to run
1. Install requirements: `pip install -r requirements.txt`
2. Ensure the RAVDESS dataset is in the correct directory.
3. Run the `Emotion_Recognition_CNN.ipynb` notebook to train and evaluate the model.
