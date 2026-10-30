# Quick Knowledge Quiz

A simple, responsive multiple-choice quiz built with **HTML, CSS, and vanilla JavaScript**. It features a clean blue-and-white interface, instant answer feedback, a progress bar, score tracking, and a results screen.

## Preview

Open `index.html` in your browser to try the quiz.

## Features

- 8 general knowledge multiple-choice questions
- Instant feedback after selecting an answer
- Correct answers highlighted in green and incorrect selections in red
- Score updates as you progress
- Progress bar showing quiz completion
- Results screen with a performance message
- Restart button to play again
- Responsive layout for desktop and mobile screens
- No frameworks, libraries, or build tools required

## Built With

- **HTML5** — page structure
- **CSS3** — styling, layout, and responsive design
- **JavaScript** — quiz logic, answer checking, scoring, and navigation

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/quick-knowledge-quiz.git
```

### 2. Open the project folder

```bash
cd quick-knowledge-quiz
```

### 3. Run the quiz

Open `index.html` in your browser.

You can also use the **Live Server** extension in Visual Studio Code.

## Project Structure

```text
quick-knowledge-quiz/
└── index.html
```

The project is contained in a single HTML file. It includes the markup, CSS styles, quiz questions, and JavaScript functionality.

## Customization

### Change the questions

In `index.html`, find the `questions` array in the `<script>` section. Each question has:

- `question` — the question text
- `options` — an array of four answer choices
- `answer` — the zero-based index of the correct option
- `fact` — the explanation shown after an answer is selected

Example:

```javascript
{
  question: "Which planet is known as the Red Planet?",
  options: ["Venus", "Mars", "Jupiter", "Mercury"],
  answer: 1,
  fact: "Mars looks reddish because iron-rich dust covers much of its surface."
}
```

Remember that `answer` starts at `0`: the first option is `0`, the second is `1`, and so on.

### Change the theme

Edit the CSS variables inside the `:root` selector near the top of the `<style>` section to update the background, text, borders, and accent colors.

## How It Works

1. The quiz displays one question and its answer choices.
2. Selecting an answer locks the choices and shows feedback.
3. The score increases when the selected answer is correct.
4. Select **Next question** to continue.
5. After the final question, the results screen displays the total score.
6. Select **Try again** to restart the quiz.

## Contributing

Contributions and suggestions are welcome. Feel free to fork the repository, make improvements, and open a pull request.

## License

This project is available under the [MIT License](https://opensource.org/licenses/MIT). If you use this license, add a `LICENSE` file to the repository.

---

Made with HTML, CSS, and JavaScript.

Run
Open index.html in a browser.
Live link:https://vercel.com/vaibhav-8cd0/quiz-app
Author: Vaibhav Gupta
