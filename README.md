# Verbiage
![Version](https://img.shields.io/badge/Version-1.0.0-lightgrey)  ![Python](https://img.shields.io/badge/Python-3.10%2B-lightgrey) ![License](https://img.shields.io/badge/License-MIT-lightgrey) ![Status](https://img.shields.io/badge/Status-Active-lightgrey)

A Python-based interactive CLI wordgame with a built-in dictionary definition feature.

## Features:
- Classic 5-letter Wordle inspired gameplay
- Grab definitions for any word via [freeDictionaryAPI](https://github.com/meetDeveloper/freeDictionaryAPI)
- Terminal output with color highlights from [Colorama](https://pypi.org/project/colorama/) and [Termcolor](https://pypi.org/project/termcolor/)
- Save game history and word definitions
- 4 game difficulties for both casual and expert players

## How To Play:
When the game begins, a random 5-letter word will be chosen:

![verbiage_game_start.png](https://github.com/langstonstewart/verbiage/blob/main/images/verbiage_game_start.png?raw=true)

You will have a certain amount of attempts to guess the word based on the selected difficulty.
Once you enter a guess, the gameboard will refresh and each letter of your guess will change:
- 🟩 GREEN 🟩 : The letter and position of letter are correct.
- 🟨 YELLOW 🟨 : The letter is correct, but not the position.
- ⬛ Gray ⬛: The letter is incorrect and not in the word.

![verbiage_game_start.png](https://github.com/langstonstewart/verbiage/blob/main/images/verbiage_game_win.png?raw=true)


Guess the word before the board fills up to win!

*This tool is currently only available for Windows.*

## How To Use (Installation):
#### 1. Install Python:
 In your preferred terminal, paste in the following code:

````
winget install Python
````
or install the latest version here:
https://www.python.org/downloads/

#### 2. Install the project folder:
Download the project folder via current release:
https://github.com/langstonstewart/verbiage/releases

### 3. Install Dependencies:
- [Tabulate by Sergey](https://pypi.org/project/tabulate/)
- [Colorama by tartley & wiggin15](https://pypi.org/project/colorama/)
- [Termcolor by hugovk](https://pypi.org/project/termcolor/)
- [Requests by Kenneth Reitz](https://pypi.org/project/requests/)

Install these dependencies with the command:
````
pip install colorama tabulate termcolor requests
````

## Getting Started:

Once you’ve installed everything, navigate to the project folder and run the BATCH file.
This should start the interactive CLI tool. 

Start a game of Verbiage and have fun!

## Contact:

If you encounter any issues or have questions, feel free to contact the maintainer at langston.professional08@gmail.com or open an issue on the GitHub repository.

## License:

This project is licensed under the MIT License – see the LICENSE file for details.
