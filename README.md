# Hand Gasture for Volume Control
This project involves developing an algorithm to control sound volume through hand gesture detection using a laptop's integrated camera. By utilizing computer vision and machine learning techniques, the system can recognize hand gestures in real-time and adjust the volume accordingly. The project is packaged with a user-friendly Graphical User Interface (GUI) built using Streamlit, allowing users to interact with the system seamlessly.

## Key Features:
- **Hand Gesture Detection:** The algorithm leverages OpenCV to capture real-time video feed from the laptop’s camera and detect hand gestures.
- **Volume Control:** Based on recognized gestures, the algorithm adjusts the system’s sound volume (e.g., raising or lowering).
- **Streamlit GUI:** A web-based interface built with Streamlit enables easy interaction with the hand gesture detection system. The GUI displays the video feed, provides feedback on detected gestures, and shows the current volume level in real-time.

## Technologies Used:
- OpenCV: For video capturing and image processing.
- Mediapipe: A machine learning framework used for efficient hand tracking and gesture recognition.
- Streamlit: To create an interactive, easy-to-use web application that allows users to operate the system without command-line inputs.
- Numpy & Python: For handling the computational and mathematical operations behind the algorithm.

## How It Works:
1. Real-time Gesture Detection: The system captures video input from the laptop’s camera and processes each frame to detect hand landmarks.
2. Gesture Recognition: Specific hand gestures are mapped to volume control actions. For example:
   - Closed index-thumb finger : lowering volume
   - Open index-thumb finger : increasing volume
3. Volume Control: The detected gesture is converted into system-level commands to adjust the volume.
4. Streamlit Interface: The GUI visualizes the camera feed and displays detected gestures and the current volume level in real-time.
