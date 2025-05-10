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
