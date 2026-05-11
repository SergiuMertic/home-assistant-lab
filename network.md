## 🔐 Network & Security Design

My home lab is designed with basic separation and secure access in mind.

```mermaid
flowchart TD
    A[Internet] --> B[Router / Firewall]

    B --> C[Main LAN Devices]
    B --> D[IoT Network]

    C --> E[Linux Home Server]
    E --> F[Home Assistant]

    D --> G[Smart Devices]
    D --> H[Sensors]

    E --> I[SSH Access]
    E --> J[Web UI Access]

    I --> K[Remote Management]
