This project presents a machine learning pipeline for detecting deepfake videos using a combination of Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN). The model processes video frames, extracts spatial features using CNNs, and learns temporal dependencies using RNNs.

📌 Project Objective
The goal is to build a deep learning model capable of classifying videos as real or deepfake, using both visual and temporal patterns across video frames.

🔍 Key Features
Frame extraction from videos using OpenCV.

Preprocessing and face detection with MTCNN.

Feature extraction using pretrained CNN models (e.g., Xception/VGGFace).

Temporal sequence learning using RNN (e.g., LSTM/GRU).

Final classification of the video based on frame-level predictions.

🔁 Model Architecture
Face Extraction: Detect and crop faces from video frames using MTCNN.

CNN: Use pretrained CNNs (e.g., Xception) to extract spatial features from faces.

RNN: Feed sequences of features into an RNN to model temporal patterns.

Output: Binary classification (Real or Fake).
