# 🌐 LinguaFlow - Language Translation Tool

A modern language translation tool built with Python and Streamlit, powered by Google Translate.

## Features
- 100+ supported languages
- Auto language detection
- Real-time word/character stats
- Glassmorphism dark-mode UI
- Copy translated text

## Installation

```bash
pip install -r requirements.txt
```

## Run

```bash
streamlit run app.py
```

## Usage
1. Select source language (Auto Detect or specific)
2. Select target language
3. Enter text (up to 5000 characters)
4. Click Translate
5. View result with stats

## Tech Stack
- **UI**: Streamlit
- **Translation**: googletrans 4.0.0-rc1
- **Language**: Python 3.8+
- **Styling**: Custom CSS (Glassmorphism dark theme)

## Notes
- Internet connection required
- `httpx==0.13.3` is pinned for googletrans compatibility
