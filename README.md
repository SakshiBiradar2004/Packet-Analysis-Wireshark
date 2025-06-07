# Packet-Analysis-Wireshark
A hands-on cybersecurity networking project focused on capturing and analyzing live network traffic using Wireshark. Includes filtered analysis of DNS, TCP (Port 443), and TLS packets from web traffic.
# Packet Analysis with Wireshark

This repository contains my second hands-on project as part of my cybersecurity networking journey. The project focuses on capturing, filtering, and analyzing real-time network traffic using Wireshark — a powerful network protocol analyzer.

---

## Project Overview

In this project, I captured and examined packet-level traffic from various protocols (DNS, TCP, TLS) to understand how data travels across networks securely and efficiently. The traffic was filtered using Wireshark's display filters for detailed inspection.

---

## 📌 Tools Used

- Wireshark
- Web Browser (traffic from Google)
- Secure protocols like TLS and TCP (Port 443)

---

## Key Filters Used

- `dns` – Analyzing domain name resolution queries
- `tcp.port == 443` – Filtering secure HTTPS traffic
- `tls` – Inspecting encrypted Transport Layer Security handshakes

---

## Screenshots

> 📌 Sensitive data blurred for security. The screenshots highlight:
- DNS request-response for Google domains
- TLS Client Hello and Server Hello exchange
- TCP segments on port 443 with ACK, SYN packets

---

## Learning Outcome

- Understood how DNS queries work behind every domain typed in the browser.
- Explored how HTTPS traffic is encrypted using TLS.
- Practiced using Wireshark’s filters and packet inspection tools.
- Learned to identify common traffic patterns in secure browsing.

---

## Status

✔️ Completed  
📁 Report PDF and Screenshots uploaded (with private data masked)  
📄 Safe to share as part of a public portfolio

