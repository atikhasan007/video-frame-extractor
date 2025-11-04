# 🎬 Video Frame Extractor

A simple Python utility to extract video frames from clips — perfect for **dataset creation** in computer vision and deep learning projects.

---

## 📘 Overview

The script **`generate_video_to_frame.py`** (or `frame-generator.py`) extracts all frames from a given video clip and saves them into an **`extracted-frames`** directory.

This helps when preparing datasets for:
- 🧠 Image classification  
- 🕵️ Object detection  
- 🎥 Video analysis  
- 🤖 Deep learning training  

---

## ⚙️ Dependencies & Installation

### 📦 Required Packages
- `opencv-python` — For video frame extraction  
- `os` — Built-in with Python ≥3.4  

### 🧩 Installation Steps

It is **strongly recommended** to use a **virtual environment** for any computer vision project to avoid package conflicts.

```bash
# Create & activate a virtual environment
python3 -m venv venv
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows

# Install required packages
pip install opencv-python
