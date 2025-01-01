# P2-AI-Powered-Gym-Tracker-with-Python-and-MediaPipe

In this project, I developed an AI-powered gym tracker using Pose Estimation techniques. With MediaPipe and Python, I designed a system that detects poses from a live webcam feed, extracts joint coordinates, calculates joint angles, and tracks workout repetitions in real-time. The results are displayed on the screen using OpenCV, creating an interactive and practical fitness tool.

🔧 Technologies and Tools Used
- Python 3: Programming language for implementation.
- MediaPipe: Pose estimation library for detecting body poses.
- OpenCV: For video capture and visualization of results.
- NumPy: To perform numerical computations for joint angle calculations.

💡 How the System Works
1. Setup MediaPipe: Configure MediaPipe’s pose estimation solution in Python for real-time use.
2. Capture Webcam Feed: Use OpenCV to stream live video and detect body poses.
3. Joint Coordinates Extraction: Identify and extract key body points (joints) detected by MediaPipe.
4. Angle Calculation: Use NumPy and trigonometry to compute angles between joints for movement analysis.
5. AI Gym Tracker: Build a system to count workout repetitions based on pose transitions (e.g., curls).

📋 Step-by-Step Workflow
1. Install and Import Dependencies: Install MediaPipe, OpenCV, and other required libraries.
2. Make Real-Time Pose Detections: Set up a live webcam feed and process the detected body poses.
3. Extract Key Joints: Identify specific body parts and extract joint coordinates for further analysis.
4. Calculate Joint Angles: Compute angles using trigonometry to track specific movements accurately.
5. Build a Curl Counter: Develop logic to count repetitions of exercises based on angle thresholds.

🔥 Project Features
- Real-Time Feedback: Displays detected poses and rep count live on the screen.
- Interactive Visualization: Renders body landmarks with OpenCV for better user experience.
- Efficient Pose Analysis: Leverages AI to monitor workout performance and ensure form accuracy.

[![P2: AI-Powered Gym Tracker with Python and MediaPipe](https://img.youtube.com/vi/7D_6EXIWhYM/0.jpg)](https://youtu.be/7D_6EXIWhYM)
