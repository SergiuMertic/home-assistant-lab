# 🏗️ Home Assistant Lab Architecture

## 🌐 System Overview

This document describes the technical architecture of my self-hosted Home Assistant home lab.

---

## 📊 Architecture Diagram (Logical View)

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
