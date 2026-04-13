# Elastic SIEM Project

## Overview
This project demonstrates the design of a SIEM (Security Information and Event Management) system using Elastic Stack, Snort IDS and UFW firewall.

This repository is based on a previously implemented lab environment.

---

## Architecture

The system includes 3 virtual machines:

- SIEM Server (Elasticsearch, Kibana, NGINX)
- IDS Server (Snort + Talos rules)
- Log Server (UFW + Filebeat)

---

## Log Flow

UFW / SNORT → Filebeat → Elasticsearch → Kibana

---

## Features

- Intrusion Detection System (Snort)
- Firewall log monitoring (UFW)
- Log forwarding with Filebeat
- Data visualization with Kibana
- Reverse proxy with NGINX
- Custom log generation

---

## Documentation

Project reports are available in the docs folder.

---


## 🧠 Lessons Learned

- SIEM architecture design
- Log collection and forwarding
- Working with Snort IDS
- Log parsing with Grok patterns
- Dashboard creation in Kibana

---

## 📌 Future Improvements

- Rebuild the full environment
- Add alerting system
- Integrate real-time monitoring

- ## Author

Pelin Gülmez
