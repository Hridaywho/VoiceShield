# 🎙️ VoiceShield – AI-Powered Emotion & Aggression Detection

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python" alt="Python Badge">
  <img src="https://img.shields.io/badge/Flask-Backend-black?logo=flask" alt="Flask Badge">
  <img src="https://img.shields.io/badge/Socket.IO-Realtime-green?logo=socketdotio" alt="Socket.IO Badge">
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License Badge">
  <img src="https://img.shields.io/badge/Status-Active-success" alt="Status Badge">
</p>

> **VoiceShield** is an intelligent, real-time **emotion and aggression detection system** that fuses **voice tone** and **facial expression analysis** to help identify aggression levels and support proactive safety interventions.

---

## 🧠 What Is VoiceShield?

VoiceShield uses **AI emotion recognition** to read both **facial cues** and **audio tone**, combining them into a unified **aggression score**.  
Built for **security systems**, **education monitoring**, and **mental wellness platforms**, it helps humans respond faster — with empathy and awareness.

<p align="center">
  <img src="https://img.shields.io/badge/Emotion-Detection-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Real--Time-Processing-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/AI-Driven-purple?style=for-the-badge">
</p>

---

## 🚀 Key Features

✨ **Dual Detection Engine** – Facial + voice emotion analysis  
⚡ **Real-time AI Processing** – Instant detection using Flask & Socket.IO  
🎨 **Responsive Dashboard** – Tailwind-styled modern interface  
🔊 **Audio Visualization** – Real-time waveform display  
📊 **Aggression Score Index** – Combined emotion-based scoring  
🔐 **Privacy-Focused** – Local inference, no cloud dependency  

---

## 🧩 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | HTML5, CSS3, JavaScript (ES6+), Tailwind CSS, face-api.js, Socket.IO, Web Audio API |
| **Backend** | Python 3.8+, Flask, Flask-SocketIO, NumPy, librosa, pyAudioAnalysis |

---

## ⚙️ Installation Guide

### 🖥️ Backend Setup
```bash
# Clone the repository
git clone https://github.com/your-username/VoiceShield.git
cd VoiceShield/backend

# Install dependencies
pip install -r requirements.txt

# Start the server
python server.py
```
✅ Flask will start at: `http://localhost:8080`

---

### 🌐 Frontend Setup
Open `index.html` directly or run a local dev server:
```bash
# Using Python
python -m http.server 8000

# Or Node.js
npx serve .
```
Access at: `http://localhost:8000`

---

## 🧠 How It Works

1. **Camera & Microphone Access** – Capture live inputs  
2. **AI Emotion Analysis** – Detect emotional patterns from face and voice  
3. **Aggression Scoring** – Combine both analyses into one intelligent score  
4. **Visual Feedback** – Display real-time graphs and aggression indicators  

| Aggression Level | Description | Recommended Action |
|------------------|--------------|--------------------|
| 0–40% | Calm | No action needed |
| 40–60% | Low Aggression | Continue monitoring |
| 60–80% | Moderate Aggression | Monitor closely |
| 80–100% | High Aggression | Immediate intervention |

---

## 🧰 API Reference

### 🔄 WebSocket Events
**Client → Server**
- `facial_analysis`: Send facial expression data  
- `audio`: Send audio data for analysis  

**Server → Client**
- `emotion_analysis`: Receive combined emotion results  
- `status`: Connection updates  
- `error`: Error notifications  

### 🌐 REST Endpoints
| Method | Endpoint | Description |
|---------|-----------|-------------|
| GET | `/health` | Server status check |
| GET | `/api/analysis` | Get current AI analysis |
| GET | `/` | Main application |

---

## 🛠️ Troubleshooting

| Problem | Possible Solution |
|----------|------------------|
| 🎥 Camera not working | Enable browser permissions |
| 🎙️ Mic access denied | Allow mic permissions |
| 🔌 Connection error | Ensure Flask is running on port 8080 |
| 🧩 Model load failed | Check internet for face-api.js |
| 🔇 Audio missing | Verify mic input & browser support |

---

## 🧱 Project Structure
```
VoiceShield/
├── backend/
│   ├── server.py
│   ├── email_notifier.py
│   ├── requirements.txt
├── frontend/
│   ├── index.html
│   ├── styles/
│   ├── scripts/
└── README.md
```

---

## 🔐 Security Practices
- 🔒 Use **HTTPS** for production  
- 🔑 Add **user authentication** for secured use  
- 🧾 Sanitize inputs to prevent injection  
- 🕵️ Ensure **data privacy compliance**  

---

## 🧭 Future Roadmap
- [ ] Cloud AI integration for enhanced accuracy  
- [ ] Mobile app version  
- [ ] Multi-language support  
- [ ] Historical emotion analytics  
- [ ] Custom model training  

---

## 💬 Support & Contact
If you encounter issues:
- 🧩 Review troubleshooting above  
- 🪄 Check browser console & server logs  
- 📨 Open a GitHub issue with full details  

---

## 🌟 Inspiration
> “Technology should not just recognize emotion — it should help us understand it.”

VoiceShield blends **AI and empathy**, empowering real-time awareness and intelligent safety.

---

<p align="center">
  <b>⭐ If you like this project, consider giving it a star on GitHub!</b><br>
  <i>Let's make AI emotionally intelligent.</i>
</p>
