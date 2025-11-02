# 🧠 InfoMorph — AI-Powered Information Transformation Platform

**Team:** Muhammad Tallal Eatazaz (21I-0637), Ahmad Moazam (21I-0436), Hamza Rehman (21I-0478)  
**Supervisor:** Dr. Adnan Tariq  
**Department:** Computer Science, FAST NUCES Islamabad  
**Session:** 2024–2025  

---

## 📘 Introduction
**InfoMorph** transforms lengthy web articles into concise, engaging video summaries narrated by an AI anchor.  
It combines **NLP**, **TTS**, and **deepfake video synthesis** to make learning and information consumption faster and more interactive.

---

## 🚨 Problem Statement
Information overload and clickbait culture make it hard to consume authentic, summarized content.  
Young users prefer short-form media but lose depth and context.  
InfoMorph bridges this gap using **AI summarization** and **video narration**.

---

## 🎯 Scope
InfoMorph:
- Scrapes web content from relevant sources.  
- Summarizes it using NLP and LLMs.  
- Converts text into natural-sounding audio (English/Urdu).  
- Generates a talking-head video using the **First Order Motion Model (FOMM)**.  
- Outputs short 30–120 second video summaries optimized for social media.

---

## 🧩 Modules

| # | Module | Description |
|---|---------|-------------|
| 1 | UI/UX Design | Interactive web interface for selecting topics and playing summaries. |
| 2 | Web Scraping | Asynchronous scraping with domain filtering and robots.txt compliance. |
| 3 | Summarization | NLP-based summarization using LLM pipelines (Gemini / custom models). |
| 4 | Translation | Converts English summaries to Urdu with transliteration. |
| 5 | Text-to-Speech | Uses ElevenLabs or open-source TTS for natural narration. |
| 6 | Video Generation | AI Anchor creation using the First Order Motion Model. |
| 7 | Integration | FastAPI backend + Next.js frontend deployment. |

---

## ⚙️ System Architecture

**N-Layered Architecture:**
1. Presentation Layer – Frontend interface.  
2. Business Logic Layer – NLP, TTS, and video generation.  
3. Persistence Layer – Data management and integration.  
4. Database Layer – Supabase for feedback and summary storage.

---

## 🧰 Tech Stack

| Category | Tools |
|-----------|-------|
| Frontend | Next.js |
| Backend | FastAPI (Python) |
| Database | Supabase |
| NLP / AI | LLM (Gemini / GPT), langdetect, translate |
| Scraping | aiohttp, newspaper3k, Google CSE API |
| TTS | ElevenLabs API |
| Video | First Order Motion Model (FOMM) |
| Deployment | Cloudinary (media), Docker/Render (optional) |

---

## 🧪 Testing
Unit tests were written for:
- URL collection & filtering  
- Scraping concurrency  
- Retry mechanism  
- Article translation  
- Text-to-speech  
- Database feedback storage  

✅ All tests passed, ensuring stable and performant modules.

---

## 📈 Performance Benchmarks

| Metric | Result |
|--------|--------|
| Summary generation time | ≤ 20 seconds (90% cases) |
| Video generation time | < 2 minutes |
| Concurrent users supported | 100+ |
| Articles processed/hour | 1000 |
| Uptime | 99.5% |

---

## 🚀 Future Enhancements
- Multilingual summarization.  
- User-guided summary focus & tone.  
- Real-time video generation for live feeds.  
- Emotion-based AI anchors.  
- Mobile app with offline playback.

---

## 👥 Contributors

| Name | Role | Major Work |
|------|------|-------------|
| **Muhammad Tallal Eatazaz** | Backend & UI | URL filtering, login/signup UI |
| **Hamza Rehman** | Backend & Frontend | Asynchronous scraping, retry logic |
| **Ahmad Moazam** | Data Handling | Article filtering, topic selection page |

---

## 🧾 License
Final Year Project © 2025  
**National University of Computer and Emerging Sciences (FAST-NUCES), Islamabad**

#Complete Code on the Final Branch
