# GestureSonic

This project utilizes computer vision techniques to control system volume based on hand gestures. By tracking hand movements using the MediaPipe library, it adjusts the volume level accordingly.

## Requirements

- Python 3.8 
- OpenCV (cv2)
- NumPy
- Mediapipe
- PyAutoGUI

## Usage

1. Run the `main.py` script:
   - ```bash
     main.py
     ```

2. Ensure your webcam is connected and positioned properly.

3. When the application starts, it will display the webcam feed with hand landmarks drawn on the screen.

4. To adjust the volume:
   - Extend your thumb and index finger apart.
   - Move them closer together to decrease the volume.
   - Move them farther apart to increase the volume.

5. Press 'x' on your keyboard to exit the application.
