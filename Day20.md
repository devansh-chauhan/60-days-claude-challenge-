# Day 20 — Face Puzzle Game with Webcam Integration

## Overview

For Day 20 of the 60 Days of Claude Challenge, I built an interactive **Face Puzzle Game** using Claude.

The application captures a photo using the device webcam and automatically converts it into a sliding puzzle game. Players can choose different difficulty levels and solve the puzzle while tracking their performance through timers, move counters, and leaderboard records.

---

## Objective

Create a complete browser-based puzzle game that:

- Uses webcam access to capture a live photo
- Splits the image into puzzle pieces
- Supports multiple difficulty levels
- Tracks moves and completion time
- Stores best scores locally
- Works on desktop and mobile devices

---

## Features Implemented

### 📸 Webcam Photo Capture
- Real-time camera access
- Capture custom image for puzzle generation
- Retake photo option

### 🧩 Puzzle Generation
- 3×3 Difficulty
- 4×4 Difficulty
- 5×5 Difficulty

### 🎮 Gameplay
- Drag and drop puzzle pieces
- Touch support for mobile devices
- Real-time move counter
- Live timer

### 🏆 Leaderboard
- Stores best completion times
- Tracks performance across attempts
- Difficulty-wise records

### 📱 Responsive Design
- Mobile-friendly interface
- Desktop support
- Smooth gameplay experience

---

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Webcam API
- Local Storage API
- Drag & Drop API

---

## Testing Performed

| Test Case | Status |
|------------|---------|
| Webcam Access | ✅ Passed |
| Image Capture | ✅ Passed |
| Puzzle Generation | ✅ Passed |
| 3×3 Difficulty | ✅ Passed |
| 4×4 Difficulty | ✅ Passed |
| 5×5 Difficulty | ✅ Passed |
| Drag & Drop | ✅ Passed |
| Touch Controls | ✅ Passed |
| Timer Functionality | ✅ Passed |
| Move Counter | ✅ Passed |
| Leaderboard Storage | ✅ Passed |
| Responsive Design | ✅ Passed |

---

## Screenshot

### Gameplay Preview

<img width="692" height="793" alt="Screenshot 2026-06-20 232324" src="https://github.com/user-attachments/assets/1fbd4822-6c50-4835-a16c-579064e42e12" />
<img width="636" height="816" alt="Screenshot 2026-06-20 232454" src="https://github.com/user-attachments/assets/523eab14-4e84-4b29-8e8e-29826f4e355f" />

[face_puzzle_game.html](https://github.com/user-attachments/files/29165341/face_puzzle_game.html)

---

## Key Learnings

- Learned how browser webcam APIs work.
- Implemented image slicing for puzzle creation.
- Explored drag-and-drop interactions in JavaScript.
- Used local storage for persistent leaderboard tracking.
- Improved responsive UI design skills.
- Understood game-state management concepts.

---

## Challenge Outcome

Successfully created a fully functional Face Puzzle Game that combines webcam capture, puzzle generation, real-time scoring, and responsive gameplay into a single web application.

---

