# 🖐️ Gesture-Controlled Subway Surfers Web App

Welcome to **Gesture Surfers**, a web app that lets you control the popular game **Subway Surfers** using real-time **hand gestures**. Built using computer vision technologies like OpenCV and MediaPipe, this project transforms your webcam into a game controller — just wave your hand to jump, roll, or move sideways!

---

## 🚀 Live Demo
```bash
# Live link will be available after deployment
```

---

## 📸 Features
```bash
🎮 Control Subway Surfers without a keyboard or touch screen
🖐️ Real-time gesture detection using your webcam
👆 Swipe Up to Jump
👇 Swipe Down to Roll
👉 Swipe Right to Move Right
👈 Swipe Left to Move Left
📷 Live video preview in a modern dashboard
🔄 Auto-launch Subway Surfers in your default web browser
✅ Works on Poki version of Subway Surfers
```

---

## 🛠️ Tech Stack
```bash
Python        # Core programming language
OpenCV        # Webcam capture & image processing
MediaPipe     # Hand landmark detection
PyAutoGUI     # Simulates keyboard arrow presses
Streamlit     # Web-based dashboard UI
Webbrowser    # Launches game in browser
```

---

## 📁 Project Structure
```bash
gesture-subway/
├── app.py                # Streamlit web app entry point
├── gesture_utils.py      # Logic for detecting hand gestures
├── requirements.txt      # Python packages
├── README.md             # Project documentation
```

---

## 🧪 Getting Started (Local Setup)

### Step 1: Clone the Repository
```bash
git clone https://github.com/Harsh456B/gesture-subway.git
cd gesture-subway
```

### Step 2: Set Up a Virtual Environment
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 4: Run the Streamlit App
```bash
streamlit run app.py
```

---

## 🧠 How It Works
```bash
1. Subway Surfers Launch
   - Uses `webbrowser.open()` to launch the game from Poki

2. Webcam Feed
   - OpenCV captures real-time video from your webcam

3. Hand Tracking
   - MediaPipe identifies 21 key hand landmarks

4. Gesture Detection
   - Detects swipe direction from finger tip movement

5. Game Control
   - PyAutoGUI simulates arrow key presses

6. Streamlit Dashboard
   - Shows live webcam feed, logs, and controls
```

---

## 📷 Screenshots
```bash
# Add screenshots after testing the application:
- Live dashboard UI
- Gesture detection
- Subway Surfers gameplay
```

---

## ⚙️ Example requirements.txt
```txt
opencv-python
mediapipe
pyautogui
streamlit
```

---

## 🧩 Troubleshooting
```bash
Problem: cv2.error: The function is not implemented
Fix: Ensure OpenCV is installed with GUI support

Problem: ModuleNotFoundError: No module named 'cv2'
Fix: pip install opencv-python

Streamlit Duplicate Key Error
Fix: Add key="unique" to each Streamlit component

Camera Doesn't Open
Fix: Close other apps using webcam; restart system
```

---

## ✅ Future Enhancements
```bash
[ ] Gesture calibration tool
[ ] Sensitivity slider
[ ] Visual feedback overlays
[ ] Pause/exit with hand signal
[ ] Gesture-based gamification
```

---

## 👏 Acknowledgements
```bash
MediaPipe – for real-time hand tracking
OpenCV – webcam and image processing
Streamlit – beautiful Python UI
PyAutoGUI – simulating keyboard input
```

---

## 📜 License
```bash
MIT License – Free to use and modify
```

---

## ✨ Join the Gesture Revolution
```bash
Control browser games with just your hand and webcam
Made with ❤️ by Harsh Bhogal — https://github.com/Harsh456B
```

