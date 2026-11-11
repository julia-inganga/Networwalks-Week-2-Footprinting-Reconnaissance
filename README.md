# NetworkWalks – Week 2: Footprinting & Network Scanning

## Project Overview

This repository documents my Week 2 practical activities as part of the Cybersecurity and Ethical Hacking program at NetworkWalks.

The project focuses on two main areas:

1. **Footprinting and Reconnaissance (W2-PM1):** Gathering information about a target domain using multiple Kali Linux tools.
2. **Network Scanning (W2-PM5):** Performing network discovery on my local network using Zenmap.

## Objectives

- Understand website footprinting and reconnaissance techniques.
- Identify publicly available domain information.
- Explore website technologies and DNS records.
- Inspect HTTP response headers.
- Identify live hosts on a local network.
- Understand the importance of documenting security observations.

## Tools Used

| Tool | Purpose |
|---|---|
| Kali Linux | Reconnaissance environment |
| WHOIS | Domain registration information |
| WhatWeb | Website technology identification |
| Nslookup | DNS resolution |
| Curl | HTTP response header inspection |
| Wafw00f | Web Application Firewall identification |
| DNSRecon | DNS enumeration |
| Zenmap | Network scanning and host discovery |
| Windows CMD | Local network configuration |

## Activities Performed

### 1. Website Footprinting and Reconnaissance

Performed authorized reconnaissance against `networkwalks.com` using WHOIS, WhatWeb, Nslookup, Curl, Wafw00f and DNSRecon.

The exercise involved gathering domain information, identifying website technologies, resolving DNS information, inspecting HTTP headers, identifying WAF technology and examining DNS records.

### 2. Network Scanning with Zenmap

Used Windows CMD to identify my local network configuration and Zenmap to perform a Ping Scan.

The latest scan identified **5 live hosts** on the local network.

I also explored host identification, MAC address information and network topology visualization.

## Key Learning Outcomes

- Understanding the footprinting and reconnaissance process.
- Using multiple tools for information gathering.
- Identifying website technologies and network infrastructure.
- Performing local network discovery.
- Analysing and documenting technical findings.
- Understanding the importance of authorized security testing.

## Risk Analysis

The report documents potential information exposure and network discovery observations.

These findings are not confirmed vulnerabilities. Further authorized testing would be required to validate any security weaknesses.

## Project Documentation

The complete practical report, including methodology, findings, risk analysis, recommendations and screenshots, will be available in this repository.

## Authorization and Disclaimer

All activities were conducted within the authorized educational scope described in the project report. The local network scanning activity was performed on my own network.

This project is intended for educational purposes and cybersecurity skills development. Unauthorized scanning or access to systems is not permitted.

## Project Report

[View the complete NetworkWalks Week 2 Report](./NetworkWalks-Week-2-Footprinting-Reconnaissance.pdf)
