# 🧠 Daily Crypto Brief Automation

This project automates daily crypto updates using **Activepieces**, **OpenAI**, and **WhatsApp Cloud API**.

## 🚀 Overview
- Fetches latest BTC and ETH data from CoinGecko
- Generates a concise "Daily Crypto Brief" via OpenAI
- Sends an HTML email report

## 🧩 Tech Stack
- Activepieces (No-code automation)
- OpenAI GPT-4o-mini
- CoinGecko API
- Gmail API

## 🗂️ Project Structure

## ⚙️ Setup
1. Import `flow.json` into Activepieces.
2. Add your credentials:
   - OpenAI API Key
   - Gmail connection
3. Adjust code steps if required.

## 📨 Example Output
**Email:**
> Daily Crypto Brief - 2025-11-10  
> • Bitcoin (BTC) is priced at $105,451 …  
> • Ethereum (ETH) …  
> • **Outlook:** Positive short-term trends may continue.

## Customize the schedule:
> In your flow trigger, set it to run once daily (e.g., 9:00 AM)

# Run or test the flow:
>Click Test Flow in Activepieces to verify the entire automation.

# 🧩 OpenAI API Notes

- Model used: gpt-4o-mini-2024-07-18
- You must have an OpenAI project created in the OpenAI Platform
- Replace all {{OPENAI_API_KEY}} placeholders with your actual key via Activepieces secrets.

# 🧾 Credits

- Activepieces for workflow orchestration
- OpenAI for text generation
- CoinGecko for free crypto market data
- Google Gmail API for automated email sending

# 🚀 Future Enhancements

- Add daily Slack, whatsapp or Telegram notifications with increased time frame
- Include market cap and trend charts
- Extend support for more tokens (SOL, XRP, ADA)