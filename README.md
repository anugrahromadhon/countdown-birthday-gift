# 🎂 Countdown Birthday Gift

A lightweight, responsive web app that counts down the days, hours, minutes, and seconds until your next birthday—and then wishes you “Happy Birthday!” when the clock hits zero. Perfect to embed on personal pages, send as a gift link, or just as a fun little project.

Source : https://github.com/heryyy/countdown-birthday-gift

---

## 🚀 Live Demo

👉 [https://anugrahromadhon.github.io/countdown-birthday-gift/](https://anugrahromadhon.github.io/countdown-birthday-gift/)

*If the above link doesn’t load, you can also try the original demo at [https://heryyy.github.io/countdown-birthday-gift/](https://heryyy.github.io/countdown-birthday-gift/).*

---

## 📁 Project Structure

```

countdown-birthday-gift/
├── index.html           # Main landing page
├── styles/
│   └── style.css        # All custom CSS styling
├── scripts/
│   └── index.js     # Logic for calculating and displaying the timer
└── .prettierrc.js       # Prettier configuration for consistent formatting

````

---

## 🔧 How to Use

1. **Clone the repository**  
   ```bash
   git clone https://github.com/anugrahromadhon/countdown-birthday-gift.git
   cd countdown-birthday-gift

2. **Open locally**
   Simply open `index.html` in your favorite browser. No build steps or server required.

3. **Set your birthday**
   In `scripts/countdown.js`, locate the line that sets the target date:

   ```js
   // Example: February 14, 2025 at 00:00:00
   const targetDate = new Date('2025-02-14T00:00:00');
   ```

   Change `'2025-02-14T00:00:00'` to your next birthday in ISO format.

4. **Watch the countdown!**
   The app will display days, hours, minutes, and seconds left. When it reaches zero, the text changes to **“🎉 Happy Birthday! 🎉”**.

---

## ✨ Customization

* **Styling:**
  Tweak colors, fonts, and layout in `styles/style.css`.

* **Date Format:**
  The script accepts any date string recognized by JavaScript’s `Date` constructor. Feel free to adjust timezones or include a specific time of day.

* **UI Enhancements:**
  Add background images, confetti effects, or sound effects for an extra surprise.

---

## 📦 Technologies

* **HTML5** for semantic structure
* **CSS3** (Flexbox + simple animations) for layout and style
* **Vanilla JavaScript** for the countdown logic
* **Prettier** for consistent code formatting

---

## 🚩 Deployment

This repo is already GitHub-Pages–ready. To publish your own:

1. Fork or clone this repo to your account.
2. In your repo’s **Settings → Pages**, set the source branch to `master` (or `main`) and folder to `/ (root)`.
3. Your site will be available at `https://<your-username>.github.io/countdown-birthday-gift/` within a few minutes.

---

## 🤝 Contributing

Feel free to submit issues or pull requests for:

* New visual effects (confetti, fireworks, etc.)
* Accessibility improvements
* Internationalization (i18n) for different languages
* Converting to a React/Vue component

---
