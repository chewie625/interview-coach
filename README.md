# Interview Coach

Practice situational interview questions with AI-powered feedback and STAR ratings.

## Features
- Generates tailored situational questions from a job description
- Speech-to-text answer input (mic) or type directly
- Rates each STAR component (Situation, Task, Action, Result) individually
- Provides example answers based on your CV
- Live free model list from OpenRouter

## Setup
1. Get a free API key from [openrouter.ai/keys](https://openrouter.ai/keys)
2. Serve the files locally:
   ```
   python3 -m http.server 8000
   ```
3. Open `http://localhost:8000` in Chrome or Edge
4. Paste your API key into the Setup tab

## Files
- `index.html` — main app
- `styles.css` — all styling

## Notes
- Speech recognition requires Chrome or Edge
- PDF CV upload supported via PDF.js
- API key is saved to localStorage so you only enter it once
