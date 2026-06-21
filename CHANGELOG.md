# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.1.0] - 2026-06-21

### Added
- Snake game (`snake-game.html`) — classic arcade game with arrow key and on-screen button controls
- Score tracking with session best score
- Game-over detection on wall and self-collision
- Fully offline, zero dependencies, single HTML file
- Dark mode support via `prefers-color-scheme`
- Mobile-friendly on-screen directional buttons

---

## [1.0.0] - 2026-06-20

### Added
- Initial release of Capitals Quiz flashcard application
- Spaced repetition algorithm with three difficulty levels (Hard/Good/Easy)
- Multiple deck support for organizing study material
- Create, edit, and delete flashcards
- Visual progress tracking with progress bars
- Deck statistics (total cards, due cards)
- Study session management
- Browser localStorage for persistent data storage
- Backup/restore functionality via browser console
- Sample deck with 28 Indian state capitals
- Offline functionality (works without internet)
- Cross-browser compatibility (Chrome, Firefox, Safari, Edge)

### Features
- **Spaced Repetition:** Evidence-based algorithm with configurable intervals
  - Hard: Review in 1 day
  - Good: Review in 3 days
  - Easy: Review in 7 days
- **Deck Management:** Create unlimited decks organized by topic
- **Card Management:** Add front/back flashcards with unlimited deck size
- **Study Tracking:** Visual progress bar and card statistics
- **Data Privacy:** 100% local storage, no cloud sync
- **Zero Dependencies:** Single HTML file, no frameworks or libraries
- **Responsive Design:** Works on desktop and mobile browsers

### Technical Details
- Single-page application (SPA)
- Vanilla JavaScript (ES6+)
- HTML5 + CSS3
- localStorage API for data persistence
- ~15 KB file size
- Zero external dependencies

### Documentation
- Comprehensive README with usage guide
- Contributing guidelines
- Code of Conduct
- MIT License

---

## [Unreleased]

### Planned Features
- [ ] Dark mode support
- [ ] Multiple spaced repetition algorithms
- [ ] Card image support
- [ ] Bulk import from CSV
- [ ] Study statistics and analytics
- [ ] Keyboard shortcuts
- [ ] Card difficulty indicators
- [ ] Deck categories
- [ ] Random card order option
- [ ] Multilingual UI support

### Future Improvements
- Performance optimizations
- Enhanced study session features
- Export decks to various formats
- Cloud sync option (optional)
- Mobile app version
- API for integrations

---

## Notes

### v1.0.0 Release Notes
- **Launch Date:** June 20, 2026
- **Status:** Stable
- **Tested Browsers:** Chrome 120+, Firefox 121+, Safari 15+, Edge 120+
- **Compatibility:** Windows, macOS, Linux, iOS, Android

### Known Limitations
- Browser storage limited to device storage capacity
- Data not synced across devices
- No built-in sync or backup to cloud (manual export/import only)
- No collaborative features

### Deprecations
None at this time.

### Security Notes
- No external API calls
- No data transmission
- All processing happens locally
- No tracking or analytics
- No third-party scripts

---

## Version History

| Version | Release Date | Status | Notes |
|---------|--------------|--------|-------|
| 1.0.0 | 2026-06-20 | Latest | Initial release |

---

## Contributing

Want to contribute to future releases? Check out [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Support

For issues or questions about past versions, please:
- 📖 Check the [README](README.md)
- 🐛 Open an [issue](https://github.com/BodhiProtocol/flashcard-app/issues)
- 💬 Check [discussions](https://github.com/BodhiProtocol/flashcard-app/discussions)

---

*Last updated: 2026-06-20*
