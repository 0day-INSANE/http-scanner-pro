# HTTP Security Scanner Pro

A web-based penetration testing platform built with Flask. Designed for authorized security testing, CTF challenges, and educational use.

> **Disclaimer:** This tool is intended for legal and authorized security testing only. Use it only on systems you own or have explicit permission to test. Misuse may violate local laws.

---

## Features

### Scanning & Testing
- **HTTP Fuzzer** — Send customizable HTTP requests with payload injection, combo lists, and proxy support
- **Injection Scanner** — Automated detection of SQL injection and other injection vulnerabilities
- **Proxy Scanner** — Validate and classify proxy lists (HTTP/HTTPS/SOCKS), with anonymity and geolocation checks
- **DNS Scanner** — Subdomain enumeration and DNS record analysis
- **URL Discovery** — Crawl and enumerate URLs from a target website

### Page Analyzer
- Load and render any URL with full HTML/CSS DOM view
- Syntax-highlighted source inspection
- Header and metadata analysis

### Community
- **Chat system** — Multi-room chat with public and private messaging
- **Challenge board** — Post and discuss CTF findings by category
- **Shop** — Item listing with reviews (demo feature)

### Admin
- Privilege management system with super-admin role
- User access control panel

---

## Requirements

- Python 3.8+
- See [requirements.txt](requirements.txt) for all dependencies

---

## Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/http_scanner_pro.git
cd http_scanner_pro

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

---

## Configuration

Create a `.env` file or set the following environment variable before running:

```bash
export SECRET_KEY="your-random-secret-key"
```

On Windows:
```cmd
set SECRET_KEY=your-random-secret-key
```

---

## Usage

```bash
python app.py
```

Then open your browser at `http://localhost:5000`.

---

## Project Structure

```
http_scanner_pro/
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
├── templates/
│   ├── index.html          # Main interface
│   └── login.html          # Login page
├── extensions/             # Browser extensions for testing
└── RICERCA URL2.py         # Standalone URL discovery script
```

---

## Legal Notice

This software is provided for educational and authorized security research purposes only. The authors are not responsible for any misuse or damage caused by this tool. Always obtain proper written authorization before testing any system.
