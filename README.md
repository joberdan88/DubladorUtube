# 🎙 Real-Time YouTube Voice Dubbing (English → Brazilian Portuguese)

A web-based application that captures the audio from a YouTube video, translates it in real time from **English** to **Brazilian Portuguese**, and plays back the dubbed version using text-to-speech.  

Perfect for language learners, content consumers, or anyone who wants to enjoy YouTube videos in their native language without waiting for official subtitles or dubs.

---

##  Features

- ** Speech Recognition** — Captures spoken audio from YouTube.
- ** Real-Time Translation** — Converts English speech into Brazilian Portuguese instantly.
- ** Text-to-Speech (TTS)** — Speaks the translated text naturally in Brazilian Portuguese.
- ** Simple UI** — Easy-to-use interface with clear instructions.
- ** Works in Browser** — No need to install anything locally.

---

##  How It Works

1. Paste a YouTube link into the app and load the video.
2. Increase your computer’s audio volume.
3. Click **"Start Dubbing"**.
4. The system captures the video’s audio, translates it, and plays back the dubbed version.
5. Enjoy the video with real-time Brazilian Portuguese dubbing.

> **Note:** The current setup captures audio via your device’s microphone. For direct internal audio capture, additional system-level configurations or APIs are required.

---

##  Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js / Express
- **Speech-to-Text (STT):**
  - [Google Cloud Speech-to-Text](https://cloud.google.com/speech-to-text) *(requires API key)*
  - [OpenAI Whisper API](https://platform.openai.com/docs/guides/speech-to-text) *(optional)*
- **Translation:** [Google Cloud Translation API](https://cloud.google.com/translate)
- **Text-to-Speech:** [Google Cloud Text-to-Speech API](https://cloud.google.com/text-to-speech)

---
