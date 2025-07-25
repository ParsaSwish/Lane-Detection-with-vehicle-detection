# 🚗 Real-Time Lane & Vehicle Detection Using YOLOv8 and OpenCV

A real-time computer vision project that detects **lane lines** and **vehicles** from dashcam video using a combination of **YOLOv8** and **OpenCV**. It overlays visual information like lane area, curvature, and vehicle bounding boxes onto the video feed, helping visualize road structure and traffic in real-time.

![Demo](assets/demo.gif) <!-- Optional: add your own screen capture gif -->

---

## 📌 Features

- 🧠 **Lane Detection** using Canny, Hough Transform & Polynomial Fit
- 🛻 **Vehicle Detection** powered by YOLOv8 (`yolov8m.pt`)
- 🔄 **Lane History Smoothing** to improve stability across frames
- 📐 **Curvature Estimation** in meters
- ⚡ **CUDA Support** for GPU acceleration
- 🪟 **Multi-Window Display**: original frame, edge map, ROI, and lane highlight

---

## 🧪 Demo

> Replace with your own video or screen recording

![Detection Output](assets/demo.gif)

---

## 🧠 Tech Stack

- Python 3.x
- OpenCV
- NumPy
- PyTorch
- Ultralytics YOLOv8

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/ParsaSwish/Lane-Detection-with-vehicle-detection.git
cd Lane-Detection-with-vehicle-detection
