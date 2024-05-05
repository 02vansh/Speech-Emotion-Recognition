# Speech-Emotion-Recognition
# Overview:
This project focuses on speech emotion recognition using deep learning techniques, specifically Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) models. The RAVDESS speech dataset was utilized for training and testing the models. Additionally, a Graphical User Interface (GUI) was developed to enable users to input audio files and receive predicted emotions.
# Dataset:
RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song): This dataset contains speech samples with various emotions such as calm, angry, happy, etc.
# Model Architecture:
CNN and LSTM models were employed for learning features from the audio samples.

CNN layers extract spatial features from spectrograms of audio signals.

LSTM layers capture temporal dependencies in the audio sequences.
# GUI Development:
A Graphical User Interface (GUI) was developed using a suitable framework (e.g., Tkinter).

The GUI allows users to upload audio files for emotion prediction.

Upon selecting an audio file, the model predicts the emotion (e.g., calm, angry, happy) and displays the result on the interface.
# Dependencies:
Python 3.x

TensorFlow

Keras

NumPy

Librosa (for audio processing)

Tkinter (for GUI)
# Conclusion:
This project demonstrates the effectiveness of CNN and LSTM models in recognizing emotions from speech audio. The developed GUI enhances user accessibility, allowing for easy input and interpretation of emotion predictions.
