# DigitalOcean IKEv2 VPN (strongSwan)

## Overview
This project documents the deployment of a secure IKEv2 VPN using strongSwan
on a DigitalOcean Ubuntu 22.04 droplet. The goal is to demonstrate practical
network security, IPsec configuration, and cloud hardening.

## Architecture
- Cloud Provider: DigitalOcean
- OS: Ubuntu 22.04 LTS
- VPN Protocol: IKEv2/IPsec
- Authentication: EAP-MSCHAPv2
- Firewall: UFW

## Security Considerations
- No private keys or secrets are committed
- Configuration files are sanitized examples
- Strong cryptographic proposals enforced
- NAT traversal enabled

## What This Demonstrates
- Secure VPN design
- Linux system hardening
- Cloud networking
- StrongSwan configuration
- Security documentation practices

## Files
- server/: example server configurations
- client/: client-side configuration guidance
- docs/: architecture and notes

## Disclaimer
This repository contains example configurations only. Do not use them
directly in production without proper key generation and hardening.
