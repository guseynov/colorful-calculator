# Calculator

A keyboard-friendly calculator built with React, Redux, and `big.js` for reliable arithmetic and cleaner number formatting.

## Features

- Basic operations: add, subtract, multiply, and divide
- Keyboard support for digits, operators, `Enter`, `Backspace`, `Esc`, and `C`
- Clear and delete-last-digit controls
- Randomized color palettes
- Responsive layout with a live display for the current expression and result

## Live Demo

- https://guseynov.github.io/projects/calculator/

## Getting Started

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Run the test runner

```bash
npm test
```

### Build for production

```bash
npm run build
```

## Keyboard Shortcuts

- `0-9` for digits
- `.` for decimal input
- `+`, `-`, `*`, `/` for operations
- `=` or `Enter` to calculate
- `Backspace` to delete the last digit
- `Esc` or `C` to clear

## Tech Stack

- React
- Redux
- `big.js`
- `react-icons`
- `typeface-inter`

## Notes

- The app stores calculator state in Redux.
- Palette changes are randomized from the available theme set.
- Division by zero is handled as an error state in the display.
