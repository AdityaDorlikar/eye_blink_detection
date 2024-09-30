# eye_blink_detection
The goal of eye blink detection is to determine when a person blinks, which can be useful in various applications such as driver monitoring systems, human-computer interaction, and more. This is typically achieved by detecting the face and eyes in real-time video and monitoring the state of the eyelids.

Eye Blink Detection using OpenCV

Table of Contents:
  
    -Overview
  
    -Prerequisites
  
    -Usage
  
    -Code Structure

**Overview:**

  This project implements an eye blink detection system using OpenCV. The system captures video from a webcam, detects faces and eyes, and determines when a user blinks based on the eye aspect ratio (EAR). 
    This technology can be utilized in various applications such as driver monitoring systems, attention tracking, and human-computer interaction.

**Prerequisites:**
  
    -Python 3.x
  
    -OpenCV
  
    -NumPy

**Usage:**

    1.Open your terminal or command prompt.

    2.Navigate to the project directory:
        cd eye-blink-detection

    3.Run the script:
      python eye_blink_detection.py

    4.A window will open displaying the video feed from your webcam. The program will detect faces and eyes, and it will print "Blink detected!" in the console whenever a blink is recognized.

    5.Press 'q' to quit the application.

**Code Structure:**

    eye_blink_detection.py: The main script for eye blink detection. It contains the logic for face and eye detection, as well as the blink detection using the eye aspect ratio.
  
    README.md: This file, which contains an overview of the project, installation instructions, and usage details.
