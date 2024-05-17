# Balloon Blast with Hand Tracking

Balloon Blast is an interactive game that uses a hand-tracking module to pop balloons when the player closes their fingers. The game combines computer vision and machine learning to provide an engaging user experience, allowing users to interact with the game using their webcam.

![Gameplay](demo.mp4) 


## Getting Started
This guide will explain how to run the Balloon Blast game, including installation steps and usage instructions. It also provides an overview of the hand tracking technology used in the game.

### Prerequisites
You will need Python 3.X.X and several packages opencv, mediapipe


## Usage Commands

1. *Installation:*
   ```bash
   pip install -r requirements.txt
   
2. *Running the System:*
   ```bash
   python main.py



The main script initializes the game, sets up the main game loop, and handles the transition between the menu and the game state.

Key Sections:
Setup: Initializes Pygame, sets the window position, and loads the music.
Main Loop: Handles user events, updates the game state, and displays the FPS if enabled.
handtracking.py
This module handles the hand tracking functionality using the Mediapipe library. It processes the webcam input to detect hand landmarks and determine whether the hand is closed.


Contributions are welcome! Please follow these steps:

Fork the repository.

1. *Create your feature branch*
   ```bash
   git checkout -b feature/YourFeature

2. *Commit your changes*
   ```bash
   git commit -m 'Add your feature'

3. *push your changes*
   ```bash
   git push origin feature/YourFeature

4. open pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- Naga Bhargav - [Portfolio](https://github.com/BhargavNaga)
