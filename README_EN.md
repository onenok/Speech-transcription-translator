# Real-time Speech Translator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A simple web application that converts English speech to text in real-time and translates it to Traditional Chinese.

## Features

- Real-time Speech Recognition: Converts English speech to text
- Instant Translation: Automatically translates English to Traditional Chinese
- Volume Visualization: Displays real-time volume level
- Text Editing: Supports direct editing of source text with automatic translation updates
- Responsive Design: Supports both landscape and portrait orientations
- Offline Usage: No installation required, runs directly in browser

## How to Use

1. Open the website: [Website Link]
2. Click the "Start Listening" button
3. Allow browser microphone access
4. Start speaking in English, text will appear in the left box
5. Translation will automatically appear in the right box
6. You can directly edit the English text on the left, translation will update automatically

## System Requirements

- Recommended browser: Google Chrome
- Microphone access required
- Internet connection required (for translation feature)

## Notes

- Translation service uses MyMemory API, usage limits may apply
- Speech recognition accuracy depends on microphone quality and ambient noise
- Recommended to use in a quiet environment

## Technical Details

- Uses Web Speech API for speech recognition
- Uses MyMemory Translation API for translation
- Uses Web Audio API for volume visualization
- Built with React framework
- Frontend-only implementation, no backend required

## License

This project is licensed under the MIT License 