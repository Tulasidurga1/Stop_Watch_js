# Stop_Watch_js
# Hosted Link:-https://tulasidurga1.github.io/Stop_Watch_js/
### HTML Structure:

### The HTML document defines the structure of the stopwatch web page. It consists of a timer display and three buttons.
### CSS Styling (style.css):

### The CSS code provides styles for the HTML elements. Here's a summary of the CSS classes and their styles:
- body: Sets the background color, font, and layout for the entire page.
- #timer: Styles the timer display, including font size, color, and text shadow.
- #buttons: Styles the button container.
- button: Styles the buttons, including background color, font size, padding, and hover effects.
- button[disabled]: Styles disabled buttons.
# JavaScript Functionality (index.js):

- The JavaScript code adds functionality to the stopwatch:
- It selects the timer element and the "Start," "Stop," and "Reset" buttons.
- It initializes variables for startTime, elapsedTime, and timerInterval.
- The startTimer function starts the stopwatch when the "Start" button is clicked. It calculates the elapsed time and updates the timer display every 10 milliseconds.
- The formatTime function converts the elapsed time into a formatted time string (HH:MM:SS.SS).
- The stopTimer function stops the stopwatch when the "Stop" button is clicked.
- The resetTimer function resets the stopwatch to zero when the "Reset" button is clicked.
- Event listeners are added to the buttons to trigger the corresponding functions when clicked.
### Usage:

- To use this stopwatch, you would include the HTML, CSS, and JavaScript files in the specified file paths ("style.css" and "index.js").
- When the page loads, the stopwatch display is set to "00:00:00," and the "Start" button is enabled.
- Clicking the "Start" button starts the stopwatch, and the button becomes disabled. The "Stop" button becomes enabled.
- Clicking the "Stop" button pauses the stopwatch, and the "Start" button becomes enabled again.
- Clicking the "Reset" button resets the stopwatch to zero, and the "Start" button becomes enabled.
- The stopwatch allows users to measure elapsed time accurately and conveniently. The CSS styles provide an appealing visual design, and the JavaScript logic ensures the stopwatch functions as expected.
