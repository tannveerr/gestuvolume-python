<div align="center">
<h1>Hand Gesture based PC Volume Control</h1>
</div>

<h3>Overview</h3>
<p>The Hand Gesture based PC Volume Control is a Python project that allows users to control their computer's audio volume using hand gestures captured through a webcam. The project utilizes the OpenCV library for computer vision, the MediaPipe library for hand tracking, and additional libraries including comtypes, numpy, and pycaw.</p>

<h3>Features</h3>
Control computer volume using hand gestures.
Real-time hand tracking using the MediaPipe library.
Adjustable sensitivity for gesture recognition.
Easy setup and configuration.

<h3>Requirements</h3>
Ensure you have the following libraries installed before running the project:
  i.opencv-python
  ii.mediapipe
  iii.comtypes
  iv.numpy
  v.pycaw
Command: 
pip install opencv-python mediapipe comtypes numpy pycaw

Note: MediaPipe is working on Python version 3.8.

<h3>How to Use?</h3>
-> Clone the repository to your local machine.
-> Navigate to the project directory:
      cd hand-gesture-volume-control
-> Run the main Python script:
      python main.py
-> A webcam window will open, and the program will start tracking your hand gestures.
-> To control the volume, use the following gestures:
    Raise index finger: Increase volume.
    Lower index finger: Decrease volume.
    Thumb and pinky out: Mute volume.
    Adjust the sensitivity parameter in the script to fine-tune gesture recognition according to your preferences.

<h3>Configuration</h3>
<p>You can customize the sensitivity, hand tracking parameters, and other settings by modifying the constants at the beginning of the main.py script.</p>

<h3>Dependencies</h3>
OpenCV
MediaPipe
comtypes
numpy
pycaw

<h3>Acknowledgments</h3>
<p>Special thanks to the OpenCV and MediaPipe teams for providing powerful computer vision tools.
Inspired by the idea of gesture-based interaction for enhanced user experience.
Feel free to contribute, report issues, or suggest improvements!</p>






