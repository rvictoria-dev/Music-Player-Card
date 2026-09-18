# ♬♪  Music Player Card

### ₊⊹  About

A minimalist music player card inspired by a Pinterest pin. The goal of this project was to recreate a cute and modern design using only HTML and CSS.

<img width="1018" height="529" alt="image" src="https://github.com/user-attachments/assets/101e76eb-72f8-48eb-b483-d36cf20ca6a9" />

---

### ★  Features

- Album cover display with rounded corners matching the card shape
- Progress bar with elapsed time indicator
- Full playback control set: repeat, rewind, play, forward, and favorite
- Clean, modern design with soft shadows and rounded edges
- Precise alignment and spacing using Flexbox

---

### ⚙️ Tech Stack

- **HTML5**
- **CSS3**

---

### 🖿  Project structure

```
Music-Player-Card/
├── Assets/
├── index.html
├── style.css
└── README.md
```

---

### .ᐟ.ᐟ  How It Works

- **Flexbox Layout:** `.player-card` uses flexbox to place the album cover and content side by side. `.progress-bar` and `.player-controls` also use flex for horizontal alignment.
- **Progress Bar:** Uses nested divs (`.progress-track` and `.progress-fill`) aligned next to the `.time` label using `flex` and `gap`.
- **Playback Controls:** Row of clean `<button>` elements with SVG icons. Browser defaults are stripped, adding a subtle opacity change on hover.
- **Spacing:** Default margins were zeroed out and reaplied at the container level to prevent layout shifts and keep everything perfectly aligned.
