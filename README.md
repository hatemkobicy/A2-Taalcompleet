# 🇳🇱 Nederlands A2 Pro — Interactive Dutch A2 Study Platform

**Nederlands A2 Pro** is a modern, lightweight, single-file interactive web application designed to help learners master Dutch at the **CEFR A2 level** and prepare effectively for the **Inburgeringsexamen** (Dutch Civic Integration Exam).

Built with zero build steps (HTML5, Vanilla JavaScript, Tailwind CSS CDN, Web Speech API, and Firebase Realtime Database), it runs smoothly across mobile, tablet, and desktop browsers and is ready for instant hosting on **GitHub Pages**.

🔗 **Live Demo:** `https://hatemkobicy.github.io/nederlands-a2-pro/` *(Update this link if your repository uses a different name)*

---

## ✨ Key Features

### 1. 📚 Grammar & Spelling (`47 Interactive Lessons`)
* Organized across **8 everyday themes** (*Moving House, The Netherlands, Children & School, Shops & Work, Education & Training, Job Hunting, Working & Safety, The Municipality*).
* **Semantic Color-Coding:** Visually highlights Subjects, Verbs, Time/Place/Rest, Conjunctions, and Grammar Focus elements (can be toggled ON/OFF).
* **A2 Exam Tips** included in every lesson.
* **94 Instant-Feedback Quiz Questions** (2 per lesson) with explanations and automatic completion tracking.

### 2. 📖 Core Vocabulary (`184 Essential A2 Words`)
* 23 high-frequency words per theme, each paired with a **simple Dutch example sentence** and translations.
* **Smart Sorting & Filtering:** Sort alphabetically (`A → Z`, automatically ignoring `de/het/een/zich`), by importance (`⭐⭐⭐` → `⭐`), or by theme (`1 → 8`).
* **Self-Test Mode:** Hide translations to practice active recall and track learned words.

### 3. ⚡ Complete Irregular Verbs (`118 Verbs`)
* Comprehensive A2 irregular verb reference featuring **Simple Past (singular & plural)**, **Present Perfect** (`hebben` / `zijn` / `both`), and practical example sentences.
* Toggle between **Card View** and **Table View**, filter by auxiliary verb or theme, and sort by letter, importance, or theme.

### 4. 📝 Interactive Practice Exams (`8 Full Theme Exams`)
* Complete 6-part practice exams for all 8 themes:
  1. **Listening (*Luisteren*):** Synthesized Dutch audio (`nl-NL`) via Web Speech API with adjustable playback speed (`0.8x` slow / `1.0x` normal) and an optional transcript toggle.
  2. **Reading (*Lezen*):** Practical Dutch texts, menus, emails, and notices with multiple-choice questions.
  3. **Grammar Parts 1 & 2:** Interactive fill-in-the-blank exercises with smart answer matching.
  4. **Writing (*Schrijven*):** Sentence-building prompts with model answers, audio playback, and self-check scoring.
  5. **Vocabulary (*Woordenschat*):** 10 visual word prompts per theme.
* Instant percentage scoring, **Geslaagd! (≥ 60%)** pass badge, and persistent best-score tracking.

---

## 🎨 Customization, Accessibility & Live Stats

* **Dual Interface Modes:** Seamlessly switch between **`🇸🇦 Arabic + 🇳🇱 Dutch + 🇬🇧 English` (RTL)** and **`🇬🇧 English + 🇳🇱 Dutch` (LTR)**.
* **5 Color Palettes + Dark Mode:** Ocean Indigo, Emerald Forest, Royal Purple, Warm Sunset, and Berry Rose — each supporting Light and Dark modes.
* **Global Font Size Controls:** `A-` / `A` / `A+` (`85%` to `125%`) for comfortable reading on any screen size.
* **Built-in Dutch Audio (🔊):** Click the speaker button on any example, word, verb, or listening test to hear Dutch pronunciation.
* **Global Search:** Search instantly across all grammar lessons, vocabulary words, and irregular verbs.
* **Auto-Save Progress:** Preferences, studied lessons, learned vocabulary/verbs, and best exam scores are saved locally in `localStorage`.
* **Real-Time Visitor Counter:** Displays live online learners and total visits powered by **Firebase Realtime Database**, with automatic language syncing and offline fallback.

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
   git clone https://github.com/hatemkobicy/nederlands-a2-pro.git
   ```
2. Open `index.html` directly in any modern browser (Chrome, Edge, Safari, or Firefox). No build tools or backend server required.

### Deploy on GitHub Pages
1. Push `index.html` and `README.md` to your GitHub repository.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment** → **Branch**, select `main` and `/ (root)`, then click **Save**.
4. Your site will be live within ~1 minute at `https://hatemkobicy.github.io/YOUR-REPO-NAME/`.

---

## 🛠️ Technologies Used

* **HTML5 & CSS3** (CSS custom properties for theming, responsive layout, RTL/LTR support)
* **Tailwind CSS** (via CDN)
* **Vanilla JavaScript (ES6+)**
* **Web Speech API** (`speechSynthesis` for `nl-NL` pronunciation)
* **Web Storage API** (`localStorage` for offline progress persistence)
* **Firebase Realtime Database** (for live online & total visit counters)

---

## 👤 Author & Contact

Created by **Hatem Kobicy**  
📧 Email: [HATEM.KOBICY@GMAIL.COM](mailto:HATEM.KOBICY@GMAIL.COM)

---

## 📄 License & Purpose

This is an independent, free, non-commercial educational web project created to support self-study learners preparing for the Dutch A2 level and the *Inburgeringsexamen*. Feedback and contributions are always welcome!