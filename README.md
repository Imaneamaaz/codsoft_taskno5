# codsoft_taskno5

# Face Recognition Project

This project implements a face recognition system using MTCNN for face detection and FaceNet for face embeddings. The system is optimized using Hyperopt and evaluated with various metrics. It also includes a function to recognize faces in images.

# Features

- **Face Detection:**  Detects faces in images using Haarcascade.
- **Face Embedding Extraction:** Extracts face embeddings using FaceNet.
- **Face Recognition:** Recognizes faces based on the extracted embeddings.
- **Model Optimization:** Optimizes the SVM model using Hyperopt.

# Requirements
- `Python 3.x`
- `OpenCV`
- `MTCNN`
- `keras-facenet`
- `scikit-learn`
- `hyperopt`
- `numpy`
- `matplotlib`
- `tensorflow`

You can install the necessary packages using:
```bash
!pip install mtcnn keras_facenet hyperopt tensorflow opencv-python scikit-learn numpy matplotlib

