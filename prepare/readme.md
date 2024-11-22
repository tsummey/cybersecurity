# Prepare Quiz App #

### Description ###

The Prepare Quiz App is a Python application designed to provide a structured and interactive quiz experience for learners preparing for various certifications, including cybersecurity and technical exams. It leverages the `Tkinter` library to create a visually appealing GUI, allowing users to select quizzes, answer questions, track progress, and review results in a seamless environment.

### Features ###

1. **Quiz Management**:
   - Load multiple quizzes from JSON files stored in a specified folder.
   - Supports dynamic quiz selection through a dropdown menu.

2. **Customizable Scoring System**:
   - Includes a default passing score, configurable in the JSON quiz file.
   - Displays real-time metrics like total questions, correct answers, incorrect answers, and the scaled score.

3. **Interactive Question Display**:
   - Handles multiple-choice questions with randomized answer options.
   - Highlights correct and incorrect answers for immediate feedback.

4. **Results and Retry Options**:
   - Displays detailed results at the end of the quiz.
   - Allows users to retry incorrect or unasked questions to reinforce learning.

5. **Error Handling and Feedback**:
   - Handles missing quiz files or unselected quizzes with error messages.
   - Ensures smooth user experience by validating inputs.

6. **GUI Features**:
   - Developed with `Tkinter` for a clean, responsive user interface.
   - Includes dynamic resizing to accommodate question text and answer options.

7. **Performance and State Management**:
   - Tracks progress, correct/incorrect answers, and scores persistently during a quiz session.
   - Automatically transitions between questions and handles end-of-quiz scenarios.

8. **Reset and Navigation**:
   - Provides options to reset the quiz or return to the welcome screen.
   - Ensures users can navigate seamlessly through the application.

### Installation and Setup ###

1. **Prerequisites**:
   - Python 3.8 or higher
   - Libraries: `tkinter`, `Pillow`, `json`, `random`

2. **Installation**:
   - Clone or download the repository.
   - Place JSON quiz files in the `quizzes` folder.

3. **Running the Application**:
   - Execute the script: `python prepare.py`

4. **Quiz Format**:
   - JSON files must include fields like `questions`, `choices`, `correct_answer`, and `domain`.
   - Each quiz can have custom passing scores and question categories.

5. **Stopping the Application**:
   - Close the Tkinter window to terminate the program.

### Usage ###

1. Launch the application.
2. Select a quiz from the dropdown menu.
3. Start the quiz and answer the questions.
4. Review the results and retry as needed.
5. Reset or navigate back to the welcome screen for new quizzes.

### Current Features ###

- Supports quizzes for certifications such as CISSP, CCSP, Security+, and more.
- Handles technical, scenario-based, and conceptual questions.
- Provides real-time performance tracking and feedback.

### License ###

This project is open-source and available under the MIT License.

