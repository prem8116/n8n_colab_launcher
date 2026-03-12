# Run n8n on Google Colab (No Credit Card Required)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prem8116/n8n_colab_launcher/blob/main/n8n_colab_launcher.ipynb)

This project allows anyone to run **n8n automation workflows** using Google Colab without providing payment information or setting up a server.

Many cloud platforms require credit card verification even for free tiers.
This notebook removes that barrier so beginners can experiment with automation instantly.

---

## Features

* No credit card required
* No server setup
* Persistent workflows using Google Drive
* Public access via Cloudflare tunnel
* Reuses existing n8n account if data already exists

---

## Quick Start

1. Click **Open in Colab** button above
2. Run all notebook cells
3. Wait for the public URL to appear
4. Open the URL in your browser
5. Access the n8n dashboard

---

## Dashboard Preview

![n8n dashboard](dashboard.png)

---

## How It Works

This notebook runs the **n8n automation server** inside Google Colab and exposes it to the internet using a Cloudflare tunnel.

Workflows and login data are stored in Google Drive, so your account and workflows persist between sessions.

---

## Limitations

* Google Colab sessions are temporary
* Public URL changes every run
* Not intended for production workloads

This setup is intended for **learning and testing automation workflows**.

---

## Repository Structure

```
n8n-colab-runner
│
├── n8n_colab_launcher.ipynb
├── README.md
├── dashboard.png
```

---

## Author

Created by **prem8116**

---

## License

MIT
