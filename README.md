Pose Detection with Posenet

    Welcome to the Pose Detection with Posenet project, 
    a real-time human pose estimation system using the Posenet model from ML5.js. 
    This project provides a simple example of how to integrate pose detection into your web applications and how to calculate angles between specific body parts.

Features

      Real-time human pose detection using Posenet.
      Visualization of detected poses with key body joint markers and skeleton lines.
      Calculation of angles between the right hip, right knee, and right ankle.
      Displaying a message when the right hip makes an angle of approximately 180 degrees.

Prerequisites:
    
    To create a Python code that captures real-time video, detects body pose using a pose estimation model, and displays a message when the right leg forms a 180-degree angle,
    you can use libraries like OpenCV for video capture and MediaPipe for pose estimation.

 Install the libraries:

        pip install opencv-python mediapipe
output:
    
    The code detects the body pose, identifies the coordinates of the right leg key points (hip, knee, ankle), and calculates the angle using vector mathematics.
    If the angle equals 180 degrees, the message "Right Leg Straight!" is displayed on the screen.
