# AI Virtual Mouse using Hand Gestures

This project implements a virtual mouse that allows you to control the cursor and perform mouse clicks using hand gestures captured via a webcam. It utilizes computer vision techniques to track hand landmarks and map them to mouse actions.

## 🚀 Features

* **Cursor Control:** Move the mouse pointer by moving your index finger.
* **Left Click:** Triggered by a specific gesture (Index finger curled, Middle finger straight).
* **Right Click:** Triggered by a gesture (Index finger straight, Middle finger curled).
* **Double Click:** Triggered by curling both Index and Middle fingers.
* **Screenshot:** Take a screenshot by curling both fingers and bringing the thumb close.
* **Smooth Tracking:** Uses MediaPipe for robust hand tracking.

## 🛠️ Tech Stack

* **Python 3.x**
* **OpenCV:** For image processing and video capture.
* **MediaPipe:** For hand landmark detection.
* **PyAutoGUI:** For programmatically controlling the mouse and keyboard.
* **Pynput:** For controlling mouse button presses.

## 📦 Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/Virtual-Mouse.git](https://github.com/YOUR_USERNAME/Virtual-Mouse.git)
    cd Virtual-Mouse
    ```

2.  **Install the required dependencies:**
    You can install the necessary libraries using pip:
    ```bash
    pip install opencv-python mediapipe pyautogui pynput
    ```

## 📂 Project Structure

* `Virtual mouse.ipynb`: The main Jupyter Notebook containing the logic.
* `util.py`: Helper module for calculating angles and distances between landmarks.
* `requirements.txt`: List of dependencies.

## 🎮 How to Use

1.  Ensure your webcam is connected.
2.  Run the notebook or convert the notebook to a Python script (`.py`) and run it:
    ```bash
    python main.py
    ```
3.  **Gestures:**
    * **Move Mouse:** Keep your index finger up and move your hand.
    * **Left Click:** Curl your Index finger while keeping the Middle finger straight.
    * **Right Click:** Curl your Middle finger while keeping the Index finger straight.
    * **Double Click:** Curl both Index and Middle fingers.
    * **Screenshot:** Curl Index and Middle fingers and tuck your thumb in.

4.  Press `q` to quit the application.

## ⚠️ Troubleshooting

* **Lighting:** Ensure the room is well-lit for accurate hand detection.
* **Permissions:** You may need to grant your terminal/IDE permission to control the mouse (especially on macOS).

## 👨‍💻 Author

**Pratham M Jain**
* [GitHub Profile](https://github.com/YOUR_GITHUB_USERNAME)

---
*Developed as part of a Computer Science & Engineering (AIML) project.*
