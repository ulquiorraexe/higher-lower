# Higher Lower Game

This is a simple web-based "Higher or Lower" game built using **Flask**. The game randomly selects a number between 0 and 9, and the player needs to guess it by visiting different URLs. After each guess, the app will tell the player whether the guess is too high, too low, or correct.

## Features

- A random number is generated between 0 and 9.
- Players can guess the number by visiting URLs with their guess in the path.
- After each guess, the game provides feedback: 
  - **Too high** if the guess is greater than the generated number.
  - **Too low** if the guess is less than the generated number.
  - **Correct** when the guess matches the number.

## Installation

To run the **Higher Lower Game** on your local machine, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/ulquiorraexe/higher-lower.git

2. Navigate to the project directory:

   ```bash
   cd higher-lower

3. Install the required dependencies:
   - Make sure you have Python 3.x installed.
   - Install Flask if you haven't already:
     ```bash
     pip install flask

4. Run the Flask app:

   ```bash
   python server.py

5. Open your browser and go to `http://127.0.0.1:5000/` to start playing the game.

## Usage

1. Go to `http://127.0.0.1:5000/` to start the game. You will see a message asking you to guess a number between 0 and 9.

2. Guess a number by adding it to the URL, for example: `http://127.0.0.1:5000/3`.

3. After each guess, the app will show feedback with a relevant GIF, indicating if your guess is too high, too low, or correct.

## Example URLs
- `http://127.0.0.1:5000/3` – Guess 3

- `http://127.0.0.1:5000/7` – Guess 7

## License

This project does not have a license.
