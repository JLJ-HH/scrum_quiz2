# Scrum PSM1 Quiz

A web-based interactive quiz application designed to help users prepare for the Professional Scrum Master I (PSM1) certification. It features a bilingual interface (German/English) and a dynamic question selection system.

## Features

- **Multi-language Support**: Toggle between German and English for the entire quiz interface and questions.
- **Customizable Question Count**: Choose how many questions to answer (from 1 up to 120).
- **Randomized Questions**: Questions are shuffled each time to ensure a fresh experience.
- **Timed Quiz**: Automatically calculates a time limit based on the number of questions (0.75 minutes per question).
- **Progress Tracking**: Real-time counter of answered questions.
- **Instant Result Evaluation**: Detailed score overview with a percentage breakdown.
- **Incorrect Answer Feedback**: Displays the correct answers for all questions answered wrongly to facilitate learning.
- **Responsive Design**: Clean and modern UI that works on both desktop and mobile devices.

## Technologies Used

- **HTML5**: Semantic structure for accessibility and SEO.
- **CSS3**: Modern styling with custom properties and responsive layout.
- **JavaScript (ES6+)**: Handles quiz logic, timer, state management, and DOM manipulation.
- **JSON**: Stores question data sets for different languages.

## Project Structure

- `index.html`: The main entry point and UI structure.
- `style.css`: All styling rules, including dark/modern aesthetic elements.
- `quiz.js`: The core logic for loading questions, managing the timer, and calculating results.
- `questions_de.json`: German question database.
- `questions_en.json`: English question database.

## How to Run

Simply open `index.html` in any modern web browser. No server setup or build process is required.

## Usage

1. Enter the desired number of questions.
2. Select your preferred language (**Deutsch** or **English**).
3. Answer the questions using the radio buttons.
4. Navigate using the **Next** and **Previous** buttons.
5. Click **Submit** (on the last page) to see your results.
6. Use the **Repeat Quiz** button to retake the quiz with the same settings.

## Autor

**José Luis Juárez** - Angehender Anwendungsentwickler aus Hamburg.

[Strato Portfolio](https://jljuarez.de/scrum-quiz/)
