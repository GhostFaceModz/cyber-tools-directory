# EST - Email Spoofing Tool

## Description
Professional email security assessment framework. Multi-threaded SMTP server with 5 realistic attack scenarios (CEO fraud, IT helpdesk, PayPal, Microsoft 365, Bank Alert). Generates audit logs and assessment reports.

## GitHub
- **Repo:** https://github.com/TechSky-Code/EST
- **Stars:** 72
- **Language:** Python

## Features
- Professional SMTP Server (multi-threaded, RFC-compliant)
- 5 pre-built attack scenarios
- Custom test creation
- Assessment reporting
- Real-time email relay
- Python 3.13+ compatible

## Installation
```bash
git clone https://github.com/techsky-eh/EST.git
cd EST
chmod +x install.sh
./install.sh
```

## Basic Usage
```bash
# List available scenarios
est list

# Execute CEO fraud scenario
est test 1 target@company.com

# Generate assessment report
est report
```
