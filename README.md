# GEMMA4-AI-BASED-OFFLINE-CISO-FORENSIC-WORKSTATION
GEMMA4 AI BASED  OFFLINE-CISO FORENSIC WORKSTATION 

## 🛠️ Installation & Setup

To run the **Gemma-CISO Forensic Workstation** locally, follow these steps:

### 1. Environment Setup
Ensure you have Python 3.9+ installed. Then, install the required libraries :
```bash
pip install -r requirements.txt
```
### 2. AI Model Configuration
This workstation requires Ollama to be installed and running. Download it at ollama.com 
Once installed, pull the specialized Gemma model in cmd :
```
ollama pull gemma4:e2b
```
### 3. Launching the Workstation
Start the web interface using Streamlit in cmd:
```
 streamlit run app.py
```
## 🧪 Quick Start: Testing the Workstation

To see the AI in action immediately, follow these steps:

1. Copy the **Sample Data** provided below.
2. Select the **"Log Analyst"** domain in the sidebar.
3. Paste the data into the text area and click **"Ingest & Initialize Case"**.
4. Watch as Gemma 4 (E2B) identifies the SQL Injection and Brute Force patterns.

### Sample Data for Testing can be c0py pasted in the type b0x as weII.:
```text
[2026-05-18 22:10:01] INFO: User 'admin' login attempt from 192.168.1.50 - Success
[2026-05-18 22:12:45] WARNING: Failed login attempt for 'root' from 45.33.2.11
[2026-05-18 22:12:46] WARNING: Failed login attempt for 'root' from 45.33.2.11
[2026-05-18 22:12:47] WARNING: Failed login attempt for 'root' from 45.33.2.11
[2026-05-18 22:15:20] ALERT: Suspicious URL accessed: /index.php?id=1' UNION SELECT NULL, user, password FROM users--
[2026-05-18 22:18:05] INFO: File 'config.php' modified by process 'unknown_daemon'
```
