Dynamic Question Rendering: Supports three distinct types of questions:

Single-select: Classic multiple choice using radio buttons.

Multi-select: Allows multiple correct answers using checkboxes.

Fill-in-the-blanks: Text input validation.

Time Management: A 15-second countdown timer for each question to increase difficulty.

Progress Tracking: A visual progress bar that updates as you move through the quiz.

Responsive Design: Fully optimized for both desktop and mobile screens.

Result Summary: Displays a final score and a performance-based message.

⚙️ Technical Logic

State Management: The app uses a currentQuiz index to track progress through the data array.

Timer Logic: Utilizes setInterval() to handle the countdown, which is cleared and reset upon every new question or completion.

Validation: * For Multi-select, the app converts the selected array to a string to compare it against the correct answers.

For Fill-in-the-blanks, it uses .toLowerCase() and .trim() to ensure minor typing variations (like extra spaces) don't result in a wrong answer.
