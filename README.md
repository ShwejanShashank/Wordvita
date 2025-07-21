# Wordvita

**Wordvita** is an original, web-based word puzzle game built using **React.js** and powered by **Machine Learning word vector models**. Unlike traditional word games, Wordvita challenges players to guess a mystery word using **five intelligent clues** derived from semantic relationships between words.

Developed by [Shwejan Shashank](https://github.com/ShwejanShashank), this game blends NLP and gaming to create a fun and educational experience.

---

## 🧠 Gameplay Overview

- Players are presented with a set of **5  clues**.
- These clues are derived using **word vector similarity** techniques (e.g., cosine similarity).
- Based on the hints, the player must **guess the correct target word**.
- Each clue is contextually meaningful — can be a synonym, category, usage, or semantic neighbor.
- No trial & error or letter guessing — it's about **understanding and reasoning**.

---

## ✨ Features

- 🔍 ML-driven word clue generation using **word embeddings**
- ⚛️ Built entirely in **React.js**
- 🧠 Unique gameplay — not inspired by Wordle
- 🎯 Focus on logical reasoning and vocabulary
- 📱 Responsive design for desktop and mobile
- ♻️ Replayable with multiple word sets

---

## 🛠 Tech Stack

- **Frontend**: React.js, HTML, CSS, JavaScript
- **ML/NLP**: Word2Vec or GloVe (or any word embedding model)
- **Logic**: Vector similarity calculations for clue generation
- **Deployment**: GitHub Pages / Netlify / Vercel (or local)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ShwejanShashank/Wordvita.git
cd Wordvita
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm start
```

Open your browser at `http://localhost:3000` to play.

---

## 🤖 ML/Word Vector Logic

- The game uses **pre-trained word embedding models** to find semantically related words.
- Clues are selected based on **cosine similarity** to the target word.
- Optional filters prevent repetitive, obscure, or misleading clues.
- All logic runs locally or can be powered via an API/backend service.

---

## 🌐 Live Demo

[Play Wordvita Online](https://github.com/ShwejanShashank/Wordvita) *(add live site URL once hosted)*

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

## 👨‍💻 Creator

Developed by [Shwejan Shashank](https://github.com/ShwejanShashank)  
For suggestions, improvements, or collaboration — feel free to contribute or raise an issue!

---

🧩 Think. Analyze. Guess.  
Play **Wordvita** – the smart word game for curious minds.
