🔍4-Digit Number Detective

A logic-based code-breaking game built with plain HTML, CSS and JavaScript. The computer picks a secret 4-digit number, and you crack it using deduction and positional clues.

---

✨ Features

- Three difficulty levels with different attempt and hint limits
- Instant feedback after every guess (correct digits and correct locations)
- Hint system with non-spoiler clues
- Guess history table so you can reason through earlier attempts
- Career statistics saved in your browser (best score, games won, success rate)
- Input validation with a shake animation on invalid guesses
- Confetti celebration when you win 🎉
- Responsive dark glassmorphism UI

---

🎮 How to Play

1. The game secretly generates a **4-digit number with unique digits**. The first digit is never 0.
2. Enter your guess and press **Check Answer**.
3. Use the two clues to narrow it down:
   - 🟢 **Correct Digits**: how many of your digits appear anywhere in the secret number
   - 🔵 **Correct Locations**: how many of those digits are also in the exact right position
4. Crack the code before you run out of attempts!

Example

Secret number: `5832`

| Guess | Correct Digits | Correct Locations |
|-------|----------------|-------------------|
| 2857  | 3              | 1                 |
| 5837  | 3              | 3                 |
| 5832  | 4              | 4 🎉              |

---

⚙️ Difficulty Levels

| Level  | Attempts | Hints |
|--------|----------|-------|
| Easy   | 15       | 5     |
| Medium | 10       | 3     |
| Hard   | 7        | 1     |

---

🛠️ Built With

- HTML5
- CSS3 (glassmorphism, animations)
- Vanilla JavaScript
- [canvas-confetti](https://github.com/catdad/canvas-confetti)
- Google Fonts (Outfit, Fira Code)

---
