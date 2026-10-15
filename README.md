# 🎓 CogniFast Study — AI Study Companion

**An AI-assisted study companion prototype built collaboratively by Dev Joshi and Veer Sanghvi during a two-hour hackathon in November 2025.**

Upload a PDF of your study notes and explore generated quizzes, flashcards, mind maps, audio summaries, and a document-aware AI tutor.

**[🚀 Live demo](https://cognifast-study-yryuumj4dcvk9a3o3ebfzz.streamlit.app/) · [🏆 Devpost](https://devpost.com/software/pastify-ai-study-companion) · [🎥 Demo video](https://vimeo.com/1141644051)**

> **Project context:** This is a hackathon prototype developed with substantial AI coding assistance, not a production-ready or independently engineered application. Generated study content may contain mistakes; check important facts against your source material.

## Features

| Tool | What it does |
| --- | --- |
| 📝 Interactive Quiz | Generates practice questions with configurable difficulty and quantity |
| ⚡ Flashcards | Creates flashcards from uploaded notes |
| 📊 Mind Map | Presents a structured overview of key concepts |
| 🎧 Audio Summary | Produces a spoken summary |
| 💬 AI Tutor | Answers questions using the uploaded document as context |

## How to use

1. Open the [live demo](https://cognifast-study-yryuumj4dcvk9a3o3ebfzz.streamlit.app/) or run the app locally.
2. Enter your own **Groq API key** in the app and upload a PDF containing your notes.
3. Click **Analyze Document** to process the material and open the study tools.
4. Choose a tool, such as **Interactive Quiz**, and generate study content.
5. Use **New Document** to start over with another PDF.

**Privacy note:** Use notes you are comfortable sending to the services powering the app. Do not upload sensitive personal information or share API keys publicly. Review the app's handling of uploaded content before using it for private documents.

## Tech stack

| Category | Technology |
| --- | --- |
| Language | Python |
| Application UI | Streamlit, custom CSS |
| AI inference | Groq Cloud API; Llama model |
| PDF extraction | `pypdf` |
| Text-to-speech | `gTTS` |

## Run locally

```bash
git clone https://github.com/Veloce5/cognifast-study.git
cd cognifast-study
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt
streamlit run app.py
```

On Windows, activate the environment using `.venv\Scripts\activate`. Enter your own API key through the app interface; never commit it to the repository.

## Project background

This prototype was created collaboratively with **Veer** during a time-limited hackathon in November 2025. The goal was to explore how a single uploaded document could become several interactive learning experiences. The project relied heavily on AI-assisted development, and remains a prototype intended for demonstration and further learning.
