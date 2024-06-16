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

## How it Works 🚀
The script starts the webcam and reads frames from it. Each frame is flipped and converted to RGB for processing with MediaPipe Hands. If hand landmarks are detected in a frame, the script calculates the distances between these landmarks. Based on these distances, it recognizes whether the hand gesture represents a dot or a dash in Morse code. The recognized gestures are translated into Morse code and displayed on the frame

## Features
1. Hand Gesture Recognition: The project uses MediaPipe Hands to detect hand landmarks in video frames captured from a webcam. It calculates the distances between these landmarks to recognize hand gestures.
2. Morse Code Translation: The recognized hand gestures are translated into Morse code. The project supports the full set of Morse code symbols for the English alphabet, digits, and some punctuation marks.
3. Real-Time Display: The translated text and input sequence in Morse code are displayed on the video frames in real time.
4. Debounce Time and Pause Duration: The project includes a debounce time to prevent false recognition of gestures due to noise in the video frames. It also includes a pause duration to detect the end of a Morse code sequence.
5. Easy to Run: The project can be easily run from the command line with a single command.
6. Cross-Platform: The project can be run on any platform that supports Python and the required dependencies.
7. Open Source: The project is open source and can be freely modified and distributed under the terms of the MIT license
