# ⏱️ React Stopwatch App

A sleek, minimal stopwatch built with **React** — complete with start, stop, reset, and lap tracking functionality.

![React Stopwatch](https://img.shields.io/badge/React-Stopwatch-blue)  
Made with ❤️ by Rajat

---

## 🖼️ Live Demo

https://stopwatch-tawny-three.vercel.app/

---

## ⚙️ Features

- 🟢 Start / ⛔ Stop the stopwatch
- 🔁 Reset timer
- 🏁 Save multiple lap timestamps
- ⏰ Time display in `hh:mm:ss` format
- Responsive and styled using Tailwind CSS
- Uses **React Hooks**: `useState`, `useEffect`

---

## 📦 Tech Stack

| Tech         | Description         |
|--------------|----------------------|
| React        | Frontend framework |
| Tailwind CSS | Styling            |
| React Icons  | For the alarm clock icon (FcAlarmClock) |

---

## 🧠 How It Works

### 🔁 Timer Logic

- The `timeInSec` state tracks the total seconds.
- `useEffect()` sets up a `setInterval` when the stopwatch is running (`toggle` is true).
- Time updates every second until stopped.
- Time is converted to `HH:MM:SS` format using `padStart()` for consistent UI.

### 🏁 Getting Started

```js

## How to Start
git clone https://github.com/your-username/react-stopwatch.git
npm install
npm run dev

##Project Structure
src/
├── Components/
│   └── Header.jsx     # Contains stopwatch UI and logic
├── App.jsx
├── main.jsx
└── index.css

