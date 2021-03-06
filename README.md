# Masturbation Prevention

This program was created at the request of a friend who had a bad habit. It is essentially a stopwatch with a few extra features. I used the Tkinter library for Python to create a graphical user interface.

![Preview screenshot](scr1.png "Preview screenshot")

Features include:
* A timer that counts up
    * Even when the program is not running!
* A button that resets the timer
* Dates and times listed to keep a record of every button press
* A scoring system to track current and high scores for encouragement
* An optional privileges list the user can write to disincentivize pressing the button
    * Calculates what the user is **NOT** allowed to do based off the score to high score ratio

When you first open `main.py`, a text file called `masturbation_prevention_info.txt` will be created in the same directory. The purpose of this file is to store data, similar to JSON or CSV files, but in a more readable way. This allows the program to keep track of the last time the stopwatch was reset and the high score while you can open and read through it.

Furthermore, you have the option of writing privileges to restrict and grant. This is controlled by how often you reset the stopwatch. In order to write privileges, open `masturbation_prevention_info.txt`, find the privileges section, and type out a list of privileges you would want restricted in the blank space above `privileges_end`. Separate each item in the list by a line feed. Privileges near the bottom and more restricted while privileges near the top are more lenient.

Examples of privileges include:
* Using your phone
* Playing video games
* Drinking alcohol

Make sure [Python](https://www.python.org/downloads/ "Download Python from www.python.org") is installed on your device before opening this file.

The purpose of this program is to demonstrate reading and writing to a file using Python. It shows basic competency for data analysis and simple algorithms.

## Credits

Alex Akoopie - Creator