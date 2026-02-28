# AI-Powered YouTube Transcript Summariser (n8n)

End-to-end AI automation pipeline integrating Apify transcript extraction with Google Gemini LLM for scalable YouTube content summarization using n8n.

---

## 🏗 Workflow Architecture

<p align="center">
  <img src="https://github.com/user-attachments/assets/c6057c36-bb7d-4ec0-b0fd-9e561389826a" width="900"/>
</p>

---

## ⚙️ How It Works

1. **Form Trigger** – Accepts a YouTube video URL.
2. **Apify API (HTTP Request)** – Extracts structured transcript data.
3. **Google Gemini (LLM)** – Generates an AI-powered summary.

---

## 🛠 Tech Stack

- n8n (Workflow Automation)
- Apify API (Transcript Extraction)
- Google Gemini LLM (Summarisation)
- Secure HTTP Header Authentication
