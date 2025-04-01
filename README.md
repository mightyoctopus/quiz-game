## Program Architecture:

### [main.py](http://main.py)

Execution file that holds the major workflow of the app 

### [data.py](http://data.py)

Acts as a mock database, storing the question data used in the quiz.

### question_model.py

Defines the Question class, which serves as a blueprint for individual quiz questions, storing their text and correct answer.

### quiz_brain

This contains the core logic of the app such as:

- Asking the questions
- Checking if the answer is correct
- Checking if player gets the end of the quiz