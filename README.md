# Edge AI Pothole Detection using Raspberry Pi

## Project Overview
This project implements an **Edge AI based pothole detection system** using a Raspberry Pi and deep learning. The system captures road images using a Pi Camera and detects potholes in real time using a **YOLOv5 deep learning model** optimized for edge deployment.

The goal of this project is to develop a **low-cost, real-time road monitoring solution** that can help authorities detect and repair potholes faster, improving road safety and infrastructure maintenance.

---

## Hardware Used
- **Raspberry Pi 4 (4GB RAM)**
- **Raspberry Pi Camera Module V2**
- MicroSD Card (32GB or higher)
- Power Supply for Raspberry Pi

---

## Software and Technologies
- **Python**
- **YOLOv5 (Deep Learning Model)**
- **TensorFlow Lite**
- **OpenCV**
- **PyTorch**
- **Raspberry Pi OS**

---

## Model Optimization for Edge Deployment
To enable efficient real-time inference on Raspberry Pi, the trained model was optimized using:

- **Float16 Quantization** – reduces model size while maintaining accuracy
- **INT8 Quantization** – improves inference speed and reduces computational load
- **TensorFlow Lite Conversion** – enables deployment on low-power edge devices

---

## System Workflow

1. **Image Capture**  
   The Raspberry Pi Camera continuously captures frames from the road environment.

2. **Preprocessing**  
   Captured frames are resized and processed using OpenCV.

3. **Pothole Detection**  
   The optimized **YOLOv5 model** detects potholes in the image.

4. **Edge Inference**  
   The TensorFlow Lite model performs real-time inference on the Raspberry Pi.

5. **Output**  
   Detected potholes are highlighted with bounding boxes on the video feed.

---

## Key Features
- Real-time pothole detection on edge device
- Low-cost and portable system
- Optimized deep learning model for embedded hardware
- Efficient inference using TensorFlow Lite
- Suitable for smart city and road monitoring applications

---

## Project Structure
