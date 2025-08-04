---
title: AI Safety Inspector

colorFrom: blue
colorTo: red
sdk: gradio
sdk_version: 4.29.0
app_file: app.py
pinned: false
license: mit
---

#  AI Safety Inspector

Detects safety hazards like missing helmets and danger zones using:
- Unsupervised Learning (Autoencoder)
- YOLOv8 Object Detection

##  Features
-  Anomaly detection without labels
-  Helmet detection with bounding boxes

##  How to Use
1. Upload a construction site image
2. Click "Analyze" to detect hazards
3. Use "Helmet Detection" tab for precise bounding boxes

Built with PyTorch, YOLOv8, and Gradio.
