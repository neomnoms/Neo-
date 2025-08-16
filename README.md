# LLM-Powered College Board Meetings Curation Tool

## 📌 Overview
This project is a **phased system** for discovering colleges, collecting and organizing their **board meeting materials** (videos, minutes, transcripts), and enabling **AI-assisted search and summarization**.  
It supports both **manual** and **automated** workflows, with eventual **Retrieval-Augmented Generation (RAG)** integration for deeper insights.

Our goal is to provide a transparent, accurate, and customizable tool for **multi-institution tracking** that’s lightweight, budget-friendly, and adaptable for educational governance research.

---

## 🚀 Features
- **College Discovery** – Identify and list institutions with metadata:
  - Name
  - Website
  - Master folder for board meetings
  - Timing/frequency of updates
- **Meeting Source Collection** – Retrieve videos or minutes within a chosen date range.
- **Transcription** – Manual and automated pipelines for meeting content.
- **Data Processing & Search** – Chunk, store, and enrich content for context-aware AI responses.
- **Verification Loop** – Human-in-the-loop review with feedback capture.

---

## 🛠 Tech Stack
- **Language Model**: OpenAI, Ollama/Mistral (local LLM)
- **Data Processing**: Python (pandas, regex, JSON handling)
- **Transcription**: Whisper / API-based tools
- **Storage Formats**: CSV (initial), JSON (later)
- **Automation**: Web scraping (BeautifulSoup, requests), scheduled scripts
- **Search**: RAG framework with vector embeddings
- **Version Control**: GitHub

---

## 📂 Project Phases

### Step 1 – College Discovery
- **Phase 1:** Manual search & spreadsheet creation
- **Phase 2:** Automated scraping
- **Phase 3:** Continuous update workflow

### Step 2 – Meeting Source Collection
- **Phase 1:** Manual link gathering
- **Phase 2:** Automated retrieval
- **Phase 3:** Integration into searchable repository

### Step 3 – Transcription
- **Phase 1:** Easy, manual/semi-automated methods
- **Phase 2:** Full automation pipeline

### Step 4 – Data Processing & Context Management
- **Phase 1:** Context window organization
- **Phase 2:** RAG integration

### Step 5 – Verification & Feedback Loop
- **Phase 1:** Manual review
- **Phase 2:** Automated feedback tracking

---

## 📋 Deliverables
- Spreadsheet with 5 target Texas-based colleges (initial phase)
- At least 2 meetings per school in prototype phase (10 total)
- Linked videos/minutes
- Transcripts stored in CSV, later in JSON

---

## 👥 Team Roles
- **Karthik** – Project Management Lead
- **Naomi** – Coordination & Documentation
- **Shanecia** – LLM Prompt Development
- **Kaylee** – College research & spreadsheet creation
- **Nicolas** – Video link gathering & prototype dev
- **Stanley** – Transcription

---

## 📅 Current Status
- Prototype in development
- GitHub repository setup
- Manual data gathering in progress
- Initial automation exploration underway

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing
We welcome contributions! Please fork the repo, create a branch, and submit a pull request. For major changes, open an issue first to discuss.
