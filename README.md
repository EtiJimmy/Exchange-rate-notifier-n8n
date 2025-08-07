# Exchange-rate-notifier-n8n
This is a simple exchange rate notifier built on n8n. It drops the current NGN-USD, CAD, AUD &amp; GBP rates every morning by 8am. 

## 📌 Features
- Scheduled daily trigger
- Fetches live exchange rates via FloatRates API
- Parses and formats exchange rate data
- Sends a clean, readable email to your inbox
- Built using n8n (open-source automation tool)

## ⚙️ Technologies
- n8n
- JavaScript (Code Node)
- HTTP Request Node
- Gmail Node
  
## 📬 Example Output
💱 Today's exchange rates (1 USD to NGN equivalent):

NGN: ₦1300.00
GBP: ₦1040.00
CAD: ₦980.23
AUD: ₦875.43
