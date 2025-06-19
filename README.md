# deep-spectrogram-classifier
A pipeline for transforming .wav audio files into spectrogram images for classification using deep learning models like ViT, EfficientNet, and custom Transformers. The project includes audio preprocessing, spectrogram generation, and training of vision-based models to classify audio data using PyTorch.

# AudioSpectroClassify 🎧📊

Transform `.wav` audio files into spectrogram images and classify them using deep learning models such as Vision Transformers (ViT), EfficientNet, and a custom Transformer model.

---

## 🚀 Overview

This project converts raw audio files into spectrogram images and leverages powerful image classification models to analyze and classify the resulting visual representations. Spectrograms serve as an effective bridge between audio signals and visual deep learning techniques.

---

## 🧠 Features

- Converts `.wav` audio files to spectrogram `.png` images.
- Resizes images to (224x224) for model compatibility.
- Supports classification using:
  - Vision Transformer (ViT)
  - EfficientNet (B0)
  - Custom Transformer model
- Evaluation metrics: precision, recall, F1-score, and confusion matrix visualization.

---

## 🗂️ Folder Structure

