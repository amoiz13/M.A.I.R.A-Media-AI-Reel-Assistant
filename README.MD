# 🤖 M.A.I.R.A — Media AI Reel Assistant

An intelligent AI system that automatically generates **faceless viral short-form videos** from trending topics.

M.A.I.R.A transforms ideas into high-engagement video content — from research to rendering — without showing your face, writing scripts manually, or editing videos yourself.

Built by **Abdul Moiz Javaid**  
_AI Engineer · Full-Stack Developer_

---

## ✨ What M.A.I.R.A Does

M.A.I.R.A is an **end-to-end AI-driven content engine** that converts trends into viral videos.

It automatically:

- 📈 Detects trending topics  
- 🧠 Generates scripts using AI  
- 🗣️ Converts text to realistic voice  
- ⏱️ Synchronizes subtitles automatically  
- 🎬 Renders complete videos  
- 🌐 Provides a clean one-click web interface  

---

## 🚀 Core Features

- 🔥 Trending topic discovery  
- 🤖 AI short-script generation  
- 🗣️ Text-to-Speech voiceover  
- ⏲️ Subtitle alignment  
- 🎬 Automatic video composition  
- 🖥️ Web-based trigger UI  
- 🐳 Dockerized and modular architecture  

---

## ⚙️ How It Works

### 1. Trend Detection
M.A.I.R.A discovers trending topics.

### 2. AI Script Writer
Each topic is transformed into a short viral-style script using an AI model.

### 3. Voice Generation
Scripts are converted into natural-sounding audio.

### 4. Subtitle Timing
Text and voice are aligned to produce subtitles.

### 5. Video Rendering
FFmpeg merges:

- Background clip  
- Voiceover  
- Subtitles  

Into a final video.

### 6. Web Interface
Trigger video generation using a browser.

---

## 🧩 Project Structure

```
MAIRA/
├── trends-engine/     # Trend detection logic
├── voice-engine/      # AI voice generation
├── aligner/           # Subtitle timing
├── renderer/          # Video composition (FFmpeg)
├── web-ui/            # Control panel
├── /videos/           # Background content
├── docker-compose.yml
└── .env.example
```

---

## 🐳 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/amoiz13/MAIRA-Media-AI-Reel-Assistant.git
cd MAIRA-Media-AI-Reel-Assistant
```

### 2. Create Environment File
Rename:

```
.env.example → .env
```

Add your AI API key inside the file.

---

### 3. Run M.A.I.R.A

```bash
docker-compose up --build
```

---

### 4. Launch App

Access in browser:

```
http://localhost
```

Click and generate videos.

---

## 📦 Requirements

- Docker + Docker Compose  
- AI API Key  
- Background videos placed in `/videos`  

---

## 🛠 Customization

You can customize:

- Voice models  
- Subtitle design  
- Video templates  
- AI providers  
- Web UI  
- Upload automation  

M.A.I.R.A is built to scale.

---

## 👨‍💻 Author

**Abdul Moiz Javaid**

AI Engineer · Full-Stack Developer  
Passionate about automation, media intelligence, and AI pipelines.

---

## 📄 License

MIT License — Free to use, modify, and distribute.

---

## 🌟 Roadmap

- ✅ Multi-voice support  
- ✅ Auto-upload to platforms  
- ✅ AI thumbnails  
- ✅ Analytics dashboard  
- ✅ Monetization engine  
- ✅ Cloud deployment  

---

If you'd like help improving this project:

> Open an issue or message me — I’ll help you scale MAIRA.
