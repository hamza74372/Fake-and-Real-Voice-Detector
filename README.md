# Fake-and-Real-Voice-Detector
A robust AI system that distinguishes between human speech and AI-generated (Deepfake) or replayed audio. Built with TensorFlow and Librosa, achieving 96% accuracy on the ASVspoof 2019 dataset

# 🎙️ Fake and Real Voice Detector (CNN)

This project is an AI-powered security system designed to detect **Voice Deepfakes** and **Replay Attacks**. It uses Deep Learning to analyze the frequency patterns of audio to determine if a voice is human (Bonafide) or AI-generated/Spoofed.

## 🚀 Overview
* **Model:** Convolutional Neural Network (CNN)
* **Dataset:** ASVspoof 2019 (LA & PA)
* **Input:** 2D Mel-Spectrograms (128x94)
* **Accuracy:** ~96%

## 📂 Project Content
* `Voice_Deepfake_Detection.ipynb`: The complete pipeline from data extraction to model training.
* `Voice_Data_1D_Readable.csv`: Extracted MFCC features for baseline testing.

## 🛠️ How to Use
1. Open the `.ipynb` file in **Google Colab**.
2. Enable **GPU** (Runtime > Change runtime type > T4 GPU).
3. Run the cells to download the dataset and train the model.
4. Use the "Real-Time Prediction" cell to upload your own `.wav` files.

## 📊 Results
The model achieves high precision by identifying synthetic artifacts in the high-frequency range that are typically absent in natural human speech.
