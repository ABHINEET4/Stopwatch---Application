# Coding-Ninjas---Front-End-Web-Development---Stopwatch
Create a stopwatch app. Use ONLY vanilla javascript, no libraries or frameworks allowed for Javascript (you can use any css framework like Bootstrap).

Hosted Website Link : https://abhineet4.github.io/Coding-Ninjas---Front-End-Web-Development---Stopwatch/

Stopwatch App
This is a simple Stopwatch App built with HTML, CSS, and JavaScript.

Usage
To use the Stopwatch App, follow these steps:

Clone the repository or download the HTML, CSS, and JavaScript files.
Open the index.html file in a web browser.
Features
The Stopwatch App includes the following features:

Start: Click the "Start" button to begin the stopwatch. The timer will start counting up from 00:00.
Stop: Click the "Stop" button to pause the stopwatch. The timer will stop counting.
Reset: Click the "Reset" button to reset the stopwatch. The timer will be set back to 00:00.
Styling
The app is styled using the provided styles.css file. The following styles have been applied:

The body has a sky blue background color and the content is center-aligned.
The stopwatch container has a burlywood background color, 5px border radius, and a box shadow effect.
The timer has a font size of 36px, bold font weight, and white color. It is displayed at the center of the stopwatch container.
The buttons are displayed in a row using flexbox. They have different background colors for Start (green), Stop (red), and Reset (yellow).
On hover, the buttons have an opacity of 0.8.
JavaScript Logic
The JavaScript code in script.js handles the functionality of the stopwatch. It includes the following functions:

startTimer(): Starts the timer by incrementing the seconds and updating the timer display every second.
stopTimer(): Stops the timer by clearing the interval.
resetTimer(): Resets the timer by stopping it and setting the minutes and seconds back to 0.
formatTime(minutes, seconds): Formats the time as "MM:SS" and returns the formatted string.
padZero(value): Pads a single-digit value with a leading zero if necessary.


License
This project is licensed under the MIT License.

Created by @Abhineet Kumar Mishra
