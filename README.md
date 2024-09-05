# Port-Counter
The script will display information about the host, including its state and details about open ports and their states.

# Nmap Port Scanning Script

## Overview

This Python script uses the `nmap` library to scan a target IP address for open ports and services. The script performs a version detection scan (`-sV`) and a default script scan (`-sC`), then outputs the results, including the host's state and information about open ports.
Meet

## Prerequisites

- **Python**: Make sure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).
- **Nmap**: The script requires Nmap to be installed on your system. You can download it from [nmap.org](https://nmap.org/download.html).
- **nmap Library**: You need the Python `nmap` library. Install it using pip:

  ```bash
  pip install python-nmap
