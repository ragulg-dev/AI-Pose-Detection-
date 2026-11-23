# AI Pose Detection & Workout Tracking System

A real-time AI-powered human pose detection system built using Python, MediaPipe, and OpenCV. It tracks body landmarks through a webcam, automatically counts workout repetitions, evaluates exercise posture, and provides real-time feedback to help users improve their workout form.

## Features

- **Real-Time Pose Detection:** Tracks 33 body landmarks using MediaPipe Pose.
- **Automatic Rep Counting:** Counts exercise repetitions by analyzing joint angles and movement stages.
- **Posture Evaluation:** Identifies incorrect exercise posture using angle-based conditions.
- **Live Feedback:** Displays posture correction suggestions directly on the webcam feed.
- **Joint Angle Calculation:** Analyzes body movements using landmark coordinates.
- **Webcam Integration:** Captures and processes live video using OpenCV.

## Tech Stack

- Python
- MediaPipe
- OpenCV
- NumPy

## How It Works

1. Captures live video from the webcam using OpenCV.
2. Detects body landmarks using MediaPipe Pose.
3. Extracts landmark coordinates and calculates joint angles.
4. Uses angle thresholds to identify movement stages.
5. Automatically counts repetitions based on movement transitions.
6. Evaluates posture and provides real-time correction feedback.
7. Displays landmarks, repetition count, movement stage, and posture information on the video feed.

## Installation & Usage

Clone the repository:

```bash
git clone https://github.com/your-username/AI-Pose-Detection.git
```

Navigate to the project folder:

```bash
cd AI-Pose-Detection
```

Install dependencies:

```bash
pip install opencv-python mediapipe numpy
```

Run the application:

```bash
python main.py
```

Make sure your webcam is connected and accessible.

## Applications

- Home workout assistance
- Exercise repetition tracking
- Posture monitoring
- Fitness movement analysis
- Computer vision applications

## Future Improvements

- Support for additional exercises
- Improved posture correction accuracy
- Voice-based feedback
- Workout progress tracking
- User-friendly interface

## Author

**Ragul G**  
Python Developer | AI & Data Science Graduate
