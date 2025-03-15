# Threat CTI GUI (Beta)

A simple Graphical User Interface (GUI) for Cyber Threat Intelligence (CTI) that leverages public threat intelligence sources to analyze Indicators of Compromise (IOCs) such as IP addresses, domains, URLs, and hashes. (Still under Dev phase)

## Overview

The Threat CTI GUI is built using Python and Tkinter, integrating APIs from AbuseIPDB, VirusTotal, PhishStats, and AlienVault OTX to provide a user-friendly interface for security researchers and enthusiasts to query threat intelligence data. The tool supports searching for IOCs and displays aggregated results in real-time, with options to clear input/output and trigger searches via Enter key.

## Features
- Search for IPs, domains, URLs, and hashes.
- Retrieve threat intelligence from multiple public sources (AbuseIPDB, VirusTotal, PhishStats, AlienVault OTX).
- Responsive GUI with threading to prevent freezing during API calls.
- Clear button to reset input and output.
- Enter key binding to trigger searches.

## Prerequisites
- Python 3.6 or higher.
- Required libraries: `requests`, `ipaddress`.
- API keys for AbuseIPDB, VirusTotal, and AlienVault OTX (free tiers available).

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/ex3ploit3r/CTI.git
cd CTI
sudo chmod +x CTI.py
python CTI.py
```

## Contributing

Contributions are welcome! Please follow these steps:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes and commit them (git commit -m "Description of changes").
- Push to the branch (git push origin feature-branch).
- Open a Pull Request with a description of your changes.

## Acknowledgments

Thanks to the maintainers of AbuseIPDB, VirusTotal, PhishStats, and AlienVault OTX for providing free API access.
Built with Python and Tkinter for a simple, cross-platform GUI.



