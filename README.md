# 🇳🇱 TaalCompleet A2 — Complete Interactive Study Guide

A modern, single-file interactive web application designed to help learners master Dutch at the **A2 level** and prepare for the **Inburgeringsexamen**, structured around the 8 themes of **TaalCompleet A2**.

Built with zero dependencies (pure HTML5, Vanilla JavaScript, Tailwind CSS CDN, and the browser's Web Speech API), it works seamlessly on mobile, tablet, and desktop — and can be hosted directly on **GitHub Pages**.

---

## ✨ Key Features

### 1. 📚 Grammar & Spelling (`47 Abc Lessons`)
- Covers **all 8 themes** (`Thema 1: Verhuizen` through `Thema 8: De gemeente`).
- **Semantic Color-Coding:** Visually highlights Subjects, Verbs, Time/Place/Rest, Conjunctions, and Grammar Focus tokens (can be toggled ON/OFF).
- **A2 Inburgering Exam Tips** for every lesson.
- **94 Interactive Quick-Quiz Questions** (2 per lesson) with instant explanations and completion tracking.

### 2. 📖 Core Vocabulary (`184 Words`)
- 23 essential words per theme with **simple Dutch example sentences** and translations.
- **Smart Sorting:** Alphabetical (`A → Z`, ignoring `de/het/een/zich`), by Importance (`⭐⭐⭐` → `⭐`), or by Theme (`1 → 8`).
- **Self-Test Mode:** Hide translations to practice active recall, and mark words as *Learned*.

### 3. ⚡ Complete Irregular Verbs (`118 Official Verbs`)
- All 118 TaalCompleet A2 irregular verbs with **Simple Past (singular & plural)**, **Present Perfect** (`hebben` / `zijn` / `both`), and simple example sentences.
- Switch between **Card View** and **Table View**, filter by auxiliary verb or theme, and sort by letter, importance, or theme.

### 4. 📝 Interactive Theme Exams (`Toetsen Thema 1–8`)
- Full interactive practice exams for all 8 themes, each featuring 6 parts:
  1. **Listening (*Luisteren*):** Generated Dutch audio via Web Speech API (`nl-NL`), adjustable speed (`0.8x` slow / `1.0x` normal), and an optional transcript toggle.
  2. **Reading (*Lezen*):** Realistic Dutch texts, menus, emails, and schedules with multiple-choice questions.
  3. **Grammar Parts 1 & 2:** Fill-in-the-blank exercises with smart answer checking.
  4. **Writing (*Schrijven*):** Sentence-building prompts with model answers, audio playback, and self-assessment checkboxes.
  5. **Vocabulary (*Woordenschat*):** 10 visual prompts per theme.
- Instant score calculation, **Geslaagd! (≥ 60%)** badge, and persistent best-score tracking.

---

## 🎨 Customization & Accessibility

- **Dual Interface Modes:** Switch instantly between **`🇸🇦 Arabic + 🇳🇱 Dutch + 🇬🇧 English` (RTL)** and **`🇬🇧 English + 🇳🇱 Dutch` (LTR)**.
- **5 Color Palettes + Dark Mode:** Ocean Indigo, Emerald Forest, Royal Purple, Warm Sunset, and Berry Rose — each supporting Light and Dark themes.
- **Global Font Size Controls:** `A-` / `A` / `A+` (`85%` to `125%`) for comfortable reading on any screen.
- **Built-in Dutch Audio (🔊):** Click the speaker button on any example, word, verb, or listening test to hear native-style Dutch pronunciation.
- **Global Search:** Instantly search across all grammar lessons, vocabulary words, and irregular verbs.
- **Auto-Save Progress:** All progress, preferences, learned items, and exam scores are saved locally in `localStorage`.

---

## 📂 Project Structure

```text
├── index.html      # Complete standalone web application (HTML + CSS + JS)
└── README.md       # Project documentation
```

---

## 🚀 Getting Started

### Run Locally
1. Clone or download this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   ```
2. Open `index.html` directly in any modern web browser (Chrome, Edge, Safari, or Firefox). No build tools or server required!

### Deploy on GitHub Pages
1. Push `index.html` and `README.md` to your GitHub repository.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment** → **Branch**, select `main` and `/ (root)`, then click **Save**.
4. Your live site will be available in ~1 minute at:
   ```text
   https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
   ```

---

## 🛠️ Technologies Used

- **HTML5 & CSS3** (Custom CSS variables for theming & responsive layout)
- **Tailwind CSS** (via CDN)
- **Vanilla JavaScript (ES6+)**
- **Web Speech API** (`speechSynthesis` for `nl-NL` pronunciation)
- **Web Storage API** (`localStorage` for offline progress persistence)

---

## 👤 Author & Contact

Created by **Hatem Kobicy**  
📧 Email: [HATEM.KOBICY@GMAIL.COM](mailto:HATEM.KOBICY@GMAIL.COM)

---

## 📄 Disclaimer

This is an independent, non-commercial educational study companion built to help Dutch learners practice A2-level grammar, vocabulary, irregular verbs, and exam skills alongside the *TaalCompleet A2* curriculum. All official trademarks and original textbook copyrights belong to their respective publisher (KleurRijker).