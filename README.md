# Maskit 🎭

**Stop leaking organization data to AI.**

The problem is simple: people copy-paste sensitive internal data into AI tools (ChatGPT, Claude, etc.) without thinking. It's an "eye-opening" security risk for companies. 

**Maskit** is a local-first browser extension that masks sensitive data *before* it gets pasted into AI or any other software.

## 🛡️ How it works
- **Intercepts:** It listens for the 'paste' action on your browser.
- **Redacts:** It scans the text for sensitive patterns (API keys, credentials, PII) locally.
- **Protects:** It replaces sensitive info with masks (e.g., `[SENSITIVE-DATA]`) before the website ever sees it.

## 🚀 Vision
To build a "safety layer" for the AI era—ensuring productivity doesn't come at the cost of data privacy.

## 🛠️ Tech Stack
- **Platform:** Chromium Extension (Manifest V3)
- **Logic:** Vanilla JavaScript (Local processing only)
- **Scope:** Zero-trust architecture. No data ever leaves the user's machine.

## 📥 Development Setup
1. Clone this repository.
2. Go to `chrome://extensions/` in your browser.
3. Enable **Developer Mode** (top right).
4. Click **Load Unpacked** and select this folder.
