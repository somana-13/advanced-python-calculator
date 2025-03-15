# Advanced Python Calculator
Calculator Project

Overview

This project is a simple Python-based calculator that lets you perform basic arithmetic and statistical operations through an interactive command-line interface. It features a calculation history that persists between sessions, the ability to edit previous entries, and support for plugins to extend its functionality.

Features

Arithmetic Operations: Easily perform addition, subtraction, multiplication, and division.
Statistical Operations: Easily perform mean, median, mode and variance.
Calculation History: Every calculation is recorded with a timestamp. You can view, clear, or edit your history.
Plugin Support: Extend the calculator’s capabilities by adding custom plugins.
Persistence: Your calculation history is saved automatically when you exit and loaded when you start again.
User-Friendly REPL: A clear command-line interface that shows available commands and usage instructions.
Demo Video Link

This the link to my demo video link - Demo Video
Create and Activate a Virtual Environment

On Linux/Mac:

python3 -m venv venv

source venv/bin/activate

On Windows:

python -m venv venv

venv\Scripts\activate

Usage

To start the calculator, run:
python main.py
When the calculator starts, you'll see a welcome message with a list of commands. - Here are a few examples: Basic Operations
add 5 7 - Adds 5 and 7.
subtract 99 76 - Subtracts 76 from 99.
multiply 84 364 - Multiplies 84 by 364.
divide 875 35 - Divides 875 by 35 (also shows an error if division by zero is attempted).
sqrt 49 - Gives the square root of 49.
mean 978 348 479 987 - Gives average of these numbers.
square 6 - Gives the square of 6.
History Management:

history – Displays all past calculations.
clear_history – Clears the calculation history.
edit_history <record_index> <command> <arg1> <arg2> – Edits a specific history record.
Plugin Commands:

plugins – Lists any available plugin commands.
Help and Exit:

help – Displays the help message.
exit – Saves the history and exits the calculator.
Testing

To run the test suite (including linting and coverage reports), execute:
pytest --pylint --cov
This command will run all tests and display the coverage percentage.
Continuous Integration

The project includes a GitHub Actions workflow that automatically runs tests on each push and pull request. The CI configuration is located in .github/workflows/python-app.yml.paraphrase the above text
Calculator Project Overview

This project is a Python-based calculator designed to perform basic arithmetic and statistical operations through an interactive command-line interface. It includes features like persistent calculation history, the ability to edit past entries, and plugin support for extending functionality.

Key Features

Arithmetic Operations: Perform addition, subtraction, multiplication, and division.
Statistical Operations: Calculate mean, median, mode, and variance.
Calculation History: All calculations are logged with timestamps. Users can view, clear, or edit the history.
Plugin Support: Enhance the calculator’s capabilities by integrating custom plugins.
Persistence: Calculation history is automatically saved upon exiting and reloaded when the calculator restarts.
User-Friendly REPL: A straightforward command-line interface displays available commands and usage instructions.


Setup Instructions

Create and Activate a Virtual Environment:
Linux/Mac:
bash
Copy
python3 -m venv venv
source venv/bin/activate
Windows:
bash
Copy
python -m venv venv
venv\Scripts\activate
Usage

To start the calculator, run:

bash
Copy
python main.py
Upon launching, a welcome message will appear, listing available commands. Below are some examples:

Basic Operations:

add 5 7 – Adds 5 and 7.
subtract 99 76 – Subtracts 76 from 99.
multiply 84 364 – Multiplies 84 by 364.
divide 875 35 – Divides 875 by 35 (shows an error if division by zero is attempted).
sqrt 49 – Computes the square root of 49.
mean 978 348 479 987 – Calculates the average of the given numbers.
square 6 – Computes the square of 6.
History Management:

history – Displays all past calculations.
clear_history – Clears the calculation history.
edit_history <record_index> <command> <arg1> <arg2> – Edits a specific history record.
Plugin Commands:

plugins – Lists available plugin commands.
Help and Exit:

help – Displays the help message.
exit – Saves the history and exits the calculator.
Testing

To run the test suite (including linting and coverage reports), execute:

bash
Copy
pytest --pylint --cov
This command runs all tests and displays the coverage percentage.

Continuous Integration

The project includes a GitHub Actions workflow that automatically runs tests on every push and pull request. The CI configuration is located in .github/workflows/python-app.yml.

This project combines functionality, ease of use, and extensibility, making it a versatile tool for both basic and advanced calculations. 
