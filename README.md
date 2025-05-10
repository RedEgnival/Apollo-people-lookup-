# 🔍 Apollo People Lookup Bot 🤖

A Telegram bot that retrieves professional details (name, title, company, email, LinkedIn) using the Apollo.io API, logs the searches into a Google Sheet, and supports both English and Hindi text input.

## ✨ Features

- Accepts voice or text input via Telegram
- Extracts names like "Sundar Pichai" or "Sam Altman"
- Searches Apollo.io's people database (paid API required)
- Logs searches in a connected Google Sheet
- Deployable via Google Colab or server

## 🧠 Tech Stack

- Python + Flask / Colab
- Apollo API
- Google Sheets API
- Telegram Bot API


## 🚀 Setup (Colab)

1. Clone this repo or open `main_colab.py` in Colab.
2. Upload your `credentials.json` (Google Sheets service account).
3. Create a Google Sheet named `Apollo search logs` with this header:
   Timestamp | Prompt | Name | Title | Company | Email | LinkedIn
4. Set your Telegram bot token and Apollo API key inside the script.
5. Run and interact with the bot on Telegram.

## 🛠 Example Commands

- `Find details of Sundar Pichai`
- `Email of Sam Altman`

## ⚠️ Notes

- Apollo's `/people/search` API requires a paid plan. On the free tier, it may return limited or no data.
- For full access, consider alternative APIs like Clearbit or LinkedIn scrapers (if allowed under ToS).

## 📄 License

MIT License
