# 🤖 Autonomous RAG Agent (Document Intelligence)

## 📌 Overview
I architected this system to automate the auditing of unstructured legal documents. Using **Retrieval-Augmented Generation (RAG)**, the agent "reasons" through complex contracts to provide 100% accurate data retrieval.

## ⚙️ Technical Logic
* **Dynamic Ingestion**: Triggered by chat, the system downloads a target PDF from **Google Drive**.
* **Vector Intelligence**: Text is split using a **Recursive Character Text Splitter** and converted into vectors via **OpenAI Embeddings**.
* **Cognitive Retrieval**: The agent autonomously calls the **Vector Store** as a tool to answer specific user questions about contract clauses.

## 🚀 Performance Proof
Successfully audited a **Basic Service Agreement**, identifying a 12-month contract duration without manual intervention.
