# Hand Tracking using MediaPipe and OpenCV

This project demonstrates real-time hand tracking using Google's [MediaPipe](https://google.github.io/mediapipe/) and [OpenCV](https://opencv.org/). It captures video from your webcam and overlays hand landmarks with connections on detected hands.

## 📸 Features

- Real-time webcam feed with hand detection
- Tracks 21 hand landmarks
- Draws hand connections using MediaPipe’s drawing utilities

## 🔧 Technologies Used

- Python
- OpenCV
- MediaPipe

## 🛠️ Installation

Follow the steps below to set up and run the project:

### 1. Clone the repository


git clone https://github.com/your-username/hand-tracking-mediapipe.git
cd hand-tracking-mediapipe

### 2. (Optional) Create and activate a virtual environment


python -m venv venv
### Activate the environment
### On Windows:
venv\Scripts\activate
### On macOS/Linux: 
source venv/bin/activate


### 3. Install dependencies
pip install opencv-python mediapipe


### ▶️ How to Run
Run the Python script using:

python hand_tracking.py
A new window will show your webcam feed with hand landmarks.

Press 'q' to quit the application.


### 💡 Future Improvements
Recognize specific hand gestures 

Control mouse or media using hand movement

Save captured hand landmark data for training models

### 👨‍💻 Author
Abhishek Kumar
GitHub: https://github.com/themarcos-abhi
