# 🛡️ AegisCore AI: Automated Threat Triage & Patch Recommendation Engine

AegisCore AI is a high-performance defensive security co-pilot built to ingest enterprise server logs, detect malicious payload patterns (such as SQL Injection, XSS, and brute force attempts), and generate automated remediation patches using Nebius & NVIDIA-powered LLMs.

## 🚀 Key Features
- **Real-Time Log Ingestion:** Streamlines raw server and application logs for immediate inspection.
- **AI Threat Triage:** Leverages high-performance LLMs to analyze payload structures and assign threat severity levels.
- **Automated Patch Generation:** Recommends precise secure coding practices and remediation steps for discovered vulnerabilities.

## 🛠️ Tech Stack
- **Language:** Python 3.10+
- **Inference Architecture:** Nebius / NVIDIA AI Endpoint
- **Security Assessment Scope:** Log analysis, payload vectors, automated threat response

## 📦 How to Run
```bash
# Clone the repository
git clone https://github.com/izhaan60/AegisCore-AI.

# Navigate into the project folder
cd AegisCore-AI

# Execute the engine
python aegis_core.py
