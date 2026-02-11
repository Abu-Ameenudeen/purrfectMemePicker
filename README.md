# 🐱 Pumpkin's Purrfect Meme Picker

A fun and interactive meme picker web app that allows users to select their current emotion and generate a matching cat meme (static image or GIF).

Built using **HTML, CSS, and Vanilla JavaScript (ES6 Modules)** as part of the Scrimba Frontend learning path.

---

## 🚀 Features

- 🎭 Dynamically generated emotion radio buttons
- 🎯 Emotion-based meme filtering
- 🎞 Optional "GIFs only" filter
- 🎲 Random meme selection when multiple matches exist
- 💡 Highlight effect for selected emotion
- 🪟 Modal popup to display selected meme
- ❌ Close button to dismiss modal

## 📂 Project Structure
```
├── index.html
├── index.css
├── index.js
├── data.js
└── images/
```

## ⚙️ How It Works

1. Emotion options are dynamically generated from `catsData`.
2. User selects:
   - An emotion
   - Optional "GIFs only" checkbox
3. App filters matching cats using:
   - Emotion tag match
   - GIF condition (if selected)
4. A random matching meme is displayed in a modal popup.

---

## 🖼️ Demo Preview

Select your mood → Click **Get Image** → Enjoy your meme 😺

---

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox)
- JavaScript (ES6 Modules)
- Google Fonts (Karla)
