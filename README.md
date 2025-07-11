# 🚁 Drone Detection System using YOLOv8 and FMCW Radar

An intelligent drone detection system that combines **computer vision** and **radar-based motion sensing** to accurately identify and track drones in restricted airspaces. Built using **YOLOv8** for visual detection and the **Waveshare 24GHz FMCW radar** module for motion detection.

---

## 🎯 Objectives

- ✅ Detect drones using camera feed and YOLOv8 object detection
- ✅ Sense motion using FMCW radar and filter non-drone objects
- 🔄 Fuse radar + vision data for robust detection
- 🚨 Trigger alerts when drone is detected in restricted area

---

## 🧠 Features

- 🧍‍♂️ **Dual-Sensor Fusion** – Combines radar and visual data to reduce false positives
- 📸 **YOLOv8-based Visual Detection** – Real-time drone classification and bounding boxes
- 📡 **24GHz FMCW Radar** – Detects object motion and range using Waveshare S3KM1110
- ⏱️ **Low Latency** – Optimized for real-time performance
- 📊 **Logging & Display** – Optional debug window and event logging

---

## 🛠 Tech Stack

| Component       | Tool / Library                            |
|------------------|--------------------------------------------|
| Visual Detection | YOLOv8 (Ultralytics), OpenCV              |
| Radar Interface  | UART Serial (PySerial), Waveshare S3KM1110 |
| Data Fusion      | Python + Custom Logic                     |
| Visualization    | OpenCV, Matplotlib (optional)             |
| Hardware         | Camera + Waveshare 24GHz FMCW Radar       |

---
