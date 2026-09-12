# dnspython

- **Repository:** [rthalley/dnspython](https://github.com/rthalley/dnspython)
- **Category:** DNS Toolkit / Python Library
- **Language:** Python
- **Tags:** `python` `dns`

## Description

A powerful DNS toolkit for Python. Supports all major DNS record types (A, AAAA,
MX, TXT, NS, CNAME, SOA, SRV, etc.), zone transfers, DNSSEC, and DNS over TLS/HTTPS.
Widely used in security tooling for DNS enumeration and reconnaissance.

## Features

- Full DNS protocol support
- Zone file parsing
- DNSSEC validation
- DNS over TLS and HTTPS
- Asynchronous I/O support

## Usage

```python
import dns.resolver
answers = dns.resolver.resolve('example.com', 'A')
for rdata in answers:
    print(rdata)
```

```bash
pip install dnspython
```
