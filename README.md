# NETWORKDEMO1

# AI-Enhanced PHY Layer Demo 📡

This repository contains a concise demonstration of using Deep Learning to improve the Physical Layer (PHY) of a communication system.

## 🎯 What this Project Does
It demonstrates how a small Neural Network can act as a "smart filter" for BPSK signals.
1.  **Generates** a standard BPSK signal.
2.  **Adds** Gaussian Noise (simulating a wireless channel).
3.  **Uses** a TensorFlow model to predict the original signal from the noisy input.

## 📊 Results
The AI successfully reduces the Mean Squared Error (MSE) and visually separates the signal constellation better than raw reception.

## 🛠 Tools Used
*   Python 3.x
*   TensorFlow / Keras
*   Numpy (Signal Generation)
*   Matplotlib (Visualization)

## 🚀 How to Run
1.  Open the `AI_PHY_Demo.ipynb` file in this repository.
2.  Click the "Open in Colab" badge (if available) or download and run locally.
