This project enables gesture-based control of the mouse cursor on a computer using a webcam or depth sensor. The system recognizes hand gestures and translates them into mouse movements and clicks.

Features
Hand Gesture Recognition: Uses machine learning to recognize hand gestures and translate them into mouse movements.

Mouse Control: Allows for moving the mouse cursor, clicking, scrolling, and dragging with gestures.

Real-Time Interaction: Provides smooth and responsive mouse control using real-time hand gesture detection.

Customizable Settings: Customize gesture-to-action mappings to suit individual preferences.

Installation
To set up the Gesture Control Mouse, follow the steps below:

Prerequisites
Python 3.x

OpenCV (for video capture)

Mediapipe (for hand tracking)

Other dependencies (listed in requirements.txt)

Steps
Clone the repository to your local machine:
git clone https://github.com/your-username/gesture-control-mouse.git
cd gesture-control-mouse

Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the script to start the gesture control:

bash
Copy
Edit
python gesture_control.py
The webcam will activate, and the system will begin recognizing hand gestures.

Usage
Move the mouse: Move your hand in the air to control the mouse cursor.

Left click: Make a fist or a specific gesture (depending on the configuration).

Right click: Perform a predefined gesture, such as a finger snap.

Scroll: Use a scrolling gesture (e.g., moving two fingers up or down).

Drag: Hold a fist gesture to drag the mouse.

Configuration
You can modify the gestures and actions in the configuration file (config.json) to fit your preferences. The default configuration is as follows:

json
Copy
Edit
{
  "left_click": "fist",
  "right_click": "snap",
  "scroll_up": "two_finger_up",
  "scroll_down": "two_finger_down"
}
Contributing
Contributions are welcome! If you'd like to contribute to this project, follow these steps:

Fork the repository.

Create a new branch.

Make your changes.

Commit and push the changes.

Create a pull request.

Acknowledgements
Mediapipe - for hand gesture recognition.

OpenCV - for video capture and image processing.

Python - for scripting and automation.


