# Speech-transcription-translator

[中文版](README.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A simple web application that converts speech (default English) to text in real-time and translates it to other languages (default Traditional Chinese).

## Features

- Real-time speech recognition
- Real-time translation
- Volume visualization showing real-time volume level
- Support direct editing of source text with automatic translation update
- Support landscape and portrait screen orientations
- Offline usage, no installation needed, runs directly in browser

## How to Use

1. Open website [Website Link](https://onenok.github.io/Speech-transcription-translator/)
2. Click "Start Listening" button
3. Allow browser microphone access
4. Start speaking, text will appear in source text box
5. Translation will appear in target text box
6. You can directly edit the text, translation will update automatically

## System Requirements

- Recommended using Google Chrome
- Microphone access required
- Internet connection required (for translation feature)

## Notes

- Translation service uses MyMemory API, usage limits may apply
- Speech recognition accuracy depends on microphone quality and ambient noise
- Recommended to use in a not noisy environment

## Technical Details

- Uses Web Speech API for speech recognition
- Uses MyMemory Translation API for translation
- Uses Web Audio API for volume visualization
- Built with React framework
- Frontend-only implementation, no backend required

## License

This project is licensed under the MIT License
