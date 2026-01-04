# Quiz Game

A simple **Quiz Game** built using `HTML`, `CSS`, and `JavaScript`.

## Features
- Multiple-choice questions
- Score calculation
- Start & restart quiz
- Dynamic UI updates

## Run
Open `index.html` in your browser.

## Author
**Sanjeev**

## Project Structure
quiz-project/
│
├── index.html
├── style.css
├── script.js
└── README.md


The quiz logic is implemented inside script.js.

## How It Works

- The quiz starts after clicking the Start button.

- Questions and options are dynamically loaded.

- When a user selects an answer:

- The score increases if the answer is correct.

- The Next button appears.

- After the last question, the final score is displayed.

- The Restart button resets the quiz.


## Code Overview

- DOMContentLoaded ensures the DOM is fully loaded before JavaScript runs.

- Questions are stored in an array of objects.

- Event listeners handle user interactions.

- Score is tracked and displayed at the end.
