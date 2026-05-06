# 📬 Node.js SMTP Server

A lightweight SMTP server that receives, processes, and logs incoming email streams in real time. Built with Node.js, deployed on AWS EC2, and routed through Cloudflare.

---

## How It Works

The server listens for inbound SMTP traffic on **TCP port 25**. When an email arrives, it captures sender and recipient metadata, processes the raw data stream, and outputs everything directly to the console.

---

## Features

- Listens for inbound SMTP connections on port 25
- Logs sender (`MAIL FROM`) and recipient (`RCPT TO`) metadata
- Streams and outputs raw email data to the console
- Lightweight — no database, no frontend, just the protocol

---

## Tech Stack

| Layer          | Technology      |
|----------------|-----------------|
| Runtime        | Node.js         |
| SMTP Library   | `smtp-server`   |
| Hosting        | AWS EC2         |
| DNS/Networking | Cloudflare      |

---

## Live Server

This is a backend-only service with no web interface.  
To test it, send an email to any address at : anything@rjainil.me

---

## Local Setup

```bash
# 1. Clone the repo
git clone https://github.com/anirudhm2007/SMTP-server

# 2. Install dependencies
npm install smtp-server

# 3. Start the server (port 25 requires root)
sudo node index.js
```

---

## Team

- Anirudh Madhavan (2025IMT-006)
- Palksh Upadhyay (2025BCS-059)
- Rathwa Jainil (2025BCS-072)
