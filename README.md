# numberquest
# 🎯 NumberQuest — Guess the Number

A fast, browser-based number guessing game built with plain HTML, CSS, and JavaScript. Pick a difficulty, guess the secret number, and watch the live range tracker shrink as you close in. Your best scores are saved automatically in your browser.

> Self-contained single-file web game — no build step, no dependencies, no backend.

## ✨ Features

- **Three difficulty levels**
  - Easy: 1–50
  - Normal: 1–100
  - Hard: 1–500
- **Live range tracker**: a progress bar and labels show the numbers still possible after each guess
- **Guess history**: every guess is listed with a "Too low", "Too high", or "Correct!" label
- **Scoreboard**: best score (fewest attempts) per difficulty, total games won, and current win streak
- **Persistent stats**: saved with `localStorage`, so they survive page refreshes
- **Sound effects**: tones for low, high, invalid input, and win, generated with the Web Audio API (can be toggled on/off)
- **How to Play** modal with quick instructions
- **Input validation** with clear feedback for out-of-range or empty guesses
- **Keyboard friendly**: press `Enter` to submit a guess
- **Responsive layout** that works on desktop and mobile
- **Accessible touches**: ARIA labels, live feedback region, and dialog roles

## 🕹️ How to Play

1. Choose a difficulty: Easy, Normal, or Hard.
2. Type a number and press **Enter** or click **Guess**.
3. Follow the hints ("Too low" / "Too high") and the shrinking range bar.
4. Guess correctly to win, then click **Play Again** to start a new round.
5. Try to beat your personal best in the fewest attempts!

## 🚀 Getting Started

### Run locally

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git

# 2. Open the project folder
cd <your-repo-name>

# 3. Open index.html in your browser
```

You can also just double-click `index.html`. No server or installation required.

### Deploy with GitHub Pages

1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and the `/ (root)` folder.
4. Click **Save**. Your game will be live at:
   `https://<your-username>.github.io/<your-repo-name>/`

It also deploys easily on Netlify or Vercel.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure and semantic markup |
| CSS3 | Styling, responsive grid layout, animations |
| Vanilla JavaScript (ES6) | Game logic and DOM updates |
| Web Audio API | Sound effects |
| localStorage | Saving best scores, wins, and streak |
| Google Fonts (Inter) | Typography |

## 📁 Project Structure

```
.
├── index.html    # Complete game: markup, styles, and scripts
└── README.md
```

## 💾 Data Storage

Stats are stored in your browser's `localStorage` under the key `numberquest_stats_v1`. Nothing is sent to a server. Use the **Reset Saved Stats** button in the scoreboard to clear them.

## 🔮 Ideas for Future Improvements

- Custom difficulty / user-defined range
- Limited-attempts challenge mode
- Dark mode
- Leaderboard with a backend
- Timer-based mode

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repo and open a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE). Add a `LICENSE` file to your repo if you'd like to use it.

## 👤 Author

**Your Name**
GitHub: [@vinayak288](https://github.com/vinayak288/numberquest.git)

---

⭐ If you enjoyed the game, consider giving the repo a star!
