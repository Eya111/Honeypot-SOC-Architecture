# 🐝 Honeypot SOC Architecture

Projet d'ingénieur : Mise en place d'une architecture SOC avec pfSense, Suricata (IPS), Cowrie (Honeypot) et Wazuh (SIEM).

## Architecture
- **Kali** : Attaquant
- **pfSense + Suricata** : Firewall & Network IPS
- **Ubuntu (DMZ)** : Cowrie Honeypot
- **Ubuntu (SIEM)** : Wazuh Manager
