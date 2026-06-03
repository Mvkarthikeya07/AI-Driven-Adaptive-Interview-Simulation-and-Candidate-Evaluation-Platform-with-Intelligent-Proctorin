<div align="center">

<img src="https://img.shields.io/badge/AI--Powered-Interview%20Platform-6C63FF?style=for-the-badge&logo=robot&logoColor=white" />

# 🤖 AI-Driven Adaptive Interview Simulation & Evaluation Platform

### *Intelligent Proctoring · Adaptive Questioning · Automated Scoring · Performance Analytics*

<br/>

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-2.x-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=flat-square&logo=sqlite&logoColor=white)](https://sqlite.org)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Head%20Pose-0F9D58?style=flat-square&logo=google&logoColor=white)](https://mediapipe.dev)
[![Chart.js](https://img.shields.io/badge/Chart.js-Visualization-FF6384?style=flat-square&logo=chart.js&logoColor=white)](https://chartjs.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)
[![Hackathon](https://img.shields.io/badge/AXIOML%202026-National%20Hackathon-FF4500?style=flat-square&logo=trophy&logoColor=white)](#-hackathon-recognition)

<br/>

> **A production-grade, full-stack AI interview simulation platform** that replicates real-world technical interviews through adaptive question generation, automated response evaluation, and intelligent behavioral proctoring — enabling a fully autonomous, scalable, and tamper-resistant candidate assessment environment.

<br/>

[🚀 Quick Start](#%EF%B8%8F-installation--setup) · [🧠 Architecture](#-system-architecture) · [📸 Screenshots](#-application-screenshots) · [⚙️ Features](#-core-features) · [🤝 Contributing](#-contributing)

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Highlights](#-key-highlights)
- [Core Features](#-core-features)
- [Application Screenshots](#-application-screenshots)
- [System Architecture](#-system-architecture)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Installation & Setup](#%EF%B8%8F-installation--setup)
- [Interview Workflow](#-interview-workflow)
- [Proctoring System](#-intelligent-proctoring-system)
- [Evaluation Engine](#-ai-evaluation-engine)
- [Performance Reports](#-performance-reports)
- [Hackathon Recognition](#-hackathon-recognition)
- [Roadmap](#-roadmap)
- [License](#-license)

---

## 🌐 Overview

The **AI-Driven Adaptive Interview Simulation Platform** is a full-stack intelligent system built to automate the end-to-end interview process — from candidate authentication to question delivery, real-time proctoring, AI-based answer evaluation, and structured performance reporting.

The platform addresses a critical gap in modern recruitment and interview preparation: the lack of **intelligent, adaptive, and secure mock interview environments**. By dynamically adjusting difficulty based on candidate performance and monitoring behavioral integrity, the system closely mimics the rigor and conditions of real-world technical interviews.

### What Makes This Different

| Traditional Mock Interviews | This Platform |
|---|---|
| Static question banks | ✅ Adaptive AI-generated questions |
| Manual evaluation | ✅ Automated scoring with rubrics |
| No proctoring | ✅ Full behavioral monitoring |
| Generic feedback | ✅ Personalized improvement plans |
| No history tracking | ✅ Cross-session progress analytics |

---

## ⚡ Key Highlights

```
┌─────────────────────────────────────────────────────────────────┐
│  🎯  Adaptive Engine       Difficulty scales with performance    │
│  🧠  AI Evaluation         Multi-criteria automated scoring      │
│  🔒  Proctoring            Browser + webcam behavioral analysis  │
│  📊  Analytics             Radar charts + question-level reports │
│  ⏱️  Real Conditions       60s timers, no repeats, live flow     │
│  📈  Progress Tracking     Full interview history with flags     │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🔧 Core Features

### 🎯 Adaptive Interview Engine
- Dynamically adjusts question difficulty: **Easy → Medium → Hard**
- Role-specific question banks for 8+ technical domains
- Zero question repetition within a single session
- Supports both **conceptual** and **coding** questions

### 🤖 AI-Powered Answer Evaluation
- Multi-criteria scoring across: conceptual correctness, technical depth, clarity, logical structure, and relevance
- Per-question scoring with an aggregated overall interview score
- Automated **confidence indicator** based on response quality

### 🔒 Intelligent Proctoring System
- Fullscreen enforcement with ESC key detection
- Tab switching and window blur monitoring
- Copy-paste and developer tools blocking
- **Webcam integration** with MediaPipe-based head pose detection
- Auto-submission after **3 security violations**

### 📊 Structured Performance Analytics
- Radar chart visualization of skill dimensions
- Question-by-question breakdown with reference answers
- Improvement suggestions per question
- Plagiarism analysis on responses
- Confidence level estimation

### 📈 Interview History & Progress
- Persistent storage of all sessions across time
- Security status tagging: **Completed / Cheated**
- Cross-session trend analysis and score tracking

---

## 📸 Application Screenshots

### 🔐 Authentication — Login Interface

> Secure email/password login before accessing the interview environment.

![Login Interface](https://github.com/user-attachments/assets/76c1d2b0-a633-481b-9337-d469f4574c52)

---

### 🔑 Password Reset System

> Secure credential recovery for returning candidates.

![Password Reset](https://github.com/user-attachments/assets/ab3970e7-99f6-4dc0-a43e-dad4ac731d01)

---

### 🧑‍💻 Interview Dashboard

> Central hub for launching new sessions — role selection and interview type configuration.

![Interview Dashboard](https://github.com/user-attachments/assets/999bb613-5344-4112-be60-c1f1f1149ae7)

---

### 🎯 Role & Mode Selection

> Choose from 8+ technical roles and 2 interview modes.

![Role Selection 1](https://github.com/user-attachments/assets/300336a8-0ad8-41a7-bd83-395e83460cf1)

![Role Selection 2](https://github.com/user-attachments/assets/bd914a9b-79db-44c9-8a5f-60f3ea67a363)

**Available Roles:**
`Software Engineer` · `Data Scientist` · `ML Engineer` · `Frontend Developer` · `Backend Developer` · `DevOps Engineer` · `Cybersecurity Analyst` · `Cloud Engineer`

**Interview Modes:**
`Technical Interview` · `Behavioral Interview`

---

### 🤖 AI Proctored Interview Activation

> Full-screen and webcam access are required before the interview begins — ensuring a controlled, monitored environment.

![Proctored Mode Activation](https://github.com/user-attachments/assets/e71881b5-29a3-4ed1-8a87-cfe0f72c1b62)

---

### ⚠️ Security Violation Detection

> Real-time violation warnings with automatic session termination after 3 infractions.

![Security Violation 1](https://github.com/user-attachments/assets/5e993a60-06d4-43c8-87c5-e42ad44890f9)

![Security Violation 2](https://github.com/user-attachments/assets/e01f66a1-e83c-4619-a1e8-ebd193e204d2)

---

### ⏱ Live Interview Question Interface

> Real-time interview environment with countdown timer, answer submission box, and live webcam monitoring.

![Interview Interface](https://github.com/user-attachments/assets/a74704ee-0adc-4af6-b126-2eff2c2d5cef)

---

### 📊 AI-Generated Performance Report

> Comprehensive post-interview evaluation including an overall score and radar chart visualization.

![Performance Report 1](https://github.com/user-attachments/assets/8c2fcdd9-0d21-40bc-9e8b-7c6b8da0aa36)

![Performance Report 2](https://github.com/user-attachments/assets/a346b3c3-75b8-4381-a5c1-29e1608f8415)

---

### 📋 Detailed Answer Evaluation

> Question-by-question breakdown with candidate answers, reference answers, scores, and improvement tips.

![Answer Evaluation 1](https://github.com/user-attachments/assets/4df613de-4266-440b-a612-4611dcba9bba)

![Answer Evaluation 2](https://github.com/user-attachments/assets/d635213b-4aa8-43cf-9478-f30dd47deccf)

---

### 📈 Interview History & Progress Tracking

> Full session history with role, type, score, date, and security flag — enabling long-term progress monitoring.

![Interview History](https://github.com/user-attachments/assets/9a1dfd6d-5fd2-4326-9533-6d06a65d36ed)

---

## 🏗 System Architecture

```
┌──────────────────────────────────────────────────────────────────────┐
│                        CLIENT (Browser)                              │
│   HTML5 · CSS3 · JavaScript · Chart.js · MediaPipe (WASM)           │
│   Proctoring Layer: Fullscreen · Tab · Blur · Paste · DevTools       │
└───────────────────────────┬──────────────────────────────────────────┘
                            │ HTTP / REST
┌───────────────────────────▼──────────────────────────────────────────┐
│                     FLASK APPLICATION LAYER                          │
│                                                                      │
│  ┌─────────────┐  ┌──────────────────┐  ┌──────────────────────┐   │
│  │ auth_routes │  │ interview_routes  │  │   report_routes      │   │
│  └─────────────┘  └──────────────────┘  └──────────────────────┘   │
└───────────────────────────┬──────────────────────────────────────────┘
                            │
┌───────────────────────────▼──────────────────────────────────────────┐
│                        AI ENGINE                                     │
│                                                                      │
│  adaptive_engine.py   →  Difficulty progression logic               │
│  question_generator.py →  Role-aware question synthesis             │
│  evaluator.py         →  Multi-criteria answer scoring              │
│  fairness.py          →  Score normalization & calibration          │
│  plagiarism.py        →  Response originality analysis              │
│  report_generator.py  →  Structured report compilation              │
└───────────────────────────┬──────────────────────────────────────────┘
                            │
┌───────────────────────────▼──────────────────────────────────────────┐
│                     DATA LAYER (SQLite + SQLAlchemy)                 │
│   Users · Sessions · Questions · Responses · Scores · Violations    │
└──────────────────────────────────────────────────────────────────────┘
```

---

## 📂 Project Structure

```
ai-interview-platform/
│
├── app.py                        # Application entry point
├── config.py                     # Environment configuration
├── requirements.txt              # Python dependencies
│
├── ai_engine/
│   ├── adaptive_engine.py        # Difficulty progression logic
│   ├── evaluator.py              # Multi-criteria answer scoring
│   ├── fairness.py               # Score normalization
│   ├── plagiarism.py             # Response originality detection
│   ├── question_generator.py     # Role-specific question synthesis
│   └── report_generator.py       # Performance report compilation
│
├── database/
│   ├── db.py                     # Database connection manager
│   └── models.py                 # SQLAlchemy ORM models
│
├── routes/
│   ├── auth_routes.py            # Login, register, password reset
│   ├── interview_routes.py       # Session management, Q&A flow
│   └── report_routes.py          # Report generation endpoints
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── interview.html
│   ├── coding_interview.html
│   ├── progress.html
│   ├── forgot_password.html
│   └── report.html
│
├── static/
│   └── css/
│       └── style.css
│
└── instance/
    └── interview.db              # SQLite persistent storage
```

---

## 🛠 Tech Stack

### Backend
| Technology | Purpose |
|---|---|
| **Flask** | Web application framework & routing |
| **SQLAlchemy** | ORM for database interactions |
| **SQLite** | Lightweight relational data storage |
| **Werkzeug** | Password hashing & security utilities |
| **python-dotenv** | Environment variable management |

### Frontend
| Technology | Purpose |
|---|---|
| **HTML5 / CSS3** | Markup & responsive styling |
| **JavaScript (Vanilla)** | Proctoring logic & dynamic UI |
| **Chart.js** | Radar chart & performance visualization |
| **MediaPipe** | Real-time head pose detection (WASM) |

### AI & Evaluation
| Component | Capability |
|---|---|
| **Adaptive Engine** | Dynamic difficulty adjustment |
| **Evaluator** | Multi-criteria automated scoring |
| **Plagiarism Checker** | Response originality analysis |
| **Fairness Module** | Score normalization & calibration |
| **Report Generator** | Structured performance compilation |

---

## ⚙️ Installation & Setup

### Prerequisites
- Python **3.10+**
- pip package manager
- A modern browser (Chrome/Edge recommended for proctoring features)

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/ai-interview-platform.git
cd ai-interview-platform
```

### 2. Create a Virtual Environment *(recommended)*
```bash
python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate           # Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Environment
```bash
cp .env.example .env
# Edit .env with your secret key and any API credentials
```

### 5. Initialize the Database
```bash
python -c "from database.db import init_db; init_db()"
```

### 6. Run the Application
```bash
python app.py
```

### 7. Open in Browser
```
http://127.0.0.1:5000
```

---

## 🎬 Interview Workflow

```
Candidate Login / Register
        │
        ▼
  Select Role & Mode
  (Technical / Behavioral)
        │
        ▼
  Proctoring Activation
  (Fullscreen + Webcam)
        │
        ▼
  ┌──────────────────────┐
  │  AI Generates Q1     │  ← Adaptive Engine picks difficulty
  │  Timer: 60 seconds   │
  │  Webcam: Monitoring  │
  └──────┬───────────────┘
         │  Answer submitted / Timer expires
         ▼
  Evaluator scores response → Adjusts next difficulty
         │
         ▼  (Repeat × N questions)
         │
         ▼
  Report Generation
  (Score · Radar Chart · Feedback · Plagiarism Check)
        │
        ▼
  Session Stored in History
  (Score · Role · Date · Security Status)
```

---

## 🔒 Intelligent Proctoring System

The proctoring layer runs entirely in the browser and activates before the first question is displayed.

### Detection Events

| Violation Type | Detection Method | Response |
|---|---|---|
| Leaving fullscreen | `fullscreenchange` event | Warning issued |
| Tab switch | `visibilitychange` event | Warning issued |
| Window blur | `blur` event | Warning issued |
| ESC key press | `keydown` listener | Warning issued |
| Copy-paste attempt | `copy` / `paste` events | Blocked silently |
| DevTools open | Size/timing heuristics | Blocked |
| Head turned away | MediaPipe head pose | Warning issued |
| **3rd Violation** | Counter threshold | **Auto-submit + Flag** |

All violations are logged with timestamps and stored against the interview session record.

---

## 🧠 AI Evaluation Engine

Each candidate response is scored across **5 dimensions**:

```
┌─────────────────────────────────────────────────────┐
│  Evaluation Dimension         Weight                │
│  ─────────────────────────    ──────                │
│  Conceptual Correctness       High                  │
│  Technical Depth              High                  │
│  Response Clarity             Medium                │
│  Logical Structure            Medium                │
│  Relevance to Expected Answer High                  │
└─────────────────────────────────────────────────────┘
```

### Automated Feedback Tiers

| Score Range | Status | Feedback Type |
|---|---|---|
| **≥ 8 / 10** | 🟢 Interview Ready | Advanced improvement suggestions |
| **5 – 7 / 10** | 🟡 Developing | Concept clarification + explanation tips |
| **< 5 / 10** | 🔴 Needs Work | Fundamental revision + structured practice |

---

## 📊 Performance Reports

Post-interview reports are generated automatically and include:

- ✅ **Overall Score** — Aggregated weighted score
- ✅ **Radar Chart** — Visual skill distribution across dimensions
- ✅ **Question-Level Breakdown** — Candidate answer vs. reference answer
- ✅ **Per-Question Score** — Individual scoring with rubric justification
- ✅ **Improvement Suggestions** — Actionable, question-specific advice
- ✅ **Plagiarism Analysis** — Originality check on submitted answers
- ✅ **Confidence Indicator** — Response quality proxy
- ✅ **Security Status** — Clean / Violation flagged

---

## 🏆 Hackathon Recognition

<div align="center">

**🎖️ AXIOML 2026 — National Level Hackathon**

*Department of Computer Science & Engineering (AI & ML)*
*Prathyusha Engineering College*
*February 3–4, 2026*

</div>

This platform was designed, built, and demonstrated under time-constrained, competitive conditions at **AXIOML 2026**, a national-level hackathon focused on AI-driven innovation. The project was recognized for its integration of adaptive AI logic, real-time proctoring, and structured automated evaluation within a full-stack architecture.

> 📎 [View LinkedIn Certificate & Recognition Post](https://www.linkedin.com/posts/m-v-karthikeya-b26a2131b_hackathon-axioml2026-artificialintelligence-activity-7437492275678515200-QQbR?utm_source=share&utm_medium=member_desktop)

---

## 🔮 Roadmap

| Feature | Status |
|---|---|
| NLP-based semantic answer evaluation | 🔲 Planned |
| Resume-based adaptive question generation | 🔲 Planned |
| AI interviewer avatar (TTS + animation) | 🔲 Planned |
| Video interview recording & replay | 🔲 Planned |
| Cloud deployment (AWS / GCP) | 🔲 Planned |
| Multi-candidate analytics dashboard | 🔲 Planned |
| LLM-powered conversational interview | 🔲 Planned |
| Coding challenge sandbox (Judge0 integration) | 🔲 Planned |

---

## 🤝 Contributing

Contributions are welcome. To get started:

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "feat: add your feature description"

# 4. Push to your branch
git push origin feature/your-feature-name

# 5. Open a Pull Request
```

Please follow [Conventional Commits](https://www.conventionalcommits.org/) for commit messages.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for full details.

---

<div align="center">

**Built with precision. Tested under pressure. Recognized at the national level.**

*If this project helped you, please consider giving it a ⭐ on GitHub.*

[![GitHub Stars](https://img.shields.io/github/stars/yourusername/ai-interview-platform?style=social)](https://github.com/yourusername/ai-interview-platform)

</div>
