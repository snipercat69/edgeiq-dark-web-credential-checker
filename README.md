# 🔍 EdgeIQ Dark Web Credential Checker

**Check if emails or usernames have appeared in known data breaches and dark web exposures.**

Search public breach databases and paste sites to identify exposed credentials, classify the types of data leaked, and get actionable reports for breach response.

[![Project Stage](https://img.shields.io/badge/Stage-Beta-blue)](https://edgeiqlabs.com)
[![Python](https://img.shields.io/badge/Python-3.8+-green)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-orange)](LICENSE)

---

## What It Does

Checks whether an email address or username appears in known data breaches. Identifies which sites/services were compromised, what data was exposed (passwords, emails, PII, payment data), and when the breach occurred.

> ⚠️ **Legal Notice:** For personal use only. Do not use this tool to search others without consent.

---

## Key Features

- **Email breach search** — check if an email appears in known breaches
- **Username lookup** — search by username/handle across breach compilations
- **Breach source identification** — lists which sites were compromised
- **Exposed data classification** — categorizes what was leaked
- **Password hash detection** — identifies exposed password hashes
- **JSON export** — structured report for security audits

---

## Prerequisites

- Python 3.8+
- `requests` library

---

## Installation

```bash
git clone https://github.com/snipercat69/edgeiq-dark-web-credential-checker.git
cd edgeiq-dark-web-credential-checker
pip install -r requirements.txt
```

---

## Quick Start

```bash
# Check an email
python3 credential_checker.py --email "your_email@example.com"

# Check a username
python3 credential_checker.py --username "johndoe"

# Export JSON report
python3 credential_checker.py --email "your_email@example.com" --format json --output report.json
```

---

## Pricing

| Tier | Price | Features |
|------|-------|----------|
| **Free** | $0 | 3 email searches, basic report |
| **Lifetime** | $39 one-time | Unlimited searches, full reports, dark web monitoring |
| **Monthly** | $7/mo | All Lifetime features, billed monthly |

---

## Support

Open an issue at: https://github.com/snipercat69/edgeiq-dark-web-credential-checker/issues

---

*Part of EdgeIQ Labs — [edgeiqlabs.com](https://edgeiqlabs.com)*
