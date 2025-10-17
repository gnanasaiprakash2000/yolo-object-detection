# 🚀 YOLOv8 Object Detection
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Ultralytics](https://img.shields.io/badge/Ultralytics-YOLOv8-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Active-success)
![Stars](https://img.shields.io/github/stars/gnanasaiprakash2000/yolo-object-detection.svg?style=social)

> Real-time **Object Detection and Segmentation** using **YOLOv8**, the latest version of the YOLO (You Only Look Once) family by **Ultralytics**.

---

## 🧠 Overview

This project demonstrates how to perform **object detection, classification, and segmentation** using the **YOLOv8 neural network**, implemented in Python with the Ultralytics library.  

YOLOv8 is the successor of YOLOv5 — redesigned for higher speed, modularity, and accuracy.  
It supports both **detection (bounding boxes)** and **segmentation (pixel masks)** with easy training and inference workflows.

---

## ⚡ What is YOLOv8?

**YOLOv8** is a **convolutional neural network (CNN)**–based object detection architecture built by [Ultralytics](https://github.com/ultralytics/ultralytics).  
It improves upon earlier YOLO versions (v3–v7) with:

### 🔹 Key Features
- **Anchor-free architecture** → faster training & inference  
- **Decoupled head** → better objectness and classification accuracy  
- **Mosaic & MixUp augmentation** → robust training  
- **Batch normalization + SiLU activation** → improved convergence  
- **ONNX / TensorRT export** for deployment on edge devices  
- **Supports tasks:** detection, segmentation, classification, and pose estimation  

### 🧩 YOLOv8 Model Variants
| Model | Size | Speed (ms) | mAP (COCO) | Best for |
|--------|------|------------|-------------|-----------|
| YOLOv8n | Nano | ~2.7 | 37.3 | Edge / Mobile |
| YOLOv8s | Small | ~6.2 | 44.9 | Real-time |
| YOLOv8m | Medium | ~11.2 | 50.2 | Balanced |
| YOLOv8l | Large | ~22.0 | 52.9 | High accuracy |
| YOLOv8x | XLarge | ~34.0 | 53.9 | Research use |

---
