# WhatsApp Automation using n8n

## Overview
This project is a WhatsApp automation workflow built using n8n. It receives WhatsApp messages through a webhook, processes the message using JavaScript, and sends an automated reply using HTTP requests.

## Features
- WhatsApp message automation
- Webhook-based message handling
- JavaScript data processing
- HTTP Request integration
- Easy workflow import into n8n

## Technologies Used
- n8n
- Node.js
- JavaScript
- Webhooks
- HTTP Requests

## Project Structure
```
Whatsapp-automation/
│── Whatsapp_Automation.json(n8n code)
│── index.js
│── package.json
│── package-lock.json
│── .gitignore
```

## Installation

Clone the repository:

```bash
git clone https://github.com/DhruvSharma379/Whatsapp-automation.git
```

Install dependencies:

```bash
npm install
```

## Usage

1. Import `Whatsapp_Automation.json` into n8n.
2. Configure your webhook and WhatsApp credentials.
3. Install the required Node.js dependencies.
4. Run the Node.js application if needed.
5. Activate the workflow in n8n.

## Author

**Dhruv Sharma**

GitHub: https://github.com/DhruvSharma379
