# 📚 Capitals Quiz - Flashcard Learning Application

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Release](https://img.shields.io/badge/Release-v1.0-blue)](https://github.com/BodhiProtocol/flashcard-app)
[![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9C%93-brightgreen)](https://github.com/BodhiProtocol/flashcard-app)

> **A minimalistic, web-based flashcard application with intelligent spaced repetition learning.** Perfect for students, professionals, and lifelong learners who want to study smarter, not harder.

---

## 🎯 Business Value

**Problem:** Traditional study methods are inefficient and time-consuming.  
**Solution:** Evidence-based spaced repetition algorithm that optimizes retention and minimizes study time.

### Key Benefits
- ✅ **Zero Infrastructure** — No server, no maintenance, no costs
- ✅ **Privacy First** — All data stays on user's device (no cloud uploads)
- ✅ **Zero Onboarding** — Works immediately, no login required
- ✅ **Offline Ready** — Study anywhere, anytime, no internet needed
- ✅ **Scalable** — From personal use to organizational deployments

---

## ✨ Core Features

| Feature | Benefit |
|---------|---------|
| **Spaced Repetition Algorithm** | Scientifically-proven method to optimize learning retention |
| **Multiple Decks** | Organize content by topic/subject for structured learning |
| **Intuitive UI/UX** | Zero learning curve — users are productive instantly |
| **Local Data Storage** | Complete privacy — no data collection or tracking |
| **Single File Deployment** | Minimal footprint — just one HTML file, no dependencies |
| **Works Offline** | Study without internet connection |
| **Cross-Platform** | Chrome, Firefox, Safari, Edge — works everywhere |

---

## 📊 Use Cases

### Education
- 🎓 **Student Exam Prep** — Accelerate learning for competitive exams
- 🌍 **Language Learning** — Master vocabulary and phrases efficiently
- 📚 **Subject Mastery** — Standardized testing, certifications, courses

### Professional Development
- 💼 **Corporate Training** — Employee skill development programs
- 🔐 **Compliance Training** — Certification and mandatory training requirements
- 🚀 **Sales Training** — Product knowledge and process memorization

### Personal Growth
- 🧠 **Hobby Learning** — History, trivia, general knowledge
- 🎨 **Skill Development** — Music theory, art history, cultural knowledge
- 📖 **Language Acquisition** — Self-paced language learning

---

## 🚀 Getting Started

### Installation
No installation required. Works on any device with a modern browser.

```bash
# Option 1: Clone the repository
git clone https://github.com/BodhiProtocol/flashcard-app.git

# Option 2: Download directly
# Visit: https://github.com/BodhiProtocol/flashcard-app
# Click: Code → Download ZIP
```

### Usage
1. **Open the app**
   - Double-click `capitals-quiz.html` or right-click → Open with Browser

2. **Choose a deck**
   - Start with the pre-loaded "Indian Capitals" sample
   - Or create your own custom deck

3. **Study with spaced repetition**
   - Cards appear based on your performance
   - Rate difficulty (Hard/Good/Easy)
   - System automatically schedules next review

4. **Track progress**
   - Visual progress bar shows study completion
   - Statistics show deck size and due cards

### Sample Deck Included
**🇮🇳 Indian Capitals** — All 28 states with capitals (perfect for geography learners)

---

## 🧠 How It Works

### Spaced Repetition Algorithm
The app uses an evidence-based interval scheduling system:

| Your Rating | Next Review |
|------------|------------|
| Hard 😤 | 1 day |
| Good ✓ | 3 days |
| Easy 🎯 | 7 days |

**Science:** Research shows spaced repetition increases long-term retention by up to 90% compared to cramming.

### Study Flow
```
Open Deck → See Question → Flip Card → See Answer → Rate Difficulty → System Schedules Next Review
```

---

## 🎨 Interface Preview

**Deck List View:**
```
📚 Flashcards
┌──────────────────────┐
│ + New Deck           │
├──────────────────────┤
│ 🇮🇳 Indian Capitals │
│ 28 cards • 5 due     │
└──────────────────────┘
```

**Study View:**
```
📚 Flashcards
┌────────────────────────────┐
│ ← Back    + Add Card       │
│                            │
│ 🇮🇳 Indian Capitals       │
│ 28 cards • 5 due          │
│ ▓▓▓▓▓░░░░ 50%             │
│                            │
│ ┌──────────────────────┐   │
│ │   Question/Answer     │   │
│ │                       │   │
│ │  (Click to flip)      │   │
│ └──────────────────────┘   │
│ [Hard] [Good] [Easy]       │
└────────────────────────────┘
```

---

## 💾 Data Management

### Storage
- **Location:** Browser localStorage (local device only)
- **Persistence:** Data saved between sessions
- **Privacy:** Zero cloud storage, zero tracking
- **Portability:** Export/import via browser console

### Backup Your Data
```javascript
// Export
copy(localStorage.getItem('flashcards'))
// Save the copied JSON to a text file

// Import
localStorage.setItem('flashcards', 'YOUR_BACKUP_JSON_HERE')
```

---

## 🛠️ Technical Specifications

| Aspect | Details |
|--------|---------|
| **Architecture** | Single-page application (SPA) |
| **Technology** | Vanilla JavaScript (no frameworks, no dependencies) |
| **File Size** | ~15 KB |
| **Browser Support** | Chrome 60+, Firefox 55+, Safari 11+, Edge 79+ |
| **Dependencies** | Zero external dependencies |
| **Performance** | Instant loading, sub-100ms interactions |

---

## 🔒 Security & Privacy

✅ **Privacy-First Design**
- ✓ No user tracking
- ✓ No data collection
- ✓ No external API calls
- ✓ No account registration
- ✓ Works completely offline

✅ **Data Security**
- ✓ All data stored locally on device
- ✓ No transmission to external servers
- ✓ User has complete data control
- ✓ Can delete data anytime

---

## 📋 Complete Feature Set

### Deck Management
- Create unlimited decks
- Organize by topic/subject
- View deck statistics
- Delete decks

### Card Management
- Create front/back flashcards
- Add cards to decks
- Delete cards
- Unlimited deck size

### Study Features
- Spaced repetition scheduling
- Difficulty-based intervals (Hard/Good/Easy)
- Visual progress tracking
- Study session management

### Data Features
- Local storage (browser)
- Manual backup/restore
- No cloud required
- Portable data export

---

## 💡 Best Practices for Effective Learning

### Question Design
1. **Be Specific** — Avoid ambiguous questions
2. **One Concept** — Each card = one idea
3. **Active Recall** — Frame as questions, not statements
4. **Clear Answers** — Keep answers concise (< 10 words)

### Study Habits
1. **Consistency** — 15-30 min daily beats 3-hour weekly sessions
2. **Don't Skip** — Review all due cards, not just the hard ones
3. **Spacing** — Let the algorithm handle intervals
4. **Track Progress** — Monitor which topics need more focus

### Example Deck
```
Front: What is the capital of Maharashtra?
Back: Mumbai

Front: Define "spaced repetition"
Back: Technique of reviewing material at optimal intervals to maximize retention
```

---

## 📖 Documentation

- **[Quick Start Guide](#getting-started)** — Get up and running in 2 minutes
- **[How Spaced Repetition Works](#how-it-works)** — Understand the science
- **[Best Practices](#-best-practices-for-effective-learning)** — Learn effectively
- **[Data Backup](#-data-management)** — Protect your data

---

## 🔄 Version History

**v1.0** (Current)
- Initial release
- Spaced repetition algorithm
- Multiple decks support
- Local storage
- Indian capitals sample deck

---

## 🤝 Support & Contribution

### Report Issues
Found a bug? Have suggestions?
- 🐛 [Open an Issue](https://github.com/BodhiProtocol/flashcard-app/issues)
- 💬 Describe the problem clearly
- 📸 Include screenshots if relevant

### Contribute
Want to improve the app?
- 🍴 Fork the repository
- 📝 Make changes
- 📤 Submit a pull request

### Get Help
- 📖 Check the FAQ below
- 💭 Review the documentation
- 🔍 Search existing issues

---

## ❓ FAQ

**Q: Is my data safe?**  
A: Yes! All data stays on your device. We don't collect, store, or transmit any data.

**Q: Can I use this offline?**  
A: Yes! Download the file and use it anywhere without internet.

**Q: Will I lose my data if I clear browser cache?**  
A: Only if you clear localStorage. Data otherwise persists indefinitely.

**Q: Can I share decks with others?**  
A: Yes, export via browser console and share the JSON file.

**Q: What if I want to use this on mobile?**  
A: Works on mobile browsers! Open the HTML file in Chrome/Safari mobile.

**Q: Can I customize the app?**  
A: Yes! Edit the HTML file directly to change colors, intervals, etc.

**Q: Why spaced repetition?**  
A: Research shows it increases retention by up to 90% vs. traditional cramming.

---

## 📄 License

This project is licensed under the **MIT License** — free for personal, educational, and commercial use.
See [LICENSE](LICENSE) file for details.

---

## 👤 About

**Created by:** BodhiProtocol  
**Built with:** Claude AI  
**Status:** Active & Maintained  
**Last Updated:** 2026

---

**⭐ If you find this helpful, please consider giving it a star!**

[GitHub Repository](https://github.com/BodhiProtocol/flashcard-app) • [Report Issue](https://github.com/BodhiProtocol/flashcard-app/issues) • [Suggest Feature](https://github.com/BodhiProtocol/flashcard-app/issues)

---

*Study smarter, not harder. 🚀*
