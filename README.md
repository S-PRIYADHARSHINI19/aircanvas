🎨 Air Canvas – Virtual Drawing using Hand Gesture Recognition
📌 Project Overview

Air Canvas is a computer vision-based application that allows users to draw on a virtual screen using hand gestures captured through a webcam.

The system detects and tracks hand movements in real-time and converts them into drawing actions without the need for a physical mouse or stylus.

This project demonstrates the practical application of Computer Vision and Human-Computer Interaction concepts.

🚀 Key Features

Real-time hand tracking using webcam

Draw on screen using finger movements

Multiple color selection options

Clear canvas functionality

Touch-free interaction system

🧠 Technical Approach

The system works by:

Capturing live video using OpenCV

Detecting hand landmarks

Tracking fingertip positions

Mapping hand movements to drawing coordinates

Rendering strokes on a virtual canvas

The drawing process is controlled entirely by finger gestures.

🛠️ Tech Stack

Python

OpenCV

NumPy

Mediapipe (for hand tracking)

📂 Project Structure
aircanvas-main/
│
├── aircanvas.py        # Main application file
├── requirements.txt    # Required libraries
└── README.md

⚙️ Installation & Execution
1️⃣ Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
python aircanvas.py


The webcam will open, and you can start drawing using your finger in the air.

🎯 Applications

Virtual whiteboards

Touchless drawing systems

Interactive teaching tools

Gesture-based user interfaces

Assistive technology

📊 Learning Outcomes

Through this project, I gained hands-on experience in:

Real-time computer vision

Hand landmark detection

Gesture recognition

Building interactive AI-based applications

🔮 Future Improvements

Add shape recognition

Save drawings as images

Add gesture-based undo/redo

Deploy as a web application