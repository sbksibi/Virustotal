# Malicious IP and Hash Checker

This Python script checks IP addresses and file hashes (MD5, SHA256) against the VirusTotal database to identify malicious activity. The results are saved to a file and also displayed in the terminal.

## Features
- Reads IPs and file hashes from an input file (`input.txt`).
- Verifies entries using the VirusTotal API.
- Outputs malicious results to a file named `virustotal_malicious_results.txt`.
- Displays results in the terminal for quick viewing.

## Requirements
- Python 3.x
- Internet connection
- VirusTotal API key

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MaliciousChecker.git
   cd MaliciousChecker
2. ```bash
    pip install requests

## RUN

1. input.txt:
    ```bash
    192.168.0.1
    8.8.8.8
    d41d8cd98f00b204e9800998ecf8427e
2. python3 MaliciousChecker.py

## Output Example