# 🧠 InfoMorph — AI-Powered Information Transformation Platform

**Team:** Muhammad Tallal Eatazaz (21I-0637), Ahmad Moazam (21I-0436), Hamza Rehman (21I-0478)  
**Supervisor:** Dr. Adnan Tariq  
**Department:** Computer Science, FAST NUCES Islamabad  
**Session:** 2024–2025  

---

## 📘 Introduction
**InfoMorph** transforms lengthy web articles into concise, engaging video summaries narrated by an AI anchor.  
It combines **Natural Language Processing (NLP)**, **Text-to-Speech (TTS)**, and **Deep Learning–based Video Generation** to make information easier to understand, more engaging, and accessible across languages.

By integrating summarization, translation, audio synthesis, and video rendering in one automated workflow, InfoMorph helps users consume complex information quickly and intuitively.

---

## 🚨 Problem Statement
In today’s fast-paced digital world, people—especially younger audiences—face **information overload**.  
They often rely on short-form videos that are convenient but lack depth or accuracy.  
InfoMorph addresses this by transforming textual content into factually accurate, short multimedia summaries that maintain both engagement and comprehension.

---

## 🎯 Scope
InfoMorph:
- Scrapes web content from online sources relevant to user topics.  
- Summarizes text using advanced NLP models.  
- Translates summaries into multiple languages (English ↔ Urdu).  
- Converts text into realistic audio narration.  
- Generates AI-anchored news-style videos using deep learning.  

Each video is between **30–120 seconds**, optimized for easy social media sharing while maintaining informative value.

---

## 🧩 System Modules

| # | Module | Description |
|---|---------|-------------|
| 1 | **UI/UX Design** | Interactive frontend for topic selection, playback, and feedback. |
| 2 | **Web Scraping** | Asynchronous article extraction with domain filtering and robots.txt compliance. |
| 3 | **Summarization** | Uses LLMs (Pegasus / Gemini) for coherent and concise summarization. |
| 4 | **Translation** | Implements MarianMT and transliteration for Urdu output. |
| 5 | **Text-to-Speech (TTS)** | Converts summaries into speech with adjustable playback speed. |
| 6 | **Video Generation (FOMM)** | Uses First Order Motion Model to animate an AI anchor synchronized with narration. |
| 7 | **Integration & Deployment** | Combines all modules using FastAPI (backend) and Next.js (frontend). |

---

## ⚙️ System Architecture

**N-Layered Architecture:**
1. **Presentation Layer:** Next.js frontend handling user interaction.  
2. **Business Logic Layer:** Core modules for scraping, summarization, translation, and video generation.  
3. **Persistence Layer:** Handles data access and integration.  
4. **Database Layer:** Manages stored summaries, feedback, and generated media using Supabase.

This architecture ensures scalability, maintainability, and independent module development.

---

## 🧰 Technology Stack

| Category | Tools / Frameworks |
|-----------|--------------------|
| **Frontend** | Next.js, TailwindCSS |
| **Backend** | FastAPI (Python) |
| **Database** | Supabase |
| **NLP / AI Models** | Pegasus (Summarization), MarianMT (Translation), Gemini / GPT |
| **Scraping** | aiohttp, newspaper3k, Google Custom Search API |
| **Speech Synthesis** | ElevenLabs API / Open-Source TTS |
| **Video Generation** | First Order Motion Model (FOMM) |
| **Media Management** | Cloudinary |
| **Testing** | Pytest, Unit Testing Framework |
| **Deployment** | Docker / Render / Cloud Infrastructure |

---

## 🧪 Testing
A suite of **unit tests** was developed to ensure module-level reliability and system integration accuracy.  
These tests covered:

- URL collection & filtering  
- Asynchronous scraping  
- Retry mechanisms for unstable connections  
- Translation validation  
- Text-to-speech generation  
- Supabase feedback storage  

All tests passed successfully, ensuring robustness and data consistency across modules.

---

## 📈 Performance Benchmarks

| Metric | Result |
|--------|--------|
| Summary generation time | ≤ 20 seconds (for ≤1000-word articles) |
| Video generation time | < 2 minutes |
| Supported concurrent users | 100+ |
| Articles processed per hour | 1000+ |
| System uptime | 99.5% |

---

## 🚀 Future Enhancements
- **Multilingual Support:** Expand to global languages beyond English and Urdu.  
- **User-Guided Summarization:** Allow users to adjust tone, length, or focus of summaries.  
- **Real-Time Streaming:** Generate live AI-narrated summaries from ongoing news feeds.  
- **Advanced AI Anchors:** Integrate avatars with expressive gestures and diverse voices.  
- **Mobile & Offline Apps:** Native Android/iOS apps with local caching and offline playback.  

---

## 👥 Individual Contributions

### **Muhammad Tallal Eatazaz**
I worked on the system integration, backend APIs, and user interface. This included setting up the FastAPI backend, building the authentication and topic selection pages, and connecting the web application to the summarization and video generation pipelines. I also implemented the URL filtering and compliance module using the Google Custom Search API and robots.txt parser, ensuring ethical and efficient content collection. Through this work, I learned how to structure modular backends, manage API communication between AI components, and design practical user workflows for AI-driven systems.

---

### **Ahmad Moazam**
I focused on improving content quality and managing data flow across modules. My work involved cleaning and filtering scraped articles, validating language detection, and ensuring that only relevant English content was passed to the summarization module. I also worked on the frontend interfaces for topic and content selection, coordinating with the backend to provide smooth user interactions. This experience strengthened my understanding of data preprocessing, system reliability, and full-stack collaboration in AI-based software projects.

---

### **Hamza Rehman**
InfoMorph is a system that takes online news articles and turns them into short multimedia summaries. It combines text summarization, translation, speech synthesis, and video generation to make information easier to follow and more accessible. The project brought together different parts of artificial intelligence — language models, deep learning, and computer vision — in one workflow.

I worked on the data and language modules. This included writing the web-scraping scripts, preparing the text data, and setting up the summarization and translation models. I used **Pegasus** for text summarization and **MarianMT** for translation. I also tested and evaluated the summaries using **ROUGE** and **BLEU** metrics, and helped connect these components into a working system. Through this, I learned how to design and evaluate AI systems that handle real-world text and media, and how to bring together research methods and software development in a practical way.

---

## 🧾 License
Final Year Project © 2025  
**National University of Computer and Emerging Sciences (FAST-NUCES), Islamabad**

---

