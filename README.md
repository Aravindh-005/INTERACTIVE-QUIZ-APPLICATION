# INTERACTIVE-QUIZ-APPLICATION

**COMPANY : CODTECH IT SOLUTION**

**NAME : Aravindh s**

**INTERN ID : CT08RKL**

**DOMAIN : FRONT END DEVELOPMENT**

**DURATION : 4 WEEKS**

**MENTOR : NEELA SANTOSH**

##The HTML-based Interactive Quiz Application is a web-based quiz tool designed to deliver a fun and engaging user experience. It combines the simplicity of HTML, CSS, and JavaScript to create an interactive platform where users can participate in a multiple-choice quiz, answering questions with a time constraint, and receive instant feedback. Let’s break down the different aspects of the program.

**Overview of the Quiz Application**
This program is a simple yet efficient quiz application where users are presented with multiple-choice questions and are required to select the correct answer within a set amount of time (10 seconds). The application consists of four main components:

HTML Structure: Provides the layout and structure for the quiz.

CSS Styling: Ensures the quiz is visually appealing with a clean and modern design.

JavaScript Functionality: Implements the core logic, such as timers, answer submission, and score tracking.

**Detailed Breakdown of the Code**
**1. HTML Structure**
The HTML provides the framework for the quiz. It contains:

A container (question-container) that houses the question, options, timer, and button elements.
A <h2> tag to display the current question.
A <div> element for displaying the countdown timer (starting from 10 seconds).
Four <div> elements representing multiple-choice options, each with an onclick event to register the user's selection.
A button that allows the user to proceed to the next question. The button is initially disabled and becomes active only when the user selects an answer or when the timer runs out.

**2. CSS Styling**
The styling uses simple, modern design principles to make the quiz visually appealing:

The body tag is styled with a clean background color and padding to center the quiz content.
The question-container div has a white background with rounded corners, padding, and a subtle shadow to make it stand out against the background.
The .options and .option classes are styled to display the answer choices as clickable buttons. These options change color when hovered over to indicate interactivity.
The .timer class is used to display the countdown timer prominently at the top of the screen, showing the remaining time for each question.

**3. JavaScript Functionality**
JavaScript is the backbone of this quiz application, implementing all the logic behind the scenes. The primary features handled by JavaScript include:

Question Management: The questions array stores all the questions, options, and answers. The displayQuestion() function dynamically updates the content of the quiz based on the current question index.
Timer: Each question has a 10-second timer implemented through the startTimer() function. The timer starts at 10 seconds for every new question, and every second the time is decremented. When the timer reaches zero, the submitAnswer() function is automatically triggered, submitting the current answer regardless of whether the user selected it or not.
Answer Selection: The selectAnswer() function is called when the user clicks on an answer option. It checks if the selected answer matches the correct answer for that question and updates the score.
Navigation: The nextQuestion() function increments the currentQuestionIndex to load the next question. If the quiz is completed, the endQuiz() function is triggered, displaying the final score in a pop-up.
Button Enablement: The "Next Question" button is disabled until an answer is selected or the timer runs out, ensuring users cannot skip questions without interacting with them.

**4. Key Features of the Application**
Countdown Timer: Each question is accompanied by a 10-second countdown timer. This adds an element of urgency, making the quiz more exciting and engaging.
Immediate Feedback: After the user selects an answer, the program enables the "Next Question" button. However, if the timer runs out, the answer is automatically submitted.
Progression Through Questions: The user can only proceed to the next question after selecting an answer or when time expires.
Final Score: Once all questions are answered, the user is presented with a score that shows how many correct answers they got out of the total questions.

**6. Enhancements and Extensions**
While this quiz application is functional, several enhancements can be made:

Adding More Questions: The number of questions can be increased to offer more variety.
Sound Effects: Audio cues can be added to alert users when time is about to run out or when they answer correctly/incorrectly.
User Input: User names can be inputted to track scores across multiple sessions.
Styling Improvements: More advanced CSS or animations can be added to make the quiz more dynamic.

**Conclusion**
This Interactive Quiz Application is a simple, effective solution for delivering timed quizzes with automatic score tracking. Using basic web technologies like HTML, CSS, and JavaScript, the program demonstrates how to create an engaging, interactive experience with minimal code. The timer feature, instant feedback, and score tracking provide a satisfying and challenging quiz experience for users. Future improvements could further enhance the functionality and design, making it a more robust application for different quiz use cases.##

**output**

![Image](https://github.com/user-attachments/assets/8a7f22bc-d8e0-4be4-8433-55ed8487b100)
