# Eye-Controlled Mouse Using OpenCV & Mediapipe
## Project Description
The Eye-Controlled Mouse is a Python-based project that allows users to control the mouse cursor using eye movements and perform click actions by blinking.
This project utilizes OpenCV for video processing, MediaPipe for facial landmark detection, and PyAutoGUI for controlling mouse actions.

## Features
Real-time face and eye tracking using a webcam
Move the mouse cursor using eye gaze
Click the mouse by blinking
Lightweight and fast performance
Can be used as an accessibility tool for people with disabilities
## Technologies Used
- Python
- OpenCV (cv2) - for video processing
- MediaPipe - for detecting facial landmarks
 PyAutoGUI - for controlling mouse movements
## Project Structure
Eye-Controlled-Mouse
- eye_controlled_mouse.py  # Main script
- README.md  # Project documentation
- requirements.txt  # Dependencies list
  
## Installation & Setup
## Install Dependencies
Make sure you have Python installed, then run:
 ```sh
   pip install opencv-python mediapipe pyautogui
   ```

## Run the Program
Execute the Python script: 
 ```sh
 python eye_controlled_mouse.py
   ```

## How It Works

* The webcam starts capturing your face.
* The program detects your eyes and tracks movements.
* Your eye gaze moves the mouse cursor.
* Blink your left eye to simulate a mouse click.
  
#
> [!TIP]
> Usage Notes
* Ensure proper lighting for better eye detection.
* Avoid moving your head too much for accurate tracking.
* If tracking is inaccurate, adjust your camera angle and position.
  
## Future Improvements
* Support for double clicks and right clicks
* More gesture-based controls (e.g., scrolling with eye gestures)
* AI-based calibration for better accuracy
## Contributing
Feel free to contribute by forking the repository and submitting a pull request.

## License
This project is open-source and available under the MIT License.

## Author
Your Name - [K.r Tanay](https://github.com/krtanay7)

