# Quiz Game

## Full Description

The Quiz Game project is an interactive Python script that tests the user's knowledge through a series of multiple-choice questions. The questions are sourced from a predefined list, and the game tracks the user's progress and score as they answer each question. The game continues until all questions have been answered, at which point the user's final score is displayed.

**Features:**
- **Dynamic Question Loading:** Questions and their correct answers are loaded dynamically from a data source and stored in a question bank.
- **Score Tracking:** The game keeps track of the user's score, updating it with each correct answer.
- **Interactive Gameplay:** Users are presented with one question at a time and receive immediate feedback on their answers.
- **Completion Message:** After the quiz is completed, the user is shown their final score along with a completion message.

**Note**: This project was inspired by Angela Yu's course on Udemy.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.

### How to Use

1. Clone or download the repository to your local machine.
2. Ensure you have the `question_model.py`, `data.py`, and `quiz_brain.py` modules in the same directory.
3. Run the script using Python:

   ```bash
   python quiz_game.py
   ```

4. The game will start by presenting questions one at a time. Enter your answer (True/False) for each question.
5. The game will provide feedback on whether your answer was correct and update your score accordingly.
6. Continue answering questions until the quiz is complete.
7. At the end of the quiz, your final score will be displayed.

### Customization

You can customize the Quiz Game by:
- **Adding More Questions:** Modify the `question_data` list in the `data.py` file to include more questions or different types of questions.
- **Changing the Question Format:** Adapt the `Question` class in `question_model.py` to handle different types of questions (e.g., multiple-choice).
- **Adjusting Feedback Messages:** Customize the feedback messages provided after each answer or at the end of the quiz.
