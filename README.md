# Pose Detection Game with PyAutoGUI

This project implements a game that interacts with your body movements using a webcam. It detects various poses and hand gestures using the Mediapipe library in Python and performs actions in the game accordingly.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- Recognizes hand gestures like joining hands and adjusts the game state accordingly.
- Supports horizontal movement using body posture (left, right, center).
- Implements jumping and crouching actions based on body posture.

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/Body-Gesture-Game-Control.git
    ```

2. Navigate to the project directory:

    ```bash
    cd pose-detection-game
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main script:

    ```bash
    python main.py
    ```

2. Ensure your webcam is enabled and positioned properly to capture your body movements.
3. Follow the on-screen instructions to start the game by joining your hands. The game will begin once both hands are detected as joined.
4. Perform the specified poses and hand gestures to control the game actions (e.g., moving left/right, jumping, crouching).

## Dependencies

- Python (3.9 - 3.11)
- OpenCV
- Mediapipe
- NumPy
- PyAutoGUI

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.
