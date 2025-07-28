# 🧠 Online Handwritten Mathematical Expression Recognition (HMER) using CNN and Bi-GRU Networks

This project presents a deep learning approach to **Online Handwritten Mathematical Expression Recognition (HMER)** using a hybrid model of **Convolutional Neural Networks (CNN)** and **Bidirectional Gated Recurrent Units (Bi-GRU)**. The goal is to accurately recognize complex handwritten math expressions in real time.

---

## 📌 Project Highlights

- **Objective**: Recognize handwritten mathematical expressions from online inputs (images or stroke data).
- **Architecture**:
  - **CNN Layers** for spatial feature extraction.
  - **Bi-GRU Layers** for sequence modeling in both forward and backward directions.
  - **CTC Loss** to handle sequence alignment without pre-segmented data.
- **Use Cases**:
  - Digital note-taking and mathematical OCR.
  - Education-based apps and smart classroom tools.
  - Accessibility tools for converting handwritten math into LaTeX or readable text.

---

## 🏗️ Model Overview

- **Input**: Grayscale preprocessed images of handwritten math expressions.
- **Feature Extractor**: CNN with multiple convolutional and pooling layers.
- **Sequence Learner**: Bi-GRU for contextual understanding of symbol sequence.
- **Decoder**: Connectionist Temporal Classification (CTC) for flexible prediction without alignment.

---

## 🔧 Tech Stack

- **Language**: Python
- **Libraries**: TensorFlow / Keras, NumPy, OpenCV
- **Tools**: Jupyter Notebook / Google Colab


