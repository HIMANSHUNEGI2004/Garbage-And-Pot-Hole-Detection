<!-- Project Title -->

<h1 align="center">Hybrid Pothole Detection using CNN + YOLO 🚗</h1>

<!-- Description & Badges -->

<p align="center">
    A Hybrid Pothole Detection System combining Convolutional Neural Networks (CNN) for classification and YOLO for real-time object detection. 📸🕵️
</p>

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Code Structure](#code-structure)

## Overview

This project implements a **hybrid pothole detection system** that uses:

- **CNN (Convolutional Neural Network)** → for classifying whether an image contains a pothole or not.
- **YOLO (You Only Look Once)** → for localizing and detecting potholes in real time within frames/images.

The hybrid approach increases detection accuracy by combining **classification confidence (CNN)** with **bounding box detection (YOLO)**, making the system suitable for intelligent road monitoring systems.

---

## Setup

### Prerequisites

- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- YOLOv5 / YOLOv8 (any YOLO version)

### Installation

```bash
pip install opencv-python
pip install tensorflow
pip install numpy
pip install matplotlib
pip install ultralytics   # for YOLOv8 (recommended)
