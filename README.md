🧠 AI-Powered Judicial Decision-Making System (AJDMS)

An advanced legal decision support system simulating an **AI Judge and AI Jury** that delivers fair, transparent, and consistent rulings by referencing past case law and legal principles.

📌 Overview

The AJDMS project is designed to address major issues in the Indian judicial system such as **judicial backlog**, **inconsistency in rulings**, and **access to justice**. It simulates a **legal deliberation** between multiple AI agents ("jury") and an **LLM-powered judge**, providing verdicts supported by precedent and Explainable AI (XAI) techniques.

🔍 Features

🤖 AI Judge – Powered by GPT-based LLM (e.g., LLaMA 2, GPT-4), it evaluates legal cases and issues verdicts.
👥 AI Jury (Multi-Agent) – AI agents trained on different legal ideologies engage in deliberation and voting.
📚 Legal Precedent Retrieval – Uses Indian Kanoon or alternative APIs to fetch relevant case law.
💬 Explainable AI (XAI)** – Verdicts come with transparent reasoning using SHAP/LIME methods.
🔐 Security & Privacy – AES-256 encryption and differential privacy ensure legal data confidentiality.
🌐 Interactive Web Interface (optional) – Submit, track, and visualize AI-generated case outcomes.

🛠️ Tech Stack

| Layer          | Technology Used                       |
|----------------|----------------------------------------|
| AI Models      | LLaMA 2 / GPT-4 / Falcon / LegalBERT   |
| Backend        | Python, FastAPI                        |
| Frontend       | React.js / Next.js (optional)          |
| AI Agents      | LangChain, OpenAI API                  |
| Data Retrieval | Indian Kanoon (scraping or 3rd-party)  |
| Database       | PostgreSQL / MongoDB                   |
| XAI Tools      | SHAP, LIME                             |
| Security       | AES-256, Opacus for differential privacy |
| Deployment     | Docker, Kubernetes                     |

🚀 How It Works

📝 User submits a case through the system.
📚 AI retrieves past legal precedents using FAISS + case law source (e.g., Indian Kanoon).
👩‍⚖️ AI Jury (multi-agent) independently analyzes and debates the case.
✅ A consensus is reached through AI-based voting.
⚖️ AI Judge finalizes the ruling, combining precedent and jury input.
🔍 The decision is explained using XAI methods and shown to the user.

🔐 Security

- AES-256 encryption for storing legal data securely.
- JWT-based role authentication (lawyer, judge, admin).
- Differential privacy using Meta’s **Opacus** to protect sensitive data.

🧪 Evaluation Metrics

| Category             | Metrics Used                        |
|----------------------|-------------------------------------|
| Legal Accuracy       | Precision, Recall, F1-Score         |
| Jury Deliberation    | Consensus Index, Voting Stability   |
| Explainability       | XAI Score, SHAP Attribution         |
| Bias Mitigation      | Fairness Index, Disparity Score     |
| System Performance   | Inference Time, Throughput          |
| User Satisfaction    | Feedback Score, Adoption Rate       |


💡 Future Enhancements

- Real-time legal feedback from practicing lawyers
- Multi-lingual support for regional Indian courts
- Integration with e-Courts for real-case simulations

simulations

🙌 Contributors
- Priyansh Lodhi
- Jaydeep Mehariya

