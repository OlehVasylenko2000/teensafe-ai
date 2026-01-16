# TeenSafe AI — Safeguard Assistant for Youth

**TeenSafe AI** is an open-source AI assistant designed to protect displaced teenagers and youth within the EU. The project is developed under the initiative of **UKRAINE Safeguard Alliance MTÜ** (PIC: 879207044). The system combines low-code (n8n) workflows with the power of Large Language Models (LLMs) to provide real-time safety guidance.

---

## 🎯 Project Goals
- **Cyber-Shield:** Rapid assessment of communication risks (cyberbullying, grooming, scams).
- **Digital Lawyer:** Navigator for children's rights in the EU (In Development).
- **Emotional Buddy:** Initial emotional support and adaptation resources (In Development).

## 📂 Repository Structure
- `/n8n-workflows` — JSON files of the architecture for import into n8n.
- `/documentation` — System prompts, AI logic, and technical guides.
- `/assets` — Visual workflow diagrams and interface screenshots.
- `LICENSE` — MIT License.

## 🛠 Tech Stack
- **Engine:** n8n (AI Beta)
- **LLMs:** Google Gemini 1.5 Pro / OpenAI GPT-4o
- **Speech-to-Text:** OpenAI Whisper (for voice message processing)
- **Interface:** Telegram Bot API

## 🚀 Quick Start (for Developers)
1. **Clone the repository:**
   `git clone https://github.com/Ukraine-Safeguard-Alliance/teensafe-ai.git`
2. **Import to n8n:**
   - Install n8n (locally or via Docker).
   - Import the JSON file from `/n8n-workflows/cyber-shield-v1.json`.
3. **Configure Credentials:**
   - Set up `TELEGRAM_BOT_TOKEN`.
   - Set up `GOOGLE_API_KEY` (for Gemini).

## 👥 Core Team
- **Lead Architect:** Nazar Vasylenko (Epic No. Y-001)
- **Logic & UX Designer:** Nestor Vasylenko (Epic No. Y-002)
- **Strategic Coordinator:** Oleh Vasylenko

## 🤝 Contributing
We welcome contributions from the global developer community. Please review the `CONTRIBUTING.md` file before submitting a Pull Request.

## 🔒 Security & Privacy
TeenSafe AI is built with **Privacy-by-Design**. We do not store personally identifiable information (PII). All communication analysis is processed in real-time to ensure GDPR compliance and protect the user's safety.

---

**Developed by:** [UKRAINE Safeguard Alliance MTÜ](https://safeguard.alliance.ee) (Estonia)
