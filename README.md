# 🌸 MindWell – A Youth Mental Wellness Platform  

> *An AI-powered platform for young mental wellness combining emotional support, self-reflection, safe communities, and engaging activities.*  

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Made%20With-❤%20%26%20Python-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Platform-Web-orange?style=for-the-badge" />
</p>

---

## 📌 Table of Contents
- [Introduction](#-introduction)  
- [Problem Statement](#-problem-statement)  
- [Features](#-features)  
- [Tech Stack](#-tech-stack)  
- [APIs & Models Used](#-apis--models-used)  
- [How It Works](#-how-it-works)  
- [Screenshots / Demo](#-screenshots--demo)  
- [Future Scope](#-future-scope)  
- [Contributors](#-contributors)  

---

## 💡 Introduction
Mental health challenges among youth are increasing due to stress, anxiety, and lack of safe outlets.  
*MindWell* is a holistic mental wellness platform designed to:  
- Support youth through *AI-driven companions*  
- Encourage *self-reflection* via diary + emotion detection  
- Provide *safe anonymous communities* for discussion  
- Promote *fun & positivity* through games and quotes  

---

## 🚩 Problem Statement
- Limited *interactive mental health platforms* tailored for young people  
- Lack of *anonymous safe spaces* to share experiences  
- Engagement gap in existing apps → users drop out quickly  

---

## ✨ Features

### 🏠 Home Page (Quotes Feature)
- Motivational quotes (via *ZenQuotes API*)  
- New quote on every refresh or click  

---

### 🤖 AI Emotional Chat Companion
- *Powered by Google Gemini* (gemini-2.5-pro)  
- Modes:  
  - 💬 Text Chat  
  - 🎙 Voice-to-Text (Web Speech API)  
  - 📞 Call Mode (Speech-to-Speech)  
  - 🧑‍🎤 3D Anime Model Mode (requires call + 3D enabled)  
- Fetches real-time *helplines/resources* via *Google Search API*  

---

### 📖 My Diary (Emotion Detection)
- Write daily reflections  
- Predicts mood using Hugging Face model:  
  j-hartman/emotional-english-distilroberta-base  
- Saves entries + predicted moods  
- *Visual graphs* for mood trends  

---

### 🌍 Community Feature
- Create/join communities *anonymously*  
- Uses *Perspective API* (Google Jigsaw) for moderation  
  - Blocks abusive/vulgar names/comments  
- Anonymous usernames auto-generated  
- Requires *50 coins* to create a new community  

---

### 🎮 Single Player Dance Game
- Split-screen: *User video vs Reference video*  
- Uses *Google Mediapipe* for pose detection + scoring  
- Encourages physical + mental wellness  

---

### 🪙 Reward System (Gamification)
- Earn coins by:  
  - Daily logins  
  - Reading quotes  
  - Using platform features  
  - Maintaining streaks  
- Use coins to create communities  

---

## 🛠 Tech Stack

*Frontend:*  
HTML CSS JavaScript  

*Backend:*  
Flask (Python)  

*Visualization:*  
Charts.js 

*Other Tools:*  
Mediapipe  

---

## 🔌 APIs & Models Used
- 🌸 [ZenQuotes API](https://zenquotes.io/) → Random motivational quotes  
- 🤖 [Google Gemini (gemini-2.5-pro)](https://ai.google/) → AI chatbot  
- 🔎 [Google Search API](https://developers.google.com/custom-search) → Helpline/resource info  
- 🎙 [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) → Voice features  
- 🧠 [Hugging Face Model](https://huggingface.co/j-hartman/emotional-english-distilroberta-base) → Emotion detection in diary  
- 🛡 [Perspective API](https://perspectiveapi.com/) → Community moderation  
- 🎮 [Google Mediapipe](https://developers.google.com/mediapipe) → Pose detection for dance game  

---
