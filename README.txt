
# Player Re-Identification (Single Video Feed)

## 👀 Objective
Detect and track players in a short football video using a YOLOv8 model. Ensure each player keeps the same ID even if they reappear.

## ✅ What I Did
- Used the YOLOv8n (nano) model for real-time player detection.
- Loaded my own 15-second football video from Google Drive.
- Ran detection on 10 video frames using Google Colab.
- Saved annotated frames as images.

## 🧰 Tools Used
- Google Colab
- Python
- YOLOv8 (Ultralytics)
- OpenCV

## 📂 Folder Contents
- `main.ipynb` — the Colab notebook
- `frame_0.jpg` to `frame_9.jpg` — annotated output frames
- `report.txt` — explanation of what was done
