# 🔮 Astrology App — Know Your Name

A beautiful, cosmic-themed web application that reveals your personality traits and destiny based on the first letter of your name — rooted in Hindu astrology and name-science (Namology).

---

## ✨ Features

- **Name-based Astrology** — Enter your first name and instantly discover your cosmic profile
- **26 Personality Profiles** — Unique Hindi descriptions for every letter A–Z
- **Animated Starfield** — Dynamic canvas-rendered twinkling stars in the background
- **Confetti Celebration** — A burst of golden confetti on each result reveal
- **Spinning Zodiac Wheel** — Animated zodiac ring on the results screen
- **Floating Divine Icons** — Ganesha and Goddess illustrations with smooth float animations
- **Responsive Design** — Works perfectly on mobile, tablet, and desktop
- **Smooth Transitions** — Fade-in/slide-up section animations

---

## 📁 File Structure

```
astrology-app/
├── index.html      # Main HTML structure & JavaScript logic
├── style.css       # All styles — cosmic dark theme with gold accents
└── README.md       # Project documentation (this file)
```

---

## 🚀 Getting Started

No build step required — this is a pure HTML/CSS/JS project.

### Run Locally

1. Download or clone the project folder.
2. Open `index.html` in any modern browser.
3. That's it! No server needed.

### Or via Live Server (VS Code)

1. Install the **Live Server** extension in VS Code.
2. Right-click `index.html` → **Open with Live Server**.

---

## 🛠 How It Works

1. User enters their **first name** (3–15 English letters).
2. The app reads the **first character** of the name.
3. It looks up a matching entry in the `data` array (A–Z).
4. The result page displays the **personality summary** in Hindi.
5. A confetti animation fires to celebrate the reveal.

### Input Validation

- Only English alphabets allowed (`A–Z`, `a–z`)
- Minimum 3 characters, maximum 15 characters
- Invalid input triggers a shake animation and error message

---

## 🎨 Design System

| Token | Value |
|---|---|
| Background (deep) | `#0a0414` |
| Background (mid) | `#120826` |
| Accent Gold | `#FFD700` |
| Accent Amber | `#FFB347` |
| Accent Rose | `#FF6B9D` |
| Text Light | `#f0e8ff` |
| Text Muted | `#b8a9d4` |
| Display Font | Cinzel Decorative |
| Body Font | Raleway |

---

## 📦 External Dependencies

| Library | Version | Purpose |
|---|---|---|
| Google Fonts | — | Cinzel Decorative + Raleway |
| canvas-confetti | 1.6.0 | Celebration burst animation |

All images are loaded from external CDN URLs (cleanpng.com).

---

## 📖 Content Language

The personality summaries are written in **Hindi (Devanagari script)**, making this app ideal for Hindi-speaking users interested in Vedic name astrology.

---

## 🙏 Credits

- **Concept**: Traditional Hindu name-based astrology (Namology)
- **Images**: cleanpng.com (Ganesha, Zodiac Wheel, Goddess illustrations)
- **Fonts**: Google Fonts
- **Confetti**: [canvas-confetti](https://github.com/catdad/canvas-confetti)

---

## 📄 License

This project is open-source and free to use for personal and educational purposes.

---

> *"नाम न सिर्फ हमारे व्यक्तित्व के विषय में जानकारी देता है बल्कि यह हमारे भविष्य का भी आइना होता है।"*  
> *"A name is not just an identity — it is a mirror of your future."*
