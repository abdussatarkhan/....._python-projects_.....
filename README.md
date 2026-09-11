# JARVIS — Voice-Activated AI Desktop Assistant & Automation Hub

<div align="center">

[![Daily Streak](https://img.shields.io/badge/Daily%20Streak-Active%20%F0%9F%94%A5-brightgreen?style=flat-square&logo=github)](https://github.com/abdussatarkhan)
[![Software Portfolio](https://img.shields.io/badge/Portfolio-Software%20Engineering%20%26%20Systems-0e75b6?style=flat-square&logo=github)](https://github.com/abdussatarkhan)
[![Author: Abdussatar](https://img.shields.io/badge/Author-Abdussatar-24292e?style=flat-square&logo=github)](https://github.com/abdussatarkhan)

</div>

[![CI](https://github.com/abdussatarkhan/python_projects_repo/actions/workflows/ci.yml/badge.svg)](https://github.com/abdussatarkhan/python_projects_repo/actions)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Web Speech API](https://img.shields.io/badge/Web_Speech_API-Voice_Recognition-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)
[![HUD Interface](https://img.shields.io/badge/Interface-Cybernetic_HUD-00FFFF?style=for-the-badge&logo=html5&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

> **An interactive, voice-controlled personal desktop assistant built with Python and HTML5/JavaScript. Features continuous voice recognition, real-time text-to-speech feedback, desktop automation triggers, system telemetry monitoring, and an Iron Man-inspired interactive cybernetic HUD.**

---

## 🏛️ System Architecture

```mermaid
graph TD
    Mic[🎙️ User Voice Input / Microphone] --> SpeechAPI[Web Speech Recognition API]
    SpeechAPI --> Parser[Natural Language Command Parser & Dispatcher]
    Parser --> PythonServer[Python Local HTTP / CORS Backend Server]
    PythonServer --> SysActions[Desktop Automation: App Launch, Media & Web Queries]
    PythonServer --> Telemetry[System Diagnostics: CPU, Memory & Network Latency]
    SysActions --> TTS[🔊 Voice Synthesis & Spoken Responses]
    Telemetry --> HUD[🖥️ Futuristic Cybernetic Canvas HUD & Audio Visualizer]
```

---

## 🌟 Key Features & Capabilities

- **🎙️ Hands-Free Voice Control**: Continuous microphone listening powered by the Web Speech API with natural conversational feedback and voice activation.
- **⚡ Desktop Automation & Quick Launch**: Instantly execute web queries, open popular applications, play audio, and fetch live weather and system time via voice or UI commands.
- **🖥️ Cybernetic Iron Man HUD**: Dynamic audio frequency spectrum visualizer, rotating holographic target rings, and dark-mode terminal layout.
- **🔒 Local-First & Zero-Cloud Backend**: Runs entirely on your local machine using Python's `http.server` with custom CORS headers and zero mandatory external API keys.

---

## 🚀 Quickstart & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/abdussatarkhan/....._python-projects_......git
cd ....._python-projects_.....
```

### 2. Launch JARVIS

**Option A: Windows One-Click (Recommended)**
Double-click `START_JARVIS.bat` in the project root folder.

**Option B: Terminal Command**
```bash
python start_jarvis.py
```

The launcher will start the local HTTP server and automatically open your default browser to:
`http://localhost:8080/jarvis.html`

> [!IMPORTANT]
> When prompted by your browser, grant microphone permissions so JARVIS can hear your voice commands.

---

## 🖥️ Application & Operational Interface

<p align="center">
  <img src="screenshots/01_dashboard_preview.png" alt="JARVIS Voice Assistant & Cybernetic HUD Interface Preview" width="95%" />
</p>

> [!TIP]
> You can also explore [`dashboard.html`](dashboard.html) locally by double-clicking it in any modern browser for standalone interface inspection.

---

## 🗺️ Roadmap & Upcoming Enhancements

- [x] Local Python CORS web server with automatic browser launch
- [x] Speech recognition and voice synthesis loop
- [x] Cybernetic canvas HUD with audio frequency reactivity
- [ ] Local LLM integration (Ollama / Llama.cpp) for offline intelligence
- [ ] Hotword wake detection ("Hey Jarvis") using Porcupine / WebAssembly
- [ ] Home Assistant / IoT smart bulb control integration

---

## 👨‍💻 Author & Contact

Built and maintained by **Abdussatar** ([@abdussatarkhan](https://github.com/abdussatarkhan)).  
For technical discussions, collaboration, or queries, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/abdus-satar-5150813b5/) or [GitHub](https://github.com/abdussatarkhan).

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### 👨‍💻 Maintained by [Abdussatar (@abdussatarkhan)](https://github.com/abdussatarkhan)
Part of the **[Abdussatar Software Engineering & Systems Portfolio](https://github.com/abdussatarkhan)**.

⭐ If you find this project interesting, consider dropping a star! ⭐

</div>
