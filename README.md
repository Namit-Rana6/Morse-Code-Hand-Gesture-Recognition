# Hand Gesture Recognition for Morse Code 🖐️💻

This project uses a webcam to capture video frames, processes them using MediaPipe Hands to detect hand landmarks, and performs hand gesture recognition based on the distances between these landmarks. It translates the recognized gestures into Morse code and displays the translated text and input sequence on the frame.

![Demo](demo.gif)

## Dependencies 🛠️

- OpenCV
- NumPy
- MediaPipe
- Time

## How to Run ▶️

1. Ensure you have Python 3 installed.
2. Install the required dependencies with pip:


pip install opencv-python numpy mediapipe

How it Works 🚀
The script starts the webcam and reads frames from it. Each frame is flipped and converted to RGB for processing with MediaPipe Hands. If hand landmarks are detected in a frame, the script calculates the distances between these landmarks. Based on these distances, it recognizes whether the hand gesture represents a dot or a dash in Morse code. The recognized gestures are translated into Morse code and displayed on the frame
