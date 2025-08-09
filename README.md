## Introduction

Flash Cards is a **demo React application** built to demonstrate how simple interactivity, state management, and component rendering work in React. It’s designed as a small, easy-to-understand project for beginners who want to explore React fundamentals without the complexity of large frameworks or heavy styling libraries. In this demo, a grid of flashcards displays questions on the front and reveals answers on click, making it an engaging way to present study material. The project can serve as a **learning reference** for aspiring developers or as a base for creating more advanced study tools. Because of its clean and minimal structure, it’s straightforward to customize, extend, or integrate into other projects.

## How it works (brief)

- `questions` is an array of `{ id, question, answer }` objects.

- `FlashCards` stores `selectedId` in state to track the active card.

- Clicking a card toggles between question and answer.

- Conditional rendering and CSS classes manage the flipped/selected state.

## How to add / customize cards

Edit the `questions` array in `App.js`:

```js
const questions = [
  {
    id: 1001,
    question: "What is JSX?",
    answer: "A syntax extension for JavaScript used by React",
  },
  {
    id: 1002,
    question: "What hook gives components state?",
    answer: "useState",
  },
];
```

Ensure IDs are unique.

## 🌟 Features

- **Interactive Card Flipping**: Click on a card to reveal its answer and click again to flip back to the question — showcasing event handling in React.

- **Responsive Layout**: Uses CSS Grid to arrange cards in a responsive 3-column format (adjustable for various devices).

- **Minimal Dependencies**: Built only with React and CSS for simplicity and speed.

- **Customizable Content**: Flashcard data is stored in a single array for easy editing — no database or backend required.

- **Highlighted Selection**: The active card is styled differently to help demonstrate conditional rendering in React.

- **Beginner-Friendly Code**: Ideal for developers learning about state (`useState`), mapping arrays to components, and applying conditional classes.

## 🛠️ Tech stack

- **React** (functional components + hooks)
- **Plain CSS** for styling (`index.css`)
- Works with **Create React App or Vite**

## 📁 Project structure

```
/src
  ├─ App.js        # Main component and FlashCards component (cards data + logic)
  ├─ index.js      # React entry point
  └─ index.css     # Styles for layout + selected card state
```

## 🚀 Installation & run

```bash
# install dependencies
npm install

# start dev server
npm start

# build for production
npm run build
```

## 👨‍💻 Learnings

- Building interactivity with React hooks (`useState`).

- Rendering lists dynamically with `.map()`.

- Applying conditional styles based on state.

- Using CSS Grid for responsive layouts.

## 🤝 Contributions

Contributions are welcome!

If you’d like to improve the app, fix a bug, or add a new feature, follow these steps:

1. **Fork** the repository.

2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes and push to your fork.

4. Open a Pull Request describing your changes in detail.
