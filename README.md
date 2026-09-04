# ✋ Finger Counter

A real-time computer vision project that detects and counts raised fingers using a webcam.

The project uses **MediaPipe** to detect hand landmarks and **OpenCV** to process the live camera feed. It can recognize raised fingers on one or two hands and display the total count from **0 to 10**.

## ✨ Features

* ✋ Real-time hand detection
* ☝️ Detect raised fingers
* 🔢 Count fingers from 0 to 10
* 👐 Support for one or two hands
* 🎥 Live webcam processing
* 📊 Display the finger count directly on the screen
* ⚡ Fast real-time performance
* 🎯 Uses hand landmarks for accurate finger detection

## 🛠️ Technologies Used

* 🐍 Python
* 👁️ OpenCV
* ✋ MediaPipe

## ⚙️ How It Works

The application captures live video from the webcam using OpenCV.

MediaPipe detects the user's hand and generates a set of landmarks for each detected hand.

The program analyzes the positions of the finger landmarks to determine whether each finger is raised or folded.

The detected fingers are then counted and the total number is displayed on the webcam feed.

When two hands are visible, the fingers from both hands are counted together.

## 🔄 Processing Pipeline

```text
Webcam
   ↓
OpenCV
   ↓
MediaPipe Hand Detection
   ↓
Hand Landmark Detection
   ↓
Finger State Analysis
   ↓
Finger Counting
   ↓
Display Result
```

## 🔢 Finger Counting

The project can recognize different hand positions and calculate the total number of raised fingers.

| Hand Position     | Count |
| ----------------- | ----: |
| ✊ Closed Hand     |     0 |
| ☝️ One Finger     |     1 |
| ✌️ Two Fingers    |     2 |
| 🤟 Three Fingers  |     3 |
| 🖖 Four Fingers   |     4 |
| 🖐️ Open Hand     |     5 |
| 👐 Two Open Hands |    10 |

The system can combine the results from both detected hands.

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/awabwdbashry-sketch/finger-counter.git
cd finger-counter
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## 📋 Requirements

* 🐍 Python 3.9 or newer
* 📷 Webcam
* 💻 Windows, Linux, or macOS

### Python Dependencies

```text
opencv-python
mediapipe
```

## ▶️ Usage

Run the application:

```bash
python finger_counter.py
```

Allow the application to access your webcam and place one or two hands in front of the camera.

The detected number of raised fingers will be displayed in real time.

## 📁 Project Structure

```text
finger-counter/
│
├── finger_counter.py
├── requirements.txt
├── README.md
├── README_AR.md
└── .gitignore
```

## 💡 Applications

Finger counting can be used as a basic building block for many computer vision and gesture-based systems.

Possible applications include:

* 🎓 Computer vision education
* 🖐️ Gesture-based interfaces
* ♿ Accessibility solutions
* 🧮 Touchless counting systems
* 🤖 Human-computer interaction
* 🎮 Gesture-controlled applications

## ⭐ Advantages

* Simple and easy to understand
* Real-time detection
* Supports two hands
* Requires only a normal webcam
* No special hardware required
* Demonstrates practical hand landmark analysis

## 🚀 Future Improvements

Possible improvements include:

* 🎯 More robust finger detection
* 🖐️ Support for more complex gestures
* 🔢 Custom counting modes
* 🎨 Improved visual interface
* 📊 Finger detection statistics
* 🎮 Integration with gesture-controlled applications
* 📱 Adaptation for mobile devices

## 🎯 Project Purpose

The main goal of this project is to demonstrate how **hand landmark detection** can be used to identify finger states and perform real-time finger counting.

It provides a simple practical example of combining **OpenCV** and **MediaPipe** for gesture-based computer vision.

## 📄 License

This project is available for educational and personal use.

---

⭐ If you find this project useful, consider giving the repository a star!

**GitHub:** `https://github.com/awabwdbashry-sketch/finger-counter`
## 👨‍💻 Developer

**Awab Bashary | AwabBuilds**

GitHub: **awabwdbashry-sketch**

