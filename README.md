# 📘 Today-Pay Quiz App

A clean, user-friendly *Quiz Application* built with *React* as part of a frontend assignment to demonstrate state management, API integration, and responsive design.

---

# 🌐 Live Demo

🚀 Deployed on Vercel → [Click here to view](https://today-pay-quiz-peach.vercel.app/)

## 🚀 Objective

The goal of this project is to create an interactive Quiz App that:

* Presents one question at a time with multiple-choice options.
* Tracks user progress and score.
* Displays detailed results with correct/incorrect answers.
* Offers a smooth, responsive UI/UX with timer per question.

---

## 🖼 Screenshots & Folder Structure

### Screenshots

| Welcome Page | Quiz Page | Results Page |
| ------------ | --------- | ------------ |
| ![Welcome](https://github.com/poojasingh2429/Today-Pay-Quiz/blob/main/src/components/public/Screenshot%202025-09-04%20204029.png) | ![Quiz](https://github.com/poojasingh2429/Today-Pay-Quiz/blob/main/src/components/public/Screenshot%202025-09-04%20204146.png) | ![Results](https://github.com/poojasingh2429/Today-Pay-Quiz/blob/main/src/components/public/Screenshot%202025-09-04%20204253.png) |

### Folder Structure

oday-Pay-Quiz/
├── public/
├── src/
│ ├── components/
│ │ ├── Quiz.js
│ │ ├── Question.js
│ │ ├── Results.js
│ │ └── Welcome.js
│ ├── App.js
│ └── index.js
└── package.json


---

## ✨ Features

### UI/UX

* Clean, mobile-first responsive design.
* Prominent navigation buttons: Next, Previous/Skip, Finish.
* Progress bar showing current question out of total.
* Timer for each question.

### Core Functionality

* Fetches 10 multiple-choice questions from Open Trivia DB API.
* Render one question at a time with 4 options.
* Tracks user score and selected answers.
* Shows detailed results at the end with correct/incorrect answers.
* Restart Quiz option.

### Bonus

* Persistent high score using localStorage.
* Smooth animations & transitions with Framer Motion.
* Accessibility support (keyboard navigation, ARIA labels).

---

## 🛠 Tech Stack

* React (Functional Components + Hooks)
* Bootstrap 5 for styling
* Framer Motion for animations
* Open Trivia DB API for questions

---

## ⚙ Installation & Setup

Clone the repository and run the following commands:

```bash
# Clone repo
git clone https://github.com/poojasingh2429/Today-Pay-Quiz.git

# Navigate into folder
cd Today-Pay-Quiz

# Install dependencies
npm install

# Start development server
npm start

🎮 Usage

Click Start Quiz on the welcome screen.

Answer each question or click Skip.

View your final score and detailed results.

Click Restart Quiz to play again.

🧪 Testing & Edge Cases

Handles no internet or API failure gracefully.

Prevents progress without selecting an answer (unless skipped).

Supports rapid clicks and page refreshes.

Verified on mobile, tablet, and desktop views.

🤝 Contribution

Contributions, issues, and feature requests are welcome:

Fork the repo

Create a new branch (git checkout -b feature-branch)

Commit your changes (git commit -m 'Add new feature')

Push to the branch (git push origin feature-branch)

Open a Pull Request
