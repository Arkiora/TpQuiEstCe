# Qui est-ce ? (Guess Who) Project
This project is a digital version of the classic "**Guess Who?**" game, implemented using **PHP**, **HTML**, and **CSS**. The goal of the game is to guess the correct character based on a series of yes/no questions. The project also includes an algorithm to detect inconsistencies in the answers, which can indicate if the player is lying.

## Features
- **Character Selection**: Players answer a series of questions to narrow down the possible characters.

- **Image Display**: Characters are displayed in a grid, and the correct character is highlighted when guessed.

- **Liar Detection**: An algorithm checks for inconsistencies in the answers to determine if the player is lying.

- **Interactive Interface**: A user-friendly form allows players to answer questions and submit their guesses.

## Technologies Used
- **PHP**: Handles the logic for processing answers and detecting lies.

- **HTML/CSS**: Provides the structure and styling for the game interface.

- **Images**: Character images are used to represent the different options in the game.

## How to Run the Code
1. **Set Up the Environment**:
    - Import the project folder into the `../xampp/htdocs/` directory.
    - Start **XAMPP** and ensure **Apache** and **MySQL** are running.

2. **Run the Application**:
    - Open `localhost/TpQuiEstCe/index.php` in your browser.
    - You will see the main interface where you can play the game.

## How It Works
1. **Answer Questions**: Players answer a series of yes/no questions about the character they are trying to guess.

2. **Submit Answers**: The answers are processed by the PHP script, which calculates a binary signature based on the responses.

3. **Liar Detection**: The script checks for inconsistencies in the answers using a syndrome-based algorithm. If inconsistencies are found, the script identifies which question was likely lied about.

4. **Display Result**: If no lies are detected, the correct character is highlighted in the grid of images.

## Project Structure
- **index.php**: The main game interface where players answer questions and view the character grid.

- **algo.php**: Contains the algorithm for detecting lies based on the answers provided.

- **post.php**: Processes the form submission and checks for inconsistencies in the answers.

- **style.css**: Provides the styling for the game interface.

- **images/**: Contains the character images used in the game.

## Example Usage
**Playing the Game**
1. Open index.php in your browser.

2. Answer the questions about the character (e.g., "Does he have glasses?", "Does he have a mustache?").

3. Submit the form to see if you guessed the correct character or if any lies were detected.

**Detecting Lies**
- If the player lies in their answers, the algorithm will detect the inconsistency and identify which question was likely lied about.

- If no lies are detected, the correct character will be highlighted in the grid.

## About This Project
This project was developed as a fun and interactive way to learn PHP and web development. It combines game logic with a simple algorithm for detecting inconsistencies, making it both educational and entertaining. The game is inspired by the classic "Guess Who?" board game, with a digital twist.