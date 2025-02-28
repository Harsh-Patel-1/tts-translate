# TTS & Translation App

A simple web application that provides text-to-speech (TTS) functionality along with language translation.

## Features

- Convert text to speech using browser's SpeechSynthesis API
- Translate text using Google Translate API
- Supports multiple languages
- User-friendly interface built with Tailwind CSS

## Technologies Used

- HTML, CSS, JavaScript
- Tailwind CSS for styling
- Google Translate API (for translation)
- SpeechSynthesis API (for text-to-speech)
- Node.js and Express.js (for backend translation API)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/tts-translate-app.git
   cd tts-translate-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file in the root directory and add your Google Translate API key:
   ```
   GOOGLE_TRANSLATE_API_KEY=your_api_key_here
   ```
4. Start the server:
   ```sh
   npm start
   ```
5. Open `http://localhost:3000` in your browser.

## Project Structure

```
📦 tts-translate-app
├── 📂 api
│   ├── translate.js
├── 📂 public
│   ├── assets
│   ├── index.html
│   ├── script.js
│   ├── styles.css
├── 📂 node_modules
├── .env
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

## Usage

1. Enter the text you want to translate and convert to speech.
2. Select the target language and preferred voice.
3. Click the "Play Text" button to hear the translated text.

## Author

## Harsh Patel

**Note:** Make sure to replace `your_api_key_here` with your actual Google Translate API key in the `.env` file.
