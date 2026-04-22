# Underwater Animal Detection

Computer vision system for detecting marine animals (manta rays, sharks, sea turtles, and rays) in underwater reef footage.

This repository contains a complete pipeline for:
- dataset creation and annotation (COCO format)
- model training
- evaluation
- edge deployment on low-power devices

---

## 📦 Repository Contents

### 📁 Dataset (COCO Format)
- Labeled underwater images in **COCO format**
- Bounding boxes for:
  - manta rays
  - eagle rays / sting rays
  - reef sharks (multiple species)
  - sea turtles
- Includes both:
  - positive images (animals present)
  - negative images (reef background, no animals)

---

### 🧠 Training Pipeline
Python scripts for:
- loading COCO datasets  
- training object detection models  
- evaluating model performance  
- analyzing dataset balance and metrics  

---

### 🤖 Model Files
- Trained and exported models  
- Formats may include:
  - TensorFlow / Keras
  - TensorFlow Lite (TFLite)
- Optimized for edge inference

---

### ⚡ Edge Deployment
Scripts for running detection on real-world hardware, including:
- video inference pipelines  
- real-time detection  
- integration with edge devices such as:
  - Raspberry Pi  
  - USB accelerators (e.g., Coral)  

---

## 🎯 Project Goal

The goal of this project is to develop a robust system capable of:

- detecting marine animals in challenging underwater environments  
- handling varying visibility, lighting, and motion conditions  
- running efficiently on low-power, field-deployed hardware  

This work is part of a broader effort to build an **autonomous underwater camera system** that can monitor reef activity and log animal sightings over long durations.

---

## 🧪 Dataset Philosophy

This dataset is intentionally designed to include:

- diverse environmental conditions (lighting, turbidity, depth)  
- realistic reef backgrounds  
- difficult cases (partial visibility, motion blur, occlusion)  
- negative examples to reduce false positives  

The goal is not just detection accuracy, but **robust real-world performance**.

---

## 🚀 Workflow Overview

1. Extract frames from underwater video  
2. Annotate using bounding boxes (CVAT)  
3. Export in COCO format  
4. Train detection models  
5. Evaluate on unseen footage  
6. Deploy to edge devices  

---

## 📊 Status

This project is actively under development.  
Dataset size and model performance are continuously improving.

---

## 📜 License

This project is licensed under the MIT License.  
See the `LICENSE` file for details.

---

## 🤝 Contributing

Contributions, ideas, and feedback are welcome.

---

## 📬 Contact

w.stewart.king.jr@gmail.com
