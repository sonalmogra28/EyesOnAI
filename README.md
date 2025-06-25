# EyesOnAI
A voice-controlled desktop assistant for the visually impaired, built to enable full hands-free system navigation. Developed during the UC Berkeley AI Hackathon 2025 (EyesOnAI) to empower digital accessibility through AI.
# 🎙️ Accessibility Assistant  
### Built at UC Berkeley EyesOnAI 2025 Hackathon

A multimodal voice-controlled assistant for the visually impaired, capable of recognizing speech, automating system tasks, responding via synthesized voice, and running through both web and desktop interfaces.

## 🔍 Overview

The Accessibility Assistant is a Python-based application that helps blind and visually impaired users **navigate their desktop hands-free**. It uses voice commands to:
- Open applications
- Search on the web
- Click buttons
- Read back results
- Interact using natural voice feedback


## 🛠️ Tech Stack

| Functionality        | Libraries / Tools |
|---------------------|-------------------|
| 🎤 Voice Input       | `sounddevice`, `wavio`, `speech_recognition`, `keyboard` |
| 🧠 Voice-to-Intent   | `VoiceRecognition`, `replicate`, `Google Gemini`, `vapiassist` |
| 🗣️ Voice Output      | `sfx`, `LMNT Speech`, `ElevenLabs` |
| 💻 Automation        | `pyautogui`, `subprocess`, `os`, `psutil`, `shutil`, `glob`, `platform` |
| 🌐 Web Control       | `selenium`, `webbrowser`, `requests` |
| 🧱 Backend API       | `Flask` |
| 🖥️ GUI Option        | `PyQt5` |
| 🧠 Custom Commands   | `AccessibilityCommands`, `computer_commands.py` |
| 📚 NLP + Reasoning   | `replicate`, `google.generativeai` |
| 🧪 Others            | `threading`, `json`, `signal`, `tempfile`, `PIL` |

---

## 🚀 Features

- **Real-time voice command recognition**
- **AI-enhanced understanding of natural phrases**
- **System automation for keyboard, apps, mouse, and search**
- **Voice response for confirmation and output**
- **Modular command structure**
- **Both Flask and PyQt5 interfaces**
- **Web automation via Selenium*

## 📸 Demo Commands

```text
"Open Chrome and search relaxing music"
"Start YouTube and play meditation sounds"
"Open Notepad"
"Take a screenshot"
"Close the current window"
"set the brightness to 10%"

### 🧾 Prerequisites:
- Python 3.8+
- OS: Windows/macOS/Linux (supports desktop automation)
- Browser: Chrome (for Selenium automation)
- APIs: Gemini, Replicate, ElevenLabs (optional)

### 🧪 Run the app
```bash
python ./app.py

export GOOGLE_API_KEY="..."
export REPLICATE_API_TOKEN="..."
export ELEVENLABS_API_KEY="..."


