# 🔄 Automated Content Syndication Workflow (n8n)

This repository contains an **n8n workflow** that automates the full content pipeline — from web scraping to AI-generated summarization and multi-platform distribution across social media and messaging apps.

---

## 📌 What It Does

- 🔍 **Scrapes** articles from a website (even dynamically rendered ones).
- 🧠 **Summarizes** the content using the **Google Gemini API**.
- 📢 **Distributes** the enriched content to:
  - Telegram
  - Instagram
  - Pinterest
  - **WhatsApp**
  - **Facebook Pages**

---

## 🛠️ Tools & Integrations

- **n8n** – Workflow automation platform
- **Google Gemini API** – AI summarization
- **Telegram Bot API**
- **Facebook Graph API**
- **WhatsApp Cloud API**
- **Instagram & Pinterest APIs** *(via official/third-party methods)*
- **HTTP Request Node** – for flexible REST API integration
- **HTML Extract / Cheerio Nodes** – for content scraping and parsing

---

## 📥 How to Use

1. **Clone or download** the `ContentAutomationWorkflow.json` file.
2. Import the workflow into your n8n instance:
   - Click **Import** from the top-right menu
   - Upload the JSON file
3. Configure credentials for:
   - **Google Gemini API**
   - **Telegram Bot**
   - **Facebook Developer App** (Page access token + permissions)
   - **WhatsApp Business API** (Cloud API setup)
   - **Instagram & Pinterest** (if needed)
4. Update:
   - Scraping source URL
   - Auth tokens and chat IDs
   - Summary parameters (if required)
5. Run manually or schedule it using n8n’s cron trigger.

---

## ⚙️ Customization Ideas

- Add filters (e.g., keyword-based) before summarization
- Store summaries in Google Sheets, Notion, or Airtable
- Add email or Slack alerts if publishing fails
- Translate summaries before publishing using DeepL or Google Translate APIs

---

## 👨‍💻 Author

**Ishaan Joshi**  
🔗 [LinkedIn](https://www.linkedin.com/in/ishaan-joshi-45117a31a)  
💻 [GitHub](https://github.com/Joshi-ishaan)

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).
