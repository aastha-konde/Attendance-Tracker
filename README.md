# Face Recognition-Based Attendance Management System

## Overview

This project implements a robust facial recognition system to automate attendance tracking using real-time video feed analysis. It employs classical computer vision techniques alongside machine learning models to detect and recognize faces with high accuracy. The system captures, processes, and identifies student faces in live video streams to mark attendance efficiently and reliably.

---

## Main Features

### Face Detection
- Utilizes **Haar Cascade classifiers** to detect faces in real-time from webcam video streams.

### Face Recognition
- Implements the **LBPH (Local Binary Patterns Histograms)** algorithm to uniquely identify students by matching detected faces against a trained facial dataset.

### Preprocessing
- Enhances input images by converting frames to **grayscale** and applying **contrast enhancement** to improve recognition accuracy, especially in low-light conditions.

### Face Cropping & Resizing
- Extracts face regions and normalizes them for consistent and accurate recognition.

### Visual Feedback
- Displays **bounding boxes** and **student names** on the live video feed for clear and immediate identification.

### Data Collection & Model Training
- Supports capturing multiple facial images per student.
- Stores images in a structured format.
- Retrains the LBPH model to continuously improve recognition performance.

### Attendance Visualization
- Integrates with **Power BI** to generate interactive dashboards and visual analytics.
- Helps administrators explore and analyze attendance trends effectively.

---

## Tech Stack

| Component          | Technology Used                          |
|--------------------|-------------------------------------------|
| Programming Language | Python                                  |
| Face Detection       | OpenCV Haar Cascade Classifiers         |
| Face Recognition     | OpenCV LBPH Face Recognizer             |
| Image Processing     | OpenCV (Grayscale conversion, Histogram Equalization) |
| Data Visualization   | Power BI                                |
| Data Storage         | Structured image datasets and records   |
| Hardware             | Standard webcam                         |

---

## Results

- Real-time face detection and recognition with **bounding box visualization**.
- **High recognition accuracy** even under varied lighting conditions due to robust preprocessing.
- **Automated attendance** marking with minimal manual input.
- **Interactive dashboards** in Power BI enable data-driven decisions.
- Demonstrated **robustness and reliability** in real-world, live settings.

---

## Conclusion

By integrating real-time face detection and LBPH-based face recognition, this system automates attendance tracking with **high accuracy and efficiency**. The preprocessing steps improve reliability in challenging lighting environments, making the solution suitable for diverse deployment scenarios. When combined with **Power BI** for visual analytics, administrators gain deep insights into attendance patterns—enabling **smart, contactless**, and **data-driven** attendance management. Its lightweight design also makes it **deployable in resource-limited institutions**, contributing to smarter education systems.

---

## 📂 Suggested Project Structure (Optional)

