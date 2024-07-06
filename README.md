<div align="center">
    <h1>QUIZ<b>DOM🧠</b></h1>
</div>
<div align="center">
	<img src="https://img.shields.io/badge/License-MIT-%230F2A5F" alt="license MIT">
</div>

## 🎓Overview

**QUIZDOM** is an all-inclusive web application designed for users of all types. Once logged in, users can create and join quizzes simply by sharing a unique quiz code. While many quiz-generating apps exist, QUIZDOM stands out by allowing quizzes to be created and taken on the same platform, making student evaluation straightforward and efficient. Teachers can create quizzes and control their accessibility, ensuring that only intended participants can join. When public access is enabled, a unique and secure quiz code is generated, which can be shared with students. This quiz code prevents anonymous entries and ensures only invited participants can take part. Additionally, teachers receive a detailed list of students and their scores for each quiz, simplifying the process of tracking and assessing student performance.

## ⏯ Preview

## 🚀 Configuration Guidelines

- Create an account on firebase.google.com and add the API key in the .env file.
- Add the MongoDB API key (either the local server key or from the Atlas MongoDB remote server) in backend/src/server.js.
- Install MongoDB Server if you want to use the database locally.
- Install Node.js to use npm and node services.
- Open a terminal with the path set to the root directory of the project and run `npm install` command to install the required packages.
- Open a new terminal with the path set to the backend directory of the project and run `npm install` command to install the required packages.
- After successful installation of all packages, run the command `npm start` in the terminal with the path set to the root directory and wait for the project to initiate.

## Blind Quiz Commands

- The Blind Quiz Module works with limited Speech Commands to interact with the App.
- Press `space` to turn the microphone on.
- Voice Commands:
  - `Instructions`: To listen to all the possible commands.
  - `start Quiz` or `title`: To hear the Quiz title and first Question.
  - `Select Option [Number]` or `Choose Option [Number]`: To mark the option of the current Question.
  - `next question`: to increment the question index and move to the next question and listen to it.
  - `previous question`: to decrement the question index and move to the previous question and listen to it.
  - `Repeat Question [Number]`: To hear a specific Question.
  - `Repeat Current Question`: To repeat the current Question.
  - `submit quiz`: to submit the quiz.
