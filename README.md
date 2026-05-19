# Secure IKEv2/IPsec VPN Deployment (StrongSwan on DigitalOcean)
This project demonstrates secure VPN configuration and cloud hardening using StrongSwan on a DigitalOcean droplet. It enables encrypted remote access across multiple platforms and aligns with governance and risk‑management best practices.

This project implements a secure IKEv2/IPsec VPN using StrongSwan on a DigitalOcean droplet.  
It enables encrypted remote access across multiple platforms (Windows, macOS, iOS, Android) and demonstrates secure configuration practices aligned with governance and risk‑management standards.

## Architecture
- **Cloud Provider:** DigitalOcean
- **OS:** Ubuntu 22.04 LTS
- **VPN Protocol:** IKEv2/IPsec
- **Authentication:** EAP‑MSCHAPv2
- **Firewall:** UFW

## Security Considerations
- No private keys or secrets are committed  
- Configuration files are sanitized examples  
- Strong cryptographic proposals enforced  
- NAT traversal enabled  

## What This Demonstrates
- Secure VPN design and implementation  
- Linux system hardening  
- Cloud networking and infrastructure security  
- StrongSwan configuration and cryptographic policy enforcement  
- Security documentation and governance alignment  

## Files
- `server/`: example server configurations  
- `client/`: client‑side configuration guidance  
- `docs/`: architecture diagram and notes  

## Disclaimer
This repository contains example configurations only.  
Do not use them directly in production without proper key generation and hardening.

## Professional Context
This project demonstrates practical cybersecurity engineering skills and secure configuration practices aligned with governance, risk, and compliance (GRC) principles.
