# 🎯 Object Detection with MaxProb



This project implements a real-time **Object Detection from Video** system using deep learning. It annotates video frames and predicts object classes using a pre-trained model, emphasizing the object with the **maximum prediction probability** in each frame.

---

## 📽️ Overview

The solution processes video files by:

- Extracting frames
- Predicting objects per frame using **VGG16**
- Annotating frames with the **most probable** object
- Reconstructing the video with visual labels and confidence

---

## 🔍 Features

✅ Object Detection with **pre-trained VGG16**  
✅ Highlights object with **highest class probability**  
✅ Modular code: easy to modify or extend  
✅ Generates an annotated video as output

---

## 🛠️ Tech Stack

- Python
- OpenCV
- TensorFlow / Keras
- NumPy
- Matplotlib

---
## 📁 Project Structure

<pre>
Object_Detection/
├── annotate_video.py     # Main script to process and annotate video
├── frame_extraction.py   # Extracts frames from video
├── model_prediction.py   # Loads model and predicts object class
├── utils.py              # Helper functions
├── input/                # Place your video files here
├── output/               # Annotated video and results saved here
└── README.md             # Project documentation
</pre>

---
---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sukhadak11/Object_Detection.git
cd Object_Detection

pip install opencv-python tensorflow matplotlib numpy

