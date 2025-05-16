# HTML Quiz

A responsive, interactive quiz web application built entirely with HTML, CSS, and JavaScript. This project demonstrates how to create a multiple-choice quiz with instant feedback, navigation controls, and a clean, modern UI—all in a single HTML file.

## Features

- **Multiple-choice questions**: Supports both single and multiple correct answers.
- **Responsive design**: Works on all devices, including mobile.
- **Navigation controls**: "Previous," "Next," and "Submit" buttons let users move between questions.
- **Live scoring**: Users see their total score after submitting the quiz.
- **Highlight selections**: Selected options are visually distinct.
- **Pure frontend**: No backend required; everything runs in the browser.

## Usage

1. Clone or download this repository.
2. Open `quiz.html` in your web browser.
3. Select answers for each question, use navigation buttons to review or change your answers.
4. Click **Submit** on the last question to see your score.

## Customization

To add or modify questions:
- Edit the `questions` array in the `<script>` section of `quiz.html`.
    - Each question has a `question` (string), `options` (array of strings), and `answer` (array of correct option indices).

Example:
```js
{
  "question": "What does HTML stand for?",
  "options": ["Hypertext Markup Language", "High-Level Text Markup Language", "Hyperlink and Text Markup Language", "Hypertext Machine Language"],
  "answer": [0]
}
```
To allow multiple correct answers, include multiple indices in the `answer` array.

## File Structure

- `quiz.html` – All code (HTML, CSS, JS) is contained within this single file.

## Demo

Open `quiz.html` in your browser to try the quiz!

## License

MIT
