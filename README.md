# OI_internship

## Task01: Weather App

<p>This repository includes two versions of a weather application:

### Basic Version:
Description: A command-line tool for retrieving weather information based on user input (city name).
Functionality: Fetches current weather data from the OpenWeatherMap API and displays city name, temperature, humidity, and weather description.
How to Use: Run the script in a terminal, enter a city name, and receive weather details.

### Advanced Version:
Description: A graphical user interface (GUI) application using tkinter that displays weather information and icons.

Functionality:
Allows users to enter a city name and view current weather conditions with an associated weather icon.
Retrieves weather data and displays it within the GUI.
Features:
GUI for user-friendly interaction.
Displays weather icons fetched from the OpenWeatherMap API.
How to Use: Run the script to open the GUI, enter a city name, and click "Search" to view the weather details and icon.
Technologies Used:

Python standard libraries: requests
Advanced version: tkinter for GUI, PIL (Pillow) for image handling
Notes:

The basic version provides quick weather updates from the command line.
The advanced version enhances user experience with a graphical interface and visual weather representation.<p/>

## Task02: Random Password Generator

This repository contains two versions of a random password generator:

### Basic Version:
Description: A command-line tool for generating a random password based on user-defined criteria.
Functionality: Prompts the user to input password length and whether to include uppercase letters, lowercase letters, numbers, and symbols.
How to Use: Run the script in a terminal, follow the prompts to configure the password parameters, and receive the generated password.

### Advanced Version:
Description: A graphical user interface (GUI) application using tkinter for generating random passwords.

Functionality:
Allows users to specify password length and select character types via checkboxes.
Displays the generated password in the GUI.

Features:
GUI for easy configuration and result display.
Provides interactive elements like checkboxes for character type selection.
How to Use: Run the script to open the GUI, enter the desired password length, select the character types, and click "Generate Password" to view the result.

Technologies Used:
Python standard libraries: random, string
Basic version: No additional libraries required
Advanced version: tkinter for GUI

Notes:
The basic version is suitable for quick password generation from the command line.
The advanced version offers a user-friendly interface with customizable options.

## Task03: BMI Calculator

This repository contains two versions of a BMI calculator:

### Basic Version:
Description: A command-line script for calculating Body Mass Index (BMI) based on user input for weight and height.
Functionality: Prompts the user to input weight and height, calculates BMI, and classifies it into categories (Underweight, Normal weight, Overweight, Obese).
How to Use: Run the script in a terminal or command prompt, enter the required values when prompted.

### Advanced Version:
Description: A graphical user interface (GUI) application using tkinter with a database backend.

Functionality:
Allows users to enter their name, weight, and height through a GUI.
Calculates BMI and classifies it.
Saves the BMI record in an in-memory SQLite database.
Displays the result and classification in a message box.

Features:
GUI for easier data entry.
Database integration for storing BMI records.
How to Use: Run the script to open the GUI, fill in the fields, and click "Submit" to calculate and save the BMI information.

Technologies Used:
Python standard libraries: tkinter, sqlite3
Basic version: No additional libraries required
Advanced version: tkinter for GUI, sqlite3 for database

Notes:
The basic version is suitable for quick calculations from the command line.
The advanced version provides a user-friendly interface and data storage capabilities.
