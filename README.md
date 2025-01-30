# Air Canvas using OpenCV and Mediapipe

Air Canvas is an interactive application that allows users to draw in the air using hand gestures. This project leverages **OpenCV** for image processing and **Mediapipe** for hand tracking.

## Features
- **Hand Gesture Detection:** Uses Mediapipe to track hand landmarks.
- **Air Drawing:** Allows users to draw on a virtual canvas by moving their fingers in the air.
- **Multiple Colors:** Supports Blue, Green, Red, and Yellow colors for drawing.
- **Erase and Clear:** Option to clear the canvas.
- **Real-time Processing:** Runs on a webcam feed for live interaction.

## Technologies Used
- **Python**
- **OpenCV** (for computer vision tasks)
- **Mediapipe** (for hand tracking)
- **NumPy** (for numerical operations)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/sushrutha777/Air-Canvas.git
   cd Air-Canvas
2. **Install dependencies:**
   ```bash
   pip install opencv-python mediapipe numpy
3. **Run the application:**
   ```bash
   python handcontrol.py
## Usage
- Move your index finger to draw.
- Touch your thumb and index finger together to stop drawing (lift mode).
- Use the buttons at the top to change colors.
- Click on the "CLEAR" button to erase everything.
- Press 'q' to exit the application.
