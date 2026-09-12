# PhoneInfoga

- **Repository:** [sundowndev/phoneinfoga](https://github.com/sundowndev/phoneinfoga)
- **Website:** [sundowndev.github.io/phoneinfoga](https://sundowndev.github.io/phoneinfoga/)
- **Category:** OSINT / Phone Number Reconnaissance
- **Language:** Go
- **Stars:** 13k+
- **Tags:** `information-gathering` `phone-number` `osint`

## Description

An advanced information gathering framework for phone numbers — validates numbers,
identifies carriers, line types, and countries. Uses free public resources and
external APIs to footprint phone numbers.

## Features

- Validate phone numbers (existence & formatting)
- Identify country, carrier, line type
- OSINT footprinting via external APIs
- Local & remote scanning
- Web interface included

## Usage

```bash
# Binary install
curl -sSL https://raw.githubusercontent.com/sundowndev/phoneinfoga/master/support/install.sh | bash
phoneinfoga scan --number "+1234567890"

# Or Docker
docker run --rm -it sundowndev/phoneinfoga:latest scan --number "+1234567890"
```
