👀 Face Detection Application

📌 Overview

This project is a real-time face detection application using OpenCV. It detects facial features such as eyes, nose, and mouth using Haar Cascade classifiers and draws bounding boxes around them.

🌟 Features
Real-time face detection using OpenCV and Haar cascades
Feature detection for eyes, nose, and mouth
Bounding box annotation with labels
Real-time video stream processing
Easy-to-use and lightweight implementation

🛠️ Technologies Used
Python
OpenCV
Haar Cascade Classifiers

🚀 Getting Started

1️⃣ Clone the Repository:
git clone <your-repo-link>

2️⃣ Install the Required Dependencies:
pip install opencv-python

3️⃣ Ensure Haar Cascade XML Files Are Available:
Make sure the following files are present in the project directory:

haarcascade_frontalface_default.xml
haarcascade_eye.xml
Nariz.xml (for nose detection)
Mouth.xml (for mouth detection)

4️⃣ Run the Application:
python face_detection.py

5️⃣ Usage Instructions:
The webcam will start, and faces will be detected in real-time.
Press 'q' to quit the application.

📊 How It Works

Captures real-time video feed from the webcam.
Converts the frame to grayscale for efficient feature detection.
Detects faces using the Haar Cascade classifier.
If a face is detected, it further detects eyes, nose, and mouth.
Draws bounding boxes around detected features.
Displays the processed video in a new window.

🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue if you encounter any problems.

📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

👨‍💻 Author

Sanika Dudhal GitHub: @Saniikaa

🙏 Acknowledgements
OpenCV for providing easy-to-use computer vision tools
Haar Cascades for facial feature detection
⭐ If you find this project useful, please consider giving it a star to show your support!
