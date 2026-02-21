# 👋 Hi, I'm Raphael Mendes

**AI Engineer** focused on building hybrid AI systems that combine Large Language Models with deterministic validation, business logic, and real-world constraints.

I design AI applications that prioritize **reliability**, **performance**, and **structured reasoning** over hype.

---

## 🚀 Featured Projects

### 🔹 [**finai-companion**]
*AI-powered financial assistant combining conversational intelligence with deterministic financial calculations.*

**Problem:** Most financial AI tools either provide generic explanations or inaccurate AI-generated calculations.

**Solution:** Hybrid architecture with strict separation between LLM and calculation engine.

**Architecture:**
LLM Layer (Groq) → Natural language understanding
Deterministic Layer → Financial calculations (interest, compound growth)
Database Layer (SQLite) → User context persistence
UI Layer (Streamlit) → Interface

text

**Engineering Decisions:**
- Rule-based validation ensures numerical accuracy
- Context persistence simulates advisory continuity
- Modular design allows swapping LLM providers

**Stack:** `Python` `Groq` `Streamlit` `SQLite` `Prompt Engineering`

---

### 🔹 [**antifraude-bootcamp-ai102**]
*Document validation pipeline with OCR simulation and rule-based fraud detection.*

**Problem:** Manual validation of invoices and documents is slow and prone to human error.

**Solution:** End-to-end pipeline prioritizing deterministic validation over AI "guessing".

**Architecture:**
PDF Extraction (pdfplumber/Camelot) → Structured text
Validation Engine → CNPJ algorithm, date anomalies, value mismatches
Risk Scoring → Rule-based flags
UI Layer (Streamlit) → Reports

text

**Engineering Decisions:**
- Implemented Brazilian CNPJ check-digit algorithm from scratch
- Rule-engine approach (not AI-dependent)
- Regex-based structured parsing for consistency

**Stack:** `Python` `Streamlit` `pdfplumber` `Camelot` `Regex` `Validation Logic`

---

### 🔹 [**ai-voice-assistant-groq(Groq + LLM)**]
*Real-time conversational voice assistant optimized for speed.*

**Problem:** Most voice assistants suffer from latency (>2s) and rigid interaction flows.

**Solution:** Streaming pipeline achieving near-real-time response using Groq's high-throughput inference.

**Architecture:**
ASR (Whisper) → Speech-to-text
LLM (Groq) → <500ms inference
TTS (gTTS) → Voice synthesis
UI (Streamlit) → Interface

text

**Technical Focus:**
- Latency optimization (total round-trip < 2s)
- Streaming response handling
- Persona-controlled system prompting

**Stack:** `Python` `Groq` `Whisper` `gTTS` `Streamlit`

---

## 🧠 Engineering Philosophy

- **Prefer deterministic validation** over blind LLM trust
- **Separate AI reasoning from business logic** (modular architecture)
- **Build hybrid systems** (LLM + rules + databases)
- **Optimize for latency and usability** before scaling
- **Measure what matters** (response time, accuracy, reliability)

---

## 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| **Core** | Python, SQL, Git, System Design |
| **AI/ML** | LLMs (Groq, OpenAI), Prompt Engineering, ASR/TTS, Azure AI (AI-102 in progress) |
| **Frameworks** | Streamlit, FastAPI, GitHub Actions |
| **Focus Areas** | Generative AI, Hybrid Architectures, Document Intelligence, Voice Interfaces |

---

## 📌 Currently

- Preparing for **Microsoft AI-102 (Azure AI Engineer Associate)**
- Building **Teia do Saber** – AI-driven educational system with question generation and adaptive error tracking

---

## 📫 Connect

[![LinkedIn](https://www.linkedin.com/in/raphael-mendes-9ba7613a5/)

---

*"I care less about AI hype — and more about AI that works."*
