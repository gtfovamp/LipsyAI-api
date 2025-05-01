# 🌑 LipsyAI-API — *Your Shadow Companion*

**⚡ FastAPI backend for AI whispers & cosmic chats**

<div align="center">
  <img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="300" alt="LipsyAI Logo">
  <br>
  <a href="https://github.com/gtfovamp/LipsyAI-api/stargazers">
    <img src="https://img.shields.io/github/stars/gtfovamp/LipsyAI-api?style=for-the-badge&color=black">
  </a>
  <a href="https://github.com/gtfovamp/LipsyAI-api/issues">
    <img src="https://img.shields.io/github/issues/gtfovamp/LipsyAI-api?style=for-the-badge&color=purple">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge">
  </a>
</div>

---

## 🚀 Features
- **🌘 Eclipse Mode**: Dark-themed API endpoints
- **🤖 ChatGPT-like AI**: Natural language processing
- **⚡ Async FastAPI**: High-performance backend
- **🔐 JWT Auth**: Secure authentication
- **📡 WebSocket Support**: Real-time communication
- **📊 Prometheus Metrics**: Performance monitoring
- **🚀 Ready-to-Deploy**: Docker support included

---

## 🛠 Installation

### Prerequisites
- Python 3.8+
- Pipenv/Poetry (optional)

### Quick Start
```bash
# Clone repository
git clone https://github.com/gtfovamp/LipsyAI-api.git
cd LipsyAI-api

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
# .venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Run development server
uvicorn app.main:app --reload
