# Online-HMER-Using-CNN-and-Bi-GRU-Networks

This project focuses on solving the challenging task of recognizing handwritten mathematical expressions in an online setting (i.e., input received as pen stroke sequences or image inputs), using a deep learning pipeline combining Convolutional Neural Networks (CNN) for spatial feature extraction and Bidirectional Gated Recurrent Units (Bi-GRU) for sequential modeling.

📌 Project Highlights
🧮 Objective: Recognize complex handwritten mathematical expressions from online input using deep learning.

🧠 Architecture:

CNN Layers: Extract meaningful spatial features from input images.

Bi-GRU Layers: Capture contextual dependencies in both forward and backward directions for better sequence modeling.

CTC Loss: Handles variable-length sequences without explicit alignment between input and output.

📊 Dataset: Trained on benchmark datasets such as CROHME 2014.

💡 Use Cases:

Educational tools for math learning apps.

Digital note-taking software.

Math OCR for scanned handwritten content.


🏗️ Model Overview
Input: Preprocessed grayscale images of handwritten math expressions.

CNN Block: Series of convolutional layers to extract low- to high-level features.

Bi-GRU Block: Models temporal dependencies for character/structure decoding.

CTC Layer: Enables the model to learn without needing pre-segmented data.


🔧 Tech Stack
Language: Python

Libraries: TensorFlow / Keras, NumPy, Pandas, Matplotlib, OpenCV

Model: CNN + Bi-GRU + CTC Loss

Tools: Jupyter Notebook / Google Colab
