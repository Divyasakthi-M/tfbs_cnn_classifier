# tfbs_cnn_classifier

CNN-based Classifier for Transcription Factor Binding Sites (TFBS)

This project implements a deep Convolutional Neural Network (CNN) to classify DNA sequences as transcription factor binding (positive) or non-binding (negative).
---

Dataset
- **Input size**: 1000 bp
- **Encoding**: One-hot (A, C, G, T → [1,0,0,0] etc.)

---

Model Architecture

- 4 Convolutional Layers (kernel size 6, padding = same)
- 2 MaxPooling Layers
- Dropout layers for regularization
- Output: Sigmoid unit for binary classification


