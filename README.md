# Gesture-RPS-Battle
A OpenCV and Mediapipe Project
# Rock-Paper-Scissors Game 🖊️🎮

Welcome to the **Rock-Paper-Scissors Game**! This project demonstrates how to use **OpenCV**, **cvzone**, and **Mediapipe** for hand gesture detection in a fun and interactive game.

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


---

## Language Used 🧑‍💻

- **Python**

## Frameworks Used 📚

- **OpenCV**
- **Mediapipe**

