# Exchange-rate-notifier-n8n
This is a simple exchange rate notifier built on n8n. It drops the current NGN-USD, CAD, AUD &amp; GBP rates every morning by 8am. 

**What It Does**

This workflow fetches daily exchange rates (USD, GBP, CAD, AUD) from a public API, compares today’s rate with yesterday’s, formats the data into a readable message, and emails it to multiple recipients — all automatically.

## 📌 Features
- Scheduled daily trigger
- Fetches live exchange rates via FloatRates API
- Parses and formats exchange rate data
- Sends a clean, readable email to your inbox
- Built using n8n (open-source automation tool)

## ⚙️ Technologies
- n8n 
- HTTP Request Node. Daily exchange rate data pulled from Floatrates (https://www.floatrates.com/daily/usd.json)
- JavaScript (Code Node). Code added using natural language and chatGPT tweaks.
- Gmail Node

- 🔧 How It Works
Schedule Trigger – Runs daily at your chosen time.
HTTP Node – Fetches live exchange rates from an API.
Code Node – Compares today’s and yesterday’s rates and formats the message.
Gmail Node – Sends a personalized email update.
  
## 📬 Example Output
💱 Today's exchange rates (1 USD to NGN equivalent):

NGN: ₦1300.00
GBP: ₦1040.00
CAD: ₦980.23
AUD: ₦875.43

Workflow 
Image
<img width="1402" height="789" alt="Screenshot 2025-08-07 at 21 34 58" src="https://github.com/user-attachments/assets/94f57448-6305-44e8-a5c6-af78c34aacd3" />

Skills I Learned
Building logic in Code nodes (JavaScript in n8n)
Connecting and authenticating APIs
Creating dynamic, automated email flows
Using n8n to build powerful, no-code workflows

💡 Why I Built This
I’m learning automation from scratch with no prior tech background. This is one of my first real-world projects to make life easier and showcase what no-code tools can do.
