# VidSnapAI 🎥🤖

**Create AI-powered reels from your images or clips in minutes.**

## 🔥 What is VidSnapAI?

VidSnapAI is a Flask-based web application that lets users upload images/videos, input a script, and automatically generates a high-quality, vertical Instagram reel (1080x1920) with a voiceover using ElevenLabs' AI.

> This is the ideal tool for content creators, influencers, marketers, or anyone looking to automate short-form content creation.

---

## ✨ Features

- 📂 Upload multiple image/video files
- 🗣️ Convert input text into AI voiceover using ElevenLabs
- 🎬 Automatically combine media + audio into vertical reels (1080x1920)
- 🖼️ Showcase your creations in a responsive gallery
- ⚡ Built using Flask, FFmpeg, Bootstrap 5

---


## 🧠 Tech Stack

- **Backend:** Flask, Python, FFmpeg
- **Frontend:** HTML, CSS (Bootstrap 5)
- **AI Voiceover:** ElevenLabs API
- **Video Rendering:** FFmpeg (via subprocess)

---

## Add your ElevenLabs API key to config.py:
```bash
ELEVENLABS_API_KEY = "your-api-key-here"
```

## Run the Flask app:
```bash
python main.py
```

## Run the background video/audio processing script:
```bash
python generate_process.py
```

## 🛠️ How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/SiddharthRiot/VidSnapAI.git
   cd vidsnapai
