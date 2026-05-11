# 🏠 Home Assistant Lab

## 🚀 Overview
This repository documents my self-hosted Home Assistant setup used for smart home automation, infrastructure learning, and system administration practice.

It is part of my IT and cybersecurity learning journey, focusing on real-world Linux administration, networking, and automation.

---

## 🧠 Goals
- Build and maintain a self-hosted smart home system
- Improve Linux system administration skills
- Learn networking and troubleshooting
- Practice automation and scripting
- Gain real-world IT infrastructure experience

---

## ⚙️ Technologies
- Home Assistant
- Linux (Debian)
- SSH
- YAML automation
- Networking (LAN / WiFi)
- IoT devices
- Virtual Machines

---

## 🏗️ Home Lab Architecture (Advanced View)

```mermaid
flowchart TD
    A[Internet Router] --> B[Linux Home Server]
    B --> C[Home Assistant Core]

    C --> D[Smart Lights]
    C --> E[Sensors]
    C --> F[Automations]

    B --> G[SSH Remote Access]
    C --> H[Web Dashboard]

    E --> I[Motion Detection]
    E --> J[Temperature Monitoring]

    F --> K[Time-based Rules]
    F --> L[Presence-based Automation]
- Network segmentation (IoT vs main devices)
- Linux server administration
- Secure remote access
- Service hosting and automation
- Real-world troubleshooting scenarios
