# 📚 Flashcard App

A minimalistic, web-based flashcard application with spaced repetition learning. Perfect for memorizing anything from vocabulary to state capitals.

## ✨ Features

- **Simple & Clean UI** — distraction-free learning experience
- **Spaced Repetition** — intelligently schedules cards based on difficulty
- **Multiple Decks** — organize cards into different study topics
- **Local Storage** — all data saved in your browser, no server required
- **Fast & Lightweight** — single HTML file, works offline
- **Sample Deck** — pre-loaded with Indian state capitals to get you started

## 🚀 Quick Start

1. **Download or clone this repo**
   ```bash
   git clone https://github.com/BodhiProtocol/flashcard-app.git
   ```

2. **Open `capitals-quiz.html` in your browser**
   - Double-click the file, or
   - Right-click → Open with → Your favorite browser

3. **Start studying!**
   - Click on "🇮🇳 Indian Capitals" to review the sample deck
   - Click "+ New Deck" to create your own
   - Click "+ Add Card" to add flashcards

## 📖 How to Use

### Study Mode
1. Click a deck from the main screen
2. Read the question (front of card)
3. Click the card to reveal the answer
4. Rate your answer:
   - **Hard** — card returns in 1 day
   - **Good** — card returns in 3 days
   - **Easy** — card returns in 7 days

### Create Cards
1. In a deck, click "+ Add Card"
2. Enter the front (question) and back (answer)
3. Click "Add"

## 🎯 Spaced Repetition Algorithm

Cards are scheduled based on your difficulty rating:
- **Hard (1 day)** — review soon if you struggled
- **Good (3 days)** — moderate spacing for normal cards
- **Easy (7 days)** — longer spacing for well-known cards

Only cards that are due show up in your study session. Once you've answered all due cards, you'll see "All caught up! 🎉"

## 💾 Data Storage

- All data is stored **locally in your browser** (localStorage)
- No server, no cloud sync, no account needed
- Data persists between sessions
- Clear browser cache/cookies to reset

## 🛠️ Installation

No installation needed! Just open the HTML file in any modern browser (Chrome, Firefox, Safari, Edge).

**Supported Browsers:**
- Chrome/Edge (recommended)
- Firefox
- Safari
- Any modern browser with ES6+ support

## 📝 Sample Decks Included

- **🇮🇳 Indian Capitals** — All 28 Indian states and their capitals

## 🎨 Customization

Want to customize the app? Edit `anki.html`:
- Change colors in the `<style>` section
- Add more sample decks in the `createSampleDeck()` function
- Modify the spaced repetition intervals in the `rateCard()` function

## 📋 Example Use Cases

- 📚 Study for exams (history, geography, languages)
- 🌍 Learn new languages (vocabulary, phrases)
- 🧠 Memorize facts (capitals, dates, definitions)
- 💼 Professional learning (certifications, technical topics)

## 🔄 Backup Your Data

To backup your cards:
1. Open browser DevTools (F12)
2. Go to Console tab
3. Run: `copy(localStorage.getItem('flashcards'))`
4. Paste into a text file and save

To restore:
1. Open the HTML file
2. Open DevTools Console
3. Run: `localStorage.setItem('flashcards', 'PASTE_YOUR_BACKUP_HERE')`

## 📄 License

This project is open source and available for personal and educational use.

## 🤝 Contributing

Found a bug or have an idea? Feel free to:
- Report issues
- Suggest features
- Fork and create a pull request

## 💡 Tips for Effective Learning

1. **Write clear questions** — make the front specific and unambiguous
2. **Keep answers concise** — short answers are easier to memorize
3. **Study regularly** — daily 10-minute sessions beat weekly cramming
4. **Review consistently** — don't skip due cards
5. **Gradually increase difficulty** — start with easier topics

---

**Happy Learning!** 🎓

For questions or feedback, feel free to open an issue or reach out.
