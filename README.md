# ADHD Adventure: A Hands_Free Educational Game

## Overview
This project is a **voice-free ADHD game** developed using Unity. It allows players to control a character and interact with game elements via **voice commands** (implemented using AWS – Amazon Web Services). The gameplay includes two main mechanics: controlling a character's jump and answering multiple-choice questions by selecting correct answers. It aims to engage ADHD students through interactive and educational experiences in a hands-free method.

![gameplay](https://github.com/user-attachments/assets/52cdbe78-0775-4cab-874e-d33545449006)


## Game Features
1. **Character Control:**
   - The player can make the character jump by issuing the "Jump" command via voice (or by pressing the Space key).
   - The character’s jump mechanics are handled through a Rigidbody2D component.

2. **Question System:**
   - The game asks multiple-choice questions with two answer options.
   - Players select answers by issuing voice commands corresponding to the correct or incorrect answers.
   - Questions cover various topics, such as geography, math, and general knowledge.
   - Feedback is provided based on the player's choice (correct or incorrect).

3. **Score and Feedback:**
   - The score updates based on correct answers.
   - A feedback system displays "Correct" or "Incorrect" after each question.
   - A summary is shown after every two correct answers, displaying the player's performance so far.
   - An end-game results screen displays the final score and performance after all questions have been answered.

![starting meny](https://github.com/user-attachments/assets/e7c39c8e-4f61-4f85-b68a-1810158d3196)


## Game Mechanics
- **Jumping:**
  - The player makes the character jump by pressing the Space key or saying "Jump."
  - The jump force can be modified using the `jumpForce` variable.
  
- **Question Answering:**
  - A question is presented, followed by two answer tiles that appear after a delay.
  - The player selects the answer by issuing voice commands that match the answer text.
  - Correct and incorrect answers are tracked, and a summary is shown periodically.

![gameplay2](https://github.com/user-attachments/assets/903f3c39-8fe1-4836-97fb-de573870a48d)


## Installation and Setup
1. **Unity Version:** Unity 2019.4.15f1 or later.
2. **Required Assets:**
   - **TextMeshPro** for displaying questions and answers.
   - **Rigidbody2D** for player movement.
   - **WAS (Word as a Service)** for voice command processing (not included in the repo).
3. **Project Files:**
   - `PlayerScript.cs` handles character jumping.
   - `QuestionManager.cs` manages questions, answers, scoring, and feedback.

![scoreboard](https://github.com/user-attachments/assets/b424d208-9477-4704-8ec6-c5c3c1d1fb66)


## How to Play
1. **Start the Game:**
   - The game begins by showing the first question after the character appears on the screen.
2. **Jumping:**
   - Press the **Space** key or say "Jump" to make the character jump over obstacles.
3. **Answering Questions:**
   - Say the correct answer or select it using your voice to move on to the next question.
4. **Game Progress:**
   - The game provides feedback after each answer.
   - A summary is shown after every two correct answers.

![gameplay3](https://github.com/user-attachments/assets/5c5641a1-250e-468b-9b5d-8cbbd8730be1)


## Future Improvements
- Adding more complex voice commands for interaction.
- Adding more in-game interactions like enemies and obstacles.
- Introducing new levels with increasing difficulty.
- Additional educational content for enhanced learning.



