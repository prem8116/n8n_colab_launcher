Run n8n on Google Colab (No Credit Card Required)

""Open in Colab" (https://colab.research.google.com/assets/colab-badge.svg)" (https://colab.research.google.com/github/prem8116/n8n_colab_launcher/blob/main/n8n_colab_launcher.ipynb)

"GitHub repo size" (https://img.shields.io/github/repo-size/prem8116/n8n_colab_launcher)
"GitHub stars" (https://img.shields.io/github/stars/prem8116/n8n_colab_launcher)
"License" (https://img.shields.io/badge/license-MIT-green)

Run n8n workflow automation on Google Colab without providing payment information or setting up a server.

Many cloud platforms require credit card verification even for free tiers.
This notebook removes that barrier so beginners can experiment with automation instantly.

---

Why This Project Exists

Many automation beginners struggle to try n8n because most cloud platforms require:

- credit card verification
- server deployment
- Docker knowledge
- infrastructure setup

Platforms like Render, Railway, Fly.io, Northflank, and Oracle Cloud free tier often require payment details or complicated setup.

This project provides a simple alternative.

With this notebook you can run n8n automation workflows on Google Colab without:

- credit card
- server setup
- Docker
- cloud deployment

---

My Story

I started learning n8n using only my mobile phone.

My laptop is very old (2GB RAM, dual-core CPU, Windows 8.1), so running development tools locally was extremely difficult. Because of that, I tried running Termux with a VNC server and Debian just to experiment with n8n.

While searching for ways to learn n8n for free, I explored several cloud platforms. Many of them offered free tiers but still required credit card verification or complicated deployment steps.

I wanted a simpler solution where beginners could experiment with automation without needing powerful hardware or payment details.

That’s when the idea came to me: what if n8n could run on Google Colab?

This notebook is the result of that experiment.

My goal is to make it easier for others to try n8n and learn automation without facing the same barriers.

---

Project Status

This project is actively maintained and tested on Google Colab.

Current features:

- Run n8n automation server on Google Colab
- No credit card required
- Persistent workflows using Google Drive
- Public access using Cloudflare tunnel
- Reuse existing n8n account between sessions

---

Features

- Run n8n workflow automation in Google Colab
- No hosting setup required
- No credit card required
- Persistent workflows using Google Drive
- Cloudflare tunnel for public access
- Simple one-click launch with Colab

---

Who This Is For

This project is useful for:

- beginners learning n8n
- automation enthusiasts
- students exploring workflow automation
- developers testing automation ideas

If you just want to try n8n quickly without setting up a server, this notebook is the fastest way.

---

Quick Start

1. Click the Open in Colab button above
2. Run all notebook cells
3. Wait for the public URL to appear
4. Open the URL in your browser
5. Access the n8n dashboard

---

Dashboard Preview

"n8n dashboard" (dashboard.png)

---

How It Works

This project runs the n8n automation server inside Google Colab.

The notebook:

1. Installs Node.js and n8n
2. Starts the n8n automation server
3. Stores workflows in Google Drive
4. Creates a public URL using Cloudflare tunnel

This allows anyone to experiment with workflow automation and no-code automation tools without deploying a server.

---

Limitations

- Google Colab sessions are temporary
- Public URL changes every run
- Long-running automations may stop when Colab runtime stops
- Not intended for production workloads

This setup is intended mainly for learning automation and testing workflows.

---

Repository Structure

n8n_colab_launcher
│
├── n8n_colab_launcher.ipynb
├── README.md
├── dashboard.png

---

Topics

automation • n8n • google-colab • workflow-automation • nocode • lowcode

---

Feedback

This project started as a personal experiment.

If you try the notebook, honest feedback is welcome:

- What works well?
- What could be improved?
- Any issues you encounter?

Both positive and negative feedback help improve the project.

---

Author

Created by prem8116

---

License

MIT License
