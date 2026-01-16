# DigitalOcean IKEv2 VPN (strongSwan) – Lab Build

This repo documents a lab build of an IKEv2 remote-access VPN using strongSwan on Ubuntu 22.04 (hosted on a DigitalOcean droplet).

## What’s included
- `server/` sanitized example configs (no secrets)
- `client/` example client configs (sanitized)
- `docs/` screenshots and report notes
- `scripts/` helper scripts (optional)

## Security note
This repo intentionally excludes:
- private keys
- `/etc/ipsec.secrets`
- real IP addresses/usernames/passwords
