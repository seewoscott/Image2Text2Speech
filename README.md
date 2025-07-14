## Configuration

To set up the project, follow these steps:

1. Copy `.env.example` to `.env` in the `image_recognition_speech_*_app` directory
2. Replace the placeholder values in `.env` with your actual API keys
3. Do not commit `.env` to version control

This tool aims to help users learn how unfamiliar words or phrases are pronounced by combining:

## 🎯 Core functionality
Image → Text:
User can “Select Image” or capture an image from clipboard
The app runs OCR to detect and extract the text content

Text → Voice:
Once text is extracted, the tool uses TTS to synthesize spoken output

Clipboard integration:
Buttons allow capturing either text or images directly from the clipboard

OCR (Optical Character Recognition)
→ Automatically recognizes and extracts characters/text from an uploaded image or clipboard content.

Text-to-Speech (TTS)
→ Converts the extracted text into spoken audio, so users can hear the correct pronunciation.

So when you come across a word you don’t know how to say—on signs, screenshots, printed materials—you just capture it and let this tool OCR it and read it aloud, facilitating vocabulary acquisition and pronunciation learning from everyday life.
