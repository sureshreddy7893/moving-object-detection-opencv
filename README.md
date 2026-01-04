# moving-object-detection-opencv
Real-time Moving Object Detection using Python and OpenCV
# 🎥 Moving Object Detection Using OpenCV

A real-time computer vision project that detects and highlights moving objects from a live webcam feed using Python and OpenCV.

---

## 📌 Project Overview
This project implements a real-time moving object detection system by comparing video frames, identifying motion regions, and drawing bounding boxes around detected objects.

---

## 🛠 Technologies Used
- Python 3
- OpenCV
- imutils
- Webcam

---

## ⚙ How It Works
1. Capture live video from webcam
2. Convert frames to grayscale
3. Apply Gaussian blur to reduce noise
4. Store the first frame as background
5. Compute frame difference
6. Apply thresholding and dilation
7. Detect contours
8. Filter noise based on area
9. Draw bounding boxes on moving objects

---

## 📂 Project Structure
Step 1: Install dependencies

Step 2: Run the program
  python code/moving_object_detection.py
  
Step 3: Exit
  Press Q to quit the camera feed.

---

📊 Output

Displays real-time camera feed

Detects motion and highlights moving objects

Shows motion status on screen

---

🚀 Applications

CCTV Surveillance

Security Monitoring

Traffic Analysis

Smart Home Automation

---

⚠ Limitations

Works best with static background

Sensitive to lighting changes

Cannot classify object types

---

🔮 Future Enhancements

Dynamic background subtraction

Object tracking

Human detection using deep learning (YOLO)

---

👨‍💻 Author

Suresh Reddy Munagala
