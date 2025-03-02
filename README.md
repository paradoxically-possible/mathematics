# Interactive Math Quiz

An interactive web-based math quiz application featuring modern design and dynamic user settings. This app comes with dynamic themes, multiple difficulty levels including an adaptive mode, and a comprehensive selection of mathematical operations.

## Main Features

🎨 **Dynamic Theme & Modern Design**  
- Modern design using CSS Variables for dynamic theming  
- Header with gradient effects and engaging icons

📊 **Difficulty Levels & Adaptive Mode**  
- Three levels: Easy, Normal, and Hard  
- Automatically adjusted number ranges based on the selected difficulty  
- **Adaptive Quiz**: An adaptive mode that analyzes past performance and adjusts operation selection to help improve your skills

🔢 **Mathematical Operations**  
- Addition (+)  
- Subtraction (-)  
- Multiplication (×)  
- Division (÷) with special validation for quotient & remainder  
- Exponentiation (^)  
- **Percentage (%)**

⏱️ **Timer Challenge Mode**  
- Optional timer mode with adjustable question duration (5–60 seconds, default 30 seconds)  
- Visual warnings via progress bar color changes as time runs low

✅ **Instant Answer Validation & Feedback**  
- Real-time answer checking  
- Visual effects (e.g., shake animation) on invalid inputs  
- Specific handling for division questions and tolerance for percentage calculations

📈 **Interactive Results & Detailed Statistics**  
- Final results display with score and detailed statistics  
- Performance charts using Chart.js showing time per question and accuracy  
- Adaptive feedback based on your performance with celebratory confetti animations for high scores

📱 **Responsive & User-Friendly Settings**  
- Mobile-friendly design compatible with various screen sizes  
- Save user preferences and quiz history using localStorage

## How to Use

1. **Configure Quiz Settings**  
   - Select the mathematical operations (including Percentage)  
   - Set the number ranges for questions and the exponent value  
   - Choose the number of questions  
   - Enable *Timer Challenge Mode* if desired, and adjust the time per question  
   - Click the **Start Quiz** button

2. **Answer the Questions**  
   - Enter your answer in the input field (for division, provide both quotient and remainder separately)  
   - Press Enter or click the **Submit Answer** button  
   - If the timer mode is active, keep an eye on the progress bar and time warnings

3. **View Results & Try Adaptive Mode**  
   - Upon completion, view your results including performance charts, statistics (average time, accuracy, fastest answer, etc.), and adaptive feedback  
   - Click **New Quiz** to try again or **Try Adaptive Quiz** to start a quiz with settings adjusted based on your previous performance

## Technologies Used

- **HTML5** – Modern web page structure  
- **Vanilla JavaScript** – Core application logic and interactivity  
- **Custom CSS & CSS Variables** – Responsive design and dynamic theming  
- **Chart.js** – Visualization of performance charts  
- **Font Awesome 6** – Supporting icons for enhanced UI

## Installation

1. Clone the repository or download the ZIP file:
   ```bash
   git clone https://github.com/paradoxically-possible/mathematics.git
