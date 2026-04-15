# Context-Aware Object Detection under Adverse Weather

## Overview

This project focuses on improving object detection performance under adverse weather conditions such as fog, sand, and low visibility.

It integrates:

* Weather-aware perception
* Depth estimation
* Reliability scoring system

---

## Features

* Object Detection using YOLOv8
* Weather Classification using CNN (ResNet18)
* Depth Estimation using MiDaS
* Context-Aware Decision System

---

## Methodology

Pipeline:

```
Input Image
→ Weather Prediction
→ Object Detection (YOLO)
→ Depth Estimation (MiDaS)
→ Context Awareness
→ Reliability Scoring
→ Final Output
```

---

## Reliability Formula

R = αC + βQ + γW + δe^(−λD)

Where:

* C = Confidence
* Q = Image Quality
* W = Weather Impact
* D = Depth

---


##  Results

* Bounding box detection
* Depth estimation visualization
* Reliability scoring overlay

---

## Evaluation Metrics

* mAP (Object Detection)
* Accuracy (Weather Model)
* Reliability Score Analysis

---

## Tech Stack

* Python
* PyTorch
* OpenCV
* Ultralytics YOLOv8
* Matplotlib / Seaborn

---

## Conclusion

The system enhances perception reliability under adverse environmental conditions by combining multiple modalities.

---

## 👩‍💻 Author

Dhanushi Gupta
