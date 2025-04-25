🏋️‍♂️ AI Fitness Coach
An AI-powered personal fitness trainer built using Python and Streamlit. This app allows users to perform exercises with real-time feedback using their webcam or uploaded videos. It uses pose estimation to detect body positions, count repetitions, visualize joint angles, and even provide audio feedback.

🚀 Features
🔍 Exercise Detection: Supports Push-ups, Squats, Bicep Curls, and Shoulder Presses using pose estimation.

🎥 Input Modes:

Webcam Mode: Live exercise tracking with real-time rep counting.

Video Mode: Upload a video for analysis and feedback.

🔢 Repetition Counter: Automatically counts reps for supported exercises.

🎯 Goal Setter (Webcam Mode): Set your target number of reps and sets, and get a "Goal Achieved" notification when you're done.

🗣️ Voice Interaction: Supports voice commands via speech recognition and gives audio feedback using text-to-speech.

📐 Angle Visualization: Joint angles are shown to help users correct their form.

🛠️ Technologies Used
Python

Streamlit

OpenCV

MediaPipe (for Pose Estimation)

Pyttsx3 (Text-to-Speech)

SpeechRecognition (Voice Commands)

NumPy, Time, Math

📁 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/AI-Fitness-Coach.git
cd AI-Fitness-Coach
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app

bash
Copy
Edit
streamlit run app.py
📸 Screenshots
Add a few screenshots or screen recordings here showing the app interface, rep counter in action, and goal achieved message.

📅 Future Improvements
Add more exercises and flexibility/mobility routines.

Include posture correction and alerts.

Integration with fitness wearables.

Personalized fitness reports and progress tracking.
