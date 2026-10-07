# Hey, I'm Donald! 👋

I'm a Computer Science and Information Security student at John Jay College of Criminal Justice. I love building things at the intersection of security, AI, and full-stack development — whether that's a cryptographic password manager, a real-time computer vision app, or an automated threat intelligence pipeline.

I was selected from 3,000+ applicants for the **Break Through Tech AI/ML Fellowship at Cornell Tech**, where I'm deepening my foundations in machine learning and working on industry projects. I'm also a **Google x BASTA Software Engineering Fellow**, working 1:1 with a Google SWE to sharpen my problem-solving and interview performance. Most recently, through my **AI Industry Immersion Experience at John Jay**, I've been building out a threat intelligence automation pipeline using n8n, Flowise, Groq, and HuggingFace BERT for real-time IoC extraction and threat triage.

---

### 💼 Experience

**AI/ML Fellow** — Break Through Tech, Cornell Tech *(2026 – Present)*
- Selected from 3,000+ applicants for a year-long intensive ML fellowship; building ML models for marketing with Witomni

**Software Engineering Fellow** — Google x BASTA Code2Career *(Fall 2026)*
- Selected for 1:1 mentorship with a Google Software Engineer
- Optimized DSA solutions through active code review and technical interview coaching

**Industry Immersion Experience – AI** — John Jay College *(Jan 2026 – Present)*
- Engineered an n8n workflow to automate incident response, processing SIEM event logs with real-time alerts
- Built a threat intelligence RAG pipeline using Flowise and Groq for IoC extraction and refinement
- Applied HuggingFace BERT NLP sentiment analysis to flag and prioritize critical threats

---

### ⭐ Featured Projects

#### 🤖 JumboVision — Real-Time Vision Assistant for the Visually Impaired
*Team hackathon project — built with collaborators.*

**What I Did:** Built the core backend pipeline for a hackathon accessibility tool that helps visually impaired users understand their surroundings in real time. I set up the WebSocket connection between the Next.js frontend and a FastAPI backend, integrated YOLOv8n for live object detection, and engineered the spatial reasoning logic that converts detections into natural-language descriptions (e.g., *"there's a chair on your left, close to you"*) relayed back to the user via text-to-speech.

**Tools:** `Python` `FastAPI` `YOLOv8n` `WebSockets` `Next.js` `TypeScript` `Web Speech API`

**Result:** Delivered a fully functional accessibility app over a single weekend with real-time object detection, spatial position awareness (left/center/right), depth estimation (close/medium/far), and a fully TTS-navigable frontend.

🔗 [View Project](https://github.com/DKAT-9/JumboVision)

---

#### 🔐 CipherVault — Local Encrypted Password Manager
**What I Did:** Built a command-line password manager from scratch that keeps all credentials stored locally with zero cloud dependency. Implemented AES-256-GCM authenticated encryption and a scrypt key derivation function to turn the master password into a secure encryption key. Added a canary value mechanism to verify the master password on login without exposing any real credentials.

**Tools:** `Python` `AES-256-GCM` `scrypt` `cryptography` library

**Result:** A fully functional, cryptographically sound password manager with add, retrieve, list, and delete operations — all behind a master password that is never stored anywhere.

🔗 [View Project](https://github.com/bananadonn/CipherVault)

---

### 🛠️ Tech Stack

**Languages:** Python, JavaScript, TypeScript

**AI / ML:** YOLOv8, HuggingFace Transformers, BERT, RAG, Flowise, Groq

**Web & Mobile:** Next.js, React Native, Expo, FastAPI, Django, Node.js, discord.js

**Tools & Platforms:** Supabase, n8n, Git, GitHub, Tailwind CSS / NativeWind

**Security:** AES-256-GCM, scrypt KDF, MITRE ATT&CK, SIEM log analysis

---

### 📁 All Projects

| Project | Description | Stack |
|---|---|---|
| [JumboVision](https://github.com/DKAT-9/JumboVision) | Real-time object detection & TTS accessibility tool | Next.js, FastAPI, YOLOv8 |
| [CipherVault](https://github.com/bananadonn/CipherVault) | CLI password manager with AES-256-GCM encryption | Python |
| [Talking-Stick-Bot](https://github.com/bananadonn/Talking-Stick-Bot) | Discord bot for admin-moderated voice channel discussions | Node.js, discord.js |
| [SimpleLogger](https://github.com/bananadonn/SimpleLogger) | Mobile workout tracker with split management | React Native, Expo, Supabase |
| [IIE-John-Jay](https://github.com/bananadonn/IIE-John-Jay) | AI & cybersecurity capstone — RAG pipelines, automation, threat intelligence | Python, Flowise, n8n |
| [Echoes](https://github.com/bananadonn/Echoes_Hack_Brooklyn) | Location-based audio storytelling for NYC, built in 48 hours | JavaScript |

---

### 📬 How to Reach Me

📧 reithdonald04@gmail.com

---

### ⚡ Fun Fact

I go to a college best known for criminal justice and criminology — and ended up writing encryption algorithms and threat intelligence pipelines. Closer to the same thing than you'd think.
