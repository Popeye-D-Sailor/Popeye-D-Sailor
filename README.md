# ⚓ Popeye-D-Sailor — Open-Source Network & Router Engineering

Welcome to the official GitHub profile for **Popeye-D-Sailor**, creator and maintainer of **WGOPilot™**.

---

## ✈️ Flagship Project: **WGOPilot™ — Enterprise OpenWrt® Router VPN Flight Deck**

**WGOPilot™** is a zero-bloat, enterprise-grade WireGuard® and OpenVPN® router management suite, Web Cockpit, and 42-column SSH CLI designed specifically for **OpenWrt® routers** (`21.02` through `25.12+`).

Built for home users, streaming/gaming enthusiasts, and network administrators, WGOPilot™ turns any consumer or enterprise OpenWrt® router into a self-healing VPN appliance.

### 🌐 First-Class Commercial VPN Provider Integrations
WGOPilot™ includes native, automated API and profile adapters—plus an in-app **Partner Deals & Recommended VPN Providers** directory—for the industry's leading privacy providers:

| Supported Provider | Native WGOPilot™ Capabilities |
| :--- | :--- |
| **NordVPN®** | • Automated **NordLynx® (WireGuard®)** token provisioning & key registration<br>• Real-time server load, city/country discovery & low-latency gate selection<br>• **OpenVPN® UDP / TCP (`:443` Stealth)** fallback & Double VPN / Onion over VPN group routing |
| **Surfshark®** | • Automated WireGuard® key management, city/country relay catalog & MultiHop support<br>• Seamless Warm Standby & Autopilot failover integration |
| **Proton VPN®** | • Native WireGuard® & OpenVPN® profile management, Secure Core, P2P & NAT-PMP Port Forwarding |
| **Private Internet Access® (PIA)** | • Automated token authentication, WireGuard® key registration & automated Port Forwarding daemon |
| **Mullvad® VPN** | • Native relay catalog discovery, multihop/bridge support & custom `.conf` / `.ovpn` vault management |

---

### 🛡️ Core Architecture & Features

- **🖥️ Standalone Avionics Web Cockpit & LuCI Integration**:
  - Real-time bandwidth speedometer, handshake telemetry, and 1-click **Flight Mode Presets** (*Standard*, *Gaming*, *Streaming*, *Max Privacy*).
  - Guided **3-Step Onboarding Setup Wizard** and **In-App Partner Deals Hub** with direct signup links and QR codes for users purchasing a VPN subscription for their router.
- **🤖 Autonomous Autopilot & Warm Standby Failover**:
  - Continuous sub-second health monitoring with automatic failover to pre-staged Warm Standby servers if an upstream relay goes offline or experiences high packet loss.
- **🔒 Fail-Closed Cabin Seal (`fw4` `nftables` & `fw3` `iptables` Kill Switch)**:
  - Strict kernel-level leak prevention with instant connection-tracking flush, IPv6 leak shield, and DNS-over-HTTPS (DoH) / private VPN DNS enforcement.
- **🔀 Smart Split-Tunneling (Policy-Based Routing Table 100)**:
  - Per-device routing (*VPN Tunnel*, *WAN Bypass*, *Strict VPN-Only*, *Paused/Bedtime*) and domain/application bypass presets for streaming, banking, and gaming.
- **🔐 Hardware-Bound Cryptographic Vault**:
  - Encrypts all private keys, provider API tokens, and credentials at rest using router-specific hardware entropy with portable disaster-recovery capsules.
- **🌍 19-Language Internationalization (i18n)**:
  - Full Web Cockpit, CLI Help Center, and documentation support across 19 languages.

---

### 📦 Project & Release Status
- **Current Stage**: Final Pre-Release QA & Hardware Certification (`v1.0` Release Candidate)
- **Target Platforms**: OpenWrt® `21.02`, `22.03`, `23.05`, `24.10`, and `25.12` (`apk` & `opkg` compatible across ARM, MIPS, and x86_64 architectures)
- **License**: MIT Open-Source License
