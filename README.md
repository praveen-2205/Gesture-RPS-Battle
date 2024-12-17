# Gesture-RPS-Battle
A OpenCV and Mediapipe Project
# Rock-Paper-Scissors Game 🖊️🎮

As the **Sublead** of the AI and Data Science Club at my college, I conducted a session on **OpenCV** and **Mediapipe**, introducing students to computer vision concepts and practical applications. To make the session engaging and hands-on, I developed this Rock-Paper-Scissors Game project, showcasing how hand gesture recognition can be implemented using these powerful tools. This project served as a fun and educational way to demonstrate real-world applications of AI and computer vision.


## Language Used 🧑‍💻

- **🐍Python**

## Frameworks Used 📚

- **🖼️OpenCV**
- **🤖Mediapipe**

---
## Overview 📊

The repository includes two versions of the Rock-Paper-Scissors game:

1. **Without Mediapipe**: Utilizes OpenCV and cvzone’s HandTrackingModule for detecting hand gestures. It uses basic gesture classification for Rock, Paper, and Scissors, and provides an interactive gameplay experience against an AI opponent.
2. **With Mediapipe**: Leverages Mediapipe's robust hand tracking and gesture classification based on hand landmarks. This version offers improved accuracy, better visuals, and real-time feedback on gameplay.

---

## Features 🔹

### Version 1: Without Mediapipe

- Hand detection using cvzone.
- Simple gesture classification for Rock, Paper, and Scissors.
- AI opponent for competitive gameplay.

### Version 2: With Mediapipe

- Advanced hand tracking using Mediapipe.
- Gesture classification based on hand landmark positions.
- Improved visuals and game feedback.

---

## Installation ⚙️

### Prerequisites

Make sure you have Python 3.7 or later installed. Then, install the following libraries:

```bash
pip install opencv-python
pip install mediapipe
pip install cvzone
```

---

## How to Play 🎮

### Version 1: Without Mediapipe

1. Run the `first.py` script.
2. Press **'s'** to start the game.
3. Show your hand gestures (Rock, Paper, Scissors) in front of the camera.
4. Watch the AI’s move and check who wins!

### Version 2: With Mediapipe

1. Run the `rockpaperscissors.py` script.
2. Place your hand in front of the camera to start the game.
3. The game will detect your gesture and randomly generate the AI’s move.
4. View the results on the screen with scores updated in real-time.

---

## File Structure 🗂🖉

- `first.py`: The script without Mediapipe, using OpenCV and cvzone.
- `rockpaperscissors.py`: The script with Mediapipe for advanced hand gesture recognition.
- `Resources/`: Contains necessary images for game visuals (like the background and AI moves).
