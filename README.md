# DeepFace Multi-Face Recognition System

This project implements a face recognition system that can detect and identify multiple people in test images using **DeepFace**, **ArcFace embeddings**, and the **RetinaFace detector**.

It works by:
1. Creating face embeddings for known people using the ArcFace model.
2. Detecting and extracting all faces from test images.
3. Comparing detected faces to known encodings using Euclidean distance.
4. Labeling each face with the correct name or as "Unknown".
---

## Tools and Technologies

- [`DeepFace`](https://github.com/serengil/deepface) – face recognition framework
- `ArcFace` – face embedding model (deep feature extractor)
- `RetinaFace` – face detection backend
- `OpenCV` – image loading, drawing, and preprocessing
- `matplotlib` – result visualization