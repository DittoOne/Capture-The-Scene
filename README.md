# 🎥 Video to Panorama Generator

Convert any video into a beautiful panoramic image using OpenCV and Python.  
This tool extracts key frames from a video and stitches them together to generate a wide-angle panoramic view.

---

## ✨ Features

- ✅ Extracts up to 30 evenly spaced frames for stitching
- 🧠 Uses OpenCV’s Stitcher API to generate panorama
- 📉 Automatically resizes large frames for better performance
- 🔄 Fallback: If stitching fails, falls back to horizontal concatenation
- 💾 Saves output image in the same directory as the input video
- 🖼️ Displays final panorama using `matplotlib`

---

## 📦 Tech Stack

- Python 3.x
- OpenCV (cv2)
- NumPy
- Matplotlib
- OS, pathlib

---

## 🎥 Demo

https://user-images.githubusercontent.com/yourusername/yourdemo.mp4  
📌 *Replace this link with your actual demo video showing the input video and resulting panorama.*

---

## 🚀 Getting Started

### 🛠️ Prerequisites

Ensure the following Python packages are installed:
-- pip install opencv-python numpy matplotlib

🧠 How It Works
  Extracts evenly spaced frames (max 30) from input video
  
  Downscales frames for speed if width > 800px
  
  Attempts to stitch using cv2.Stitcher.create()
  
  If stitching fails, performs simple np.hstack() horizontal concatenation
  
  Displays the result using matplotlib

## 🎥 Demo

✅ Check out how it works in this video:

[![Watch the Demo](https://drive.google.com/file/d/1OJ47AP75xOsq3r3Q9y1TW6tqJRugN0rm/view?usp=drive_link)

👤 Author
🌐 LinkedIn Profile [Md Shahriar Rahman Bhuiyan](https://www.linkedin.com/in/md-shahriar-rahman-bhuiyan-3893012a8)



