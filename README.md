# Hand-Controlled Circle Catcher Game

Welcome to the Hand-Controlled Circle Catcher Game! This interactive game uses computer vision and hand tracking to create an engaging experience where you try to catch colored circles with your hand. It's a fun project that combines OpenCV, MediaPipe, and PyAutoGUI to bring the game to life.

## Features

- **Hand Tracking:** The game uses MediaPipe to detect and track your hand movements in real-time.
- **Dynamic Gameplay:** Colored circles fall from the top of the screen, and you control a red circle with your hand to catch them.
- **Scoring System:** Different colored circles have different point values, and your goal is to achieve the highest score possible.
- **Win or Lose:** The game provides feedback on whether you've won or lost based on your score.
- **Customization:** You can easily adjust game parameters like circle speed, colors, and scoring criteria to tailor the game to your preferences.

## Getting Started

1. **Prerequisites:** Make sure you have Python and the required libraries (OpenCV, NumPy, PyAutoGUI, and MediaPipe) installed on your system. You can install them using `pip`.

   ```bash
   pip install opencv-python numpy pyautogui mediapipe
   ```

2. **Clone the Repository:** Clone this repository to your local machine.

   ```bash
   git clone https://github.com/abdul-rehman18/Game-using-Hand-Gesture-Virtual-Mouse-in-Python-using-OpenCv-Mediapipe-Pyautogui.git
   ```

3. **Run the Game:** Open a terminal in the project directory and run the game.

   ```bash
   python game.py
   ```

4. **Play the Game:** Use your hand to control the red circle and try to catch the falling circles. The game keeps track of your score.

## Customization

You can customize various aspects of the game to suit your preferences:

- Adjust the game difficulty by changing parameters like circle speed and scoring criteria.
- Modify the colors of the falling circles by editing the `colors` list in the `game.py` file.
- Experiment with different hand gestures and tracking by exploring the MediaPipe documentation.

## Contributions

Contributions are welcome! If you have ideas for improvements or new features, feel free to open an issue or create a pull request.

## Acknowledgments

- Special thanks to the [MediaPipe](https://mediapipe.dev/) and [OpenCV](https://opencv.org/) teams for their amazing libraries.
- Inspired by the fun of combining computer vision and gaming.

Have a blast playing the Hand-Controlled Circle Catcher Game! 🕹🎉
