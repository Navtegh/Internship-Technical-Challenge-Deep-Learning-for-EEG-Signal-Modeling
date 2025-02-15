# EEG Signal Classification

This repository contains the implementation and evaluation of different deep learning models for **EEG signal classification**. The models tested include **EEGNet, CNN, CNN-GRU, LSTM, and Transformer-based architectures**.

## 📌 **Project Overview**
The goal of this project is to classify EEG signals using different deep learning architectures and analyze their performance in terms of accuracy, computational efficiency, and generalization across subjects.

## 🚀 **Models Implemented**
- **EEGNet** (Lightweight CNN for EEG classification)
- **CNN** (Convolutional Neural Network)
- **CNN + GRU** (Hybrid model combining CNN and Gated Recurrent Unit)
- **LSTM** (Long Short-Term Memory Network)
- **Transformer** (Self-attention based model for sequence learning)

## 🛠 **Preprocessing Techniques**
- **Filtering**: High Pass filter to remove drifts.
- **Normalization**: Standardization of EEG signal amplitudes.
- **Epoching**: Splitting EEG signals into time windows for classification.

## ⚡ **Key Findings**
- **EEGNet is the best model overall**, achieving high accuracy with minimal computational cost.
- **Transformer models generalize well** across subjects but require **significantly more computation** (640s training time, 1.1GB memory).
- **CNN performs well but is slightly less efficient than EEGNet.**
- **LSTM and CNN-GRU struggle with cross-subject generalization.**
## Author
Navtegh Singh Gill
