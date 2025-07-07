Digi रक्षक (Rakshak)

Real-Time AI-Based Email Threat Detection System

Digi रक्षक (Rakshak) is a privacy-focused desktop application that automatically scans incoming emails for phishing, spam, and malicious content—without requiring any manual input. Running silently in the background, it provides real-time protection and explains threats through a clean, intuitive dashboard..
🚀 Features & Unique Selling Propositions (USPs)

    ✅ Real-Time & Autonomous
    Continuously scans all incoming emails and generates immediate alerts—no manual action required.

    🔍 Explainable AI
    Clearly displays why an email was flagged using model-driven reasoning, building user trust.

    🔐 Offline & Secure
    The system runs entirely on the user’s machine after initial training; no data is sent to the cloud.

    ✉ Multi-Platform Integration
    Works with Gmail, Outlook, and Yahoo accounts seamlessly.

🧠 Tech Stack
Layer 	Technologies Used
Language 	Python, JavaScript
ML/NLP 	Scikit-learn, BERT, Transformers, Pandas, NLTK
Backend 	IMAP/SMTP, Email Parser, Python scripts
Frontend 	Electron.js, React.js
Security 	VirusTotal API.
UI/UX 	React.js
🗂 Project Structure

(digi-rakshak/ ├── backend/

│ ├── app/

│ │ ├── assets/

│ │ ├── routes/

│ │ ├── services/

│ │ ├── utils/

│ │ └── init.py

│ ├── env_name/

│ │ ├── Include/

│ │ ├── Lib/

│ │ ├── Scripts/

│ │ └── pyvenv.cfg

│ ├── app.py

│ ├── run.py

│ └── requirements.txt │ ├── ml_models/

│ ├── training/

│ ├── models/

│ └── notebooks/ │ ├── dashboard/ # React + Vite frontend

│ ├── backend/ # Optional bridge or API routing?

│ ├── node_modules/

│ ├── public/

│ ├── src/

│ │ ├── assets/

│ │ ├── components/

│ │ │ ├── Navbar.css

│ │ │ └── Navbar.jsx

│ │ ├── pages/

│ │ │ ├── About.jsx

│ │ │ ├── Home.jsx

│ │ │ ├── Services.jsx

│ │ │ └── Test.jsx

│ │ ├── App.jsx

│ │ ├── main.jsx

│ │ ├── App.css

│ │ └── index.css

│ ├── index.html

│ ├── vite.config.js

│ ├── package.json

│ ├── package-lock.json

│ └── README.md

│ ├── extension/ # Browser extension

│ ├── .dist/

│ ├── digi_rakshas.png

│ ├── manifest.json

│ ├── popup.html

│ ├── popup.js
│ └── popup.css │ └── docs/ # Documentation, if any ''') This combines your Python backend, ML modules, React frontend, and browser extension into a clear monorepo-style structure.
🚀 Installation & Setup

1️⃣ Clone the Repository

Screenshot 2025-05-10 234255

2️⃣ Backend Setup

Install dependencies for both Flask modules

Screenshot 2025-05-10 235145

3️⃣ ML Model Setup (Optional if models are not pre-trained)

Train the model (only if not using pre-trained):

Screenshot 2025-05-10 235318

Place trained models in:

Screenshot 2025-05-10 235428

4️⃣ Frontend Setup (Dashboard UI)

Install dependencies and run the dashboard:

Screenshot 2025-05-10 235544

Frontend runs by default on:

Screenshot 2025-05-10 235620

It provides real-time alerts and a visual summary from backend modules.

WhatsApp Image 2025-05-11 at 07 39 29

By default:

backend_module01 runs on http://172.16.40.174:5000
backend_module02 runs on http://127.0.0.1:5000




Here are planned enhancements to expand Digi रक्षक's functionality and security coverage:

🧠 Image-Based Phishing Detection Integrate OCR (Optical Character Recognition) to detect threats hidden in embedded images (e.g., QR code scams, screenshot phishing).

🔗 Cross-Platform Messaging Analysis Extend AI threat detection to messaging platforms like WhatsApp, Telegram, and Slack by scanning links and shared content.

🌐 Browser Extension Develop a browser plugin for Chrome/Edge that scans emails viewed in web clients and warns in real-time.

🧩 Plugin API for Enterprise Systems Enable organizations to integrate Digi रक्षक with their internal email servers and monitoring systems via a plugin-based architecture.
🔄 Auto-Model Updates Periodic offline model retraining using anonymized user-approved feedback to adapt to evolving phishing techniques.
