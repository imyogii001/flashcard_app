
# Flashcard Learning App
A simple command-line flashcard app built with Python to help you study smarter. Add your own Q&A cards, quiz yourself, and track what you've learned — all saved locally with no setup required.

#Features

- Add Flashcards — Create custom question & answer pairs
- Review Flashcards— Quiz yourself one card at a time
- Mark as Learned— Track your progress and skip mastered cards
- Persistent Storage — All data saved in a local `flashcards.json` file

#Tech Stack
- Python 3
- `json` module (built-in)
- No third-party libraries required

#Project Structure
flashcard-app/
│
├── flashcards.py       # Main application file
└── flashcards.json     # Auto-generated data file (created on first run)

# How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/flashcard-app.git
   cd flashcard-app
   ```

2. Run the app
   ```bash
   python flashcards.py
   ```

3. Follow the menu 
   1. Add Flashcard
   2. Review Flashcards
   3. Mark Flashcards as Learned
   4. Exit

#How It Works

- Each flashcard is stored as a dictionary with three fields: `question`, `answer`, and `learned`
- Cards marked as learned are skipped during review sessions
- Data is read from and written to `flashcards.json` automatically on every action
- If the file doesn't exist, the app starts fresh without crashing

#Future Improvements

- [ ] Spaced repetition algorithm
- [ ] Multiple user support
- [ ] Score tracking & progress dashboard
- [ ] GUI or web interface
- [ ] Unit tests


