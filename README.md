# Bubble Pop

A Pygame-based bubble popping game featuring real-time hand tracking, developed during the Global Game Jam in Halifax (January 2025).

## Overview

This project uses **MediaPipe** for hand tracking and **OpenCV** for camera input/visual effects to create an interactive augmented reality experience. Players use their index finger to pop bubbles on screen while avoiding bombs.

## Features

- **Real-time Hand Tracking**: Control the game using your webcam and hand gestures.
- **Interactive Gameplay**: Pop bubbles to gain time, avoid bombs to save lives.
- **Leaderboard**: Track high scores locally.
- **Dynamic Visuals**: Spongebob-themed background and custom assets.

## Prerequisites

- Python3 and an IDE (e.g., PyCharm, VSCode)
- Webcam

## Installation

1.  **Clone the repository and navigate to the local folder in your terminal**

2.  **Set up a virtual environment (Recommended):**
    ```bash
    python -m venv venv
    # On Windows:
    venv\Scripts\activate
    # On macOS/Linux:
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the main game script:

```bash
python main.py
```

## How to Play

1.  **Start the Game**: Select "START GAME" from the main menu.
2.  **Controls**: Move your hand in front of the camera. The tip of your index finger acts as the cursor.
3.  **Objective**:
    - **Pop Green Bubbles**: Gain +2 seconds.
    - **Avoid Bombs (Red)**: Lose 1 life.
    - Survive as long as possible before time runs out or you lose all 3 lives.

## Credits

Developed in a team of 7 at Global Game Jam 2025, Halifax.
Team Members:
- Tushant Kaura
- Gautam Sahni
- Yugam Yugam
- Param Kataria
- Gurshan Singh
- Hesham Hamed
- Ahmad Abdullah

## License

[MIT License](LICENSE) (Assuming MIT, or specify otherwise)
