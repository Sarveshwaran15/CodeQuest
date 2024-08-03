Project Description: Online Code Execution and Quiz Platform
Overview
The project is an integrated platform combining a code execution IDE with a quiz system. It enables users to solve programming problems, execute their code in various languages, and receive feedback on their solutions. The platform uses Flutter for the frontend and Node.js for the backend, leveraging the JDoodle API for code execution.

Features
Programming Quiz Interface:

Question List: Users are presented with a list of ten programming questions.
Question Selection: Clicking a question opens an interactive coding environment with a text editor.
Code Execution:

IDE Functionality: A built-in IDE allows users to write and submit code in multiple programming languages (Python, JavaScript, Java, C++, C).
Execution: Submitted code is executed using the JDoodle API, which provides results in real-time.
Code Saving: Users can save their code locally in text file format.
Scoring and Feedback:

Result Evaluation: The backend evaluates the output of the submitted code against predefined expected results.
Score Calculation: Users receive feedback on whether their code solves the problem correctly. Each question carries a score of 10 marks, contributing to a total score out of 100.
Completion Status: Questions are marked as "solved" if the output is correct, similar to platforms like LeetCode.
User Interaction:

Dropdown Menu: Users can select the programming language for the IDE from a dropdown menu.
Submit Button: Code can be submitted for execution, and users receive immediate feedback.
Submit Quiz: After solving all questions, users can submit their answers to see their total score.
Technologies Used
Frontend:

Flutter: Provides a responsive and interactive user interface. The app is designed to work on both mobile and web platforms.
Backend:

Node.js: Handles code execution requests and interactions with the JDoodle API.
JDoodle API: Used to execute code in different programming languages and return execution results.
Express: A web application framework for Node.js used to build the REST API.
CORS: Ensures secure communication between the frontend and backend.
Deployment:


How It Works
Initial Setup:

Users start by viewing a list of programming questions.
Each question can be opened to access the coding environment.
Coding and Execution:

Users write their code in the provided editor.
They select the language from a dropdown menu and submit their code.
The backend saves the code, executes it via JDoodle, and returns the output.
Feedback and Scoring:

The backend compares the output to predefined correct answers.
Questions are marked as solved if the output matches the expected result.
Scores are calculated based on the number of correctly solved questions.
Completion:

Once all questions are attempted, users can submit their quiz to receive a total score and feedback on their performance.
