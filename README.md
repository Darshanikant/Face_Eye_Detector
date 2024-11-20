# Face_Eye_Detector
# Face and Eye Detection App
- This project is a real-time Face and Eye Detection App built using OpenCV and Python. It utilizes Haar cascades to detect faces and eyes from webcam input, making it a -- - simple yet powerful demonstration of computer vision capabilities.

# Features
- Real-time face and eye detection using webcam input.
- Highlights detected faces with blue bounding boxes labeled "Face."
- Highlights detected eyes with red bounding boxes labeled "Eye."
- Easy-to-use Python script with OpenCV integration.
# Prerequisites
- Python 3.6 or higher
- OpenCV library
- NumPy library
- Installation


# Code Explanation
- The app uses Haar cascades for face and eye detection:
- Face Detection: haarcascade_frontalface_default.xml
- Eye Detection: haarcascade_eye.xml
- It preprocesses the webcam frames by converting them to grayscale.
- Detected features are annotated with bounding boxes and labels for better visualization.
# Example Output
<img width="959" alt="face i detector" src="https://github.com/user-attachments/assets/c7a02334-e9e0-49bb-8a6f-294912bdeb59">


# Challenges Faced
- Configuring the paths to Haar cascade XML files.
- Fine-tuning the detection parameters for accurate results.
# Conclusion
- This project demonstrates the potential of computer vision using OpenCV for real-time facial feature detection. It's an excellent starting point for developing more advanced applications like face recognition, emotion detection, or even eye-tracking systems.
