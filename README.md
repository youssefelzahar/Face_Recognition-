# Face Recognition using Siamese Network

This project implements face recognition using a **Siamese Neural Network** to learn similarity between face images, enabling robust identification even with limited labeled data.

---

## Overview

Unlike traditional classification models, this system uses a Siamese Network architecture that learns to compare pairs of face images and determine whether they belong to the same person. This approach is highly effective for face verification tasks where the model predicts similarity scores rather than explicit labels.

The main notebook (`Untitled.ipynb`) includes:

- Preparing pairs of face images for training
- Building and training a Siamese Network for face verification
- Encoding faces into embeddings
- Comparing embeddings to recognize or verify identities
- Visualization of results with similarity scores

---

## Features

- Siamese Network architecture tailored for face verification
- Learns face embeddings to measure similarity
- Effective for one-shot or few-shot learning scenarios
- Face detection and preprocessing integrated with recognition pipeline
- Step-by-step notebook implementation for easy understanding and customization

---

## Requirements

- Python 3.7+
- TensorFlow or PyTorch (depending on implementation)
- OpenCV
- NumPy
- Matplotlib (optional)

Install dependencies:

```bash
pip install -r requirements.txt
