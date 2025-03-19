# Diploma-Project:

-------Driver Drowsiness Detection System----------

🚗 Overview:

The Driver Drowsiness Detection System is a computer vision-based application that helps prevent road accidents by monitoring a driver’s alertness. It continuously analyzes facial features to detect drowsiness and alerts the driver in real time.

🛠️ Features:

Real-time face detection using OpenCV

Eye and mouth detection for drowsiness analysis

Alarm system to alert the driver

User-friendly interface for easy operation

Lightweight and efficient for real-time execution

🏗️ Tech Stack:

Programming Language: Python 3

Libraries Used:

OpenCV

NumPy

SciPy

Playsound

Dlib

Imutils

📌 Installation:

Clone the repository:

git clone https://github.com/yourusername/driver-drowsiness-detection.git
cd driver-drowsiness-detection

Install dependencies:

pip install opencv-python numpy scipy playsound dlib imutils

Download the required facial landmark model:

Get the shape_predictor_68_face_landmarks.dat file from Dlib’s official model

Extract and place it in the project directory

🚀 Usage:

Run the script to start monitoring driver drowsiness:

python drowsiness_detection.py


⚡ How It Works:

The system captures real-time video input from a webcam.

It detects the driver’s face and extracts eye and mouth features.

It calculates the Eye Aspect Ratio (EAR) to determine drowsiness levels.

If drowsiness is detected, an alarm sound is played to alert the driver.

📌 Future Enhancements:

Implement AI-based deep learning models for improved accuracy

Add support for mobile devices and embedded systems

Integrate with vehicle control systems for enhanced safety

🤝 Contributing:

Contributions are welcome! Feel free to fork the repository and submit pull requests.

✨ Acknowledgments:

Special thanks to the open-source community for providing resources and tools for development.

🚀 Stay Safe, Drive Smart!

