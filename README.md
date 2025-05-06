# ShodanRecon 🔍

ShodanRecon is a Python-based real-time reconnaissance tool that uses the Shodan API to scan public IP addresses for open ports, services, and metadata. Ideal for security analysts, ethical hackers, or IT professionals seeking visibility into externally exposed assets.

## 🚀 Features

- 🔍 Scan any public IP using Shodan's API
- 🛡️ Identify open ports, banners, and exposed services
- 📊 Export results to a clean CSV report
- ⚠️ Handles invalid IPs and API errors gracefully
- 🧩 Simple codebase, easy to extend

## 📦 Requirements

- Python 3.x
- `requests` library

```bash
pip install requests
```

🔑 Setup

1. Get a free Shodan API key: https://account.shodan.io/
2. Replace YOUR_API_KEY in the script with your key.

📌 Notes

1. Free Shodan API keys work only for specific endpoints.
2. This tool uses the /shodan/host/{ip} endpoint (free-accessible).

🛠️ Future Upgrades

🔧 GUI version (Tkinter/Flask)
🗂️ Batch upload from file
🔄 Live auto-scanning mode
📉 Dashboard visualization
