# ⚓ Popeye-D-Sailor — Network & Router Systems Engineering

Welcome to the official GitHub profile for **Popeye-D-Sailor**, creator and maintainer of **WGOPilot™**.

Impact-Site-Verification: 437bf73f-11ae-4bf5-b92b-ae7a3d50a557

---

## ✈️ Flagship Project: **WGOPilot™ — Flight Control for WireGuard® & OpenVPN® on OpenWrt®**

**WGOPilot™** is a zero-bloat, enterprise-grade router VPN management suite, Web Cockpit, and 42-column SSH CLI designed for routers running the **OpenWrt®** operating system (`21.02` through `25.12+`) and supporting the **WireGuard®** and **OpenVPN®** protocols.

Built for home users, streaming and gaming enthusiasts, and network administrators, **WGOPilot™** turns compatible router hardware into a self-healing VPN gateway.

### 🌐 Commercial VPN Provider Compatibility & Partner Hub
**WGOPilot™** includes automated API and profile adapters—plus an optional in-app **Partner Deals & Recommended VPN Providers** directory—for leading commercial VPN services:

| Compatible Service | Native **WGOPilot™** Capabilities |
| :--- | :--- |
| **NordVPN®** | • Automated token provisioning and key registration for **NordLynx®** (built on the **WireGuard®** protocol)<br>• Real-time server load, city/country discovery & low-latency gate selection<br>• Profile support for the **OpenVPN®** protocol (`UDP` & `TCP :443` Stealth fallback) and specialty server groups |
| **Surfshark®** | • Automated key management and profile provisioning for the **WireGuard®** protocol, city/country relay catalog & MultiHop support<br>• Seamless Warm Standby & Autopilot failover integration |
| **Proton VPN®** | • Native profile management for the **WireGuard®** and **OpenVPN®** protocols, Secure Core, P2P & NAT-PMP Port Forwarding |
| **Private Internet Access® (PIA®)** | • Automated token authentication, key registration for the **WireGuard®** protocol & automated Port Forwarding daemon |
| **Mullvad®** | • Native relay catalog discovery, multihop/bridge support & custom `.conf` / `.ovpn` Hardware Vault management |

---

### 🛡️ Core Architecture & Capabilities

- **🖥️ Standalone Avionics Web Cockpit & LuCI Web UI Integration**:
  - Real-time bandwidth speedometer, handshake telemetry, and 1-click **Flight Mode Presets** (*Standard*, *Gaming*, *Streaming*, *Max Privacy*).
  - Guided **3-Step Onboarding Setup Wizard** and **In-App Partner Deals Hub** with direct signup links and QR codes for users purchasing a VPN subscription for their home router.
- **🤖 Autonomous Autopilot & Warm Standby Failover**:
  - Continuous health monitoring with automatic failover to pre-staged Warm Standby servers if an upstream relay goes offline or experiences high packet loss.
- **🔒 Fail-Closed Cabin Seal (`fw4` `nftables` & `fw3` `iptables` Kill Switch)**:
  - Strict kernel-level leak prevention with instant connection-tracking flush, IPv6 leak shield, and DNS-over-HTTPS (DoH) / private VPN DNS enforcement.
- **🔀 Smart Split-Tunneling (Policy-Based Routing Table 100)**:
  - Per-device routing (*VPN Tunnel*, *WAN Bypass*, *Strict VPN-Only*, *Scheduled Bedtime Pause*) and domain/application bypass presets for streaming, banking, and gaming.
- **🔐 Hardware-Bound Cryptographic Vault**:
  - Encrypts all private keys, provider API tokens, and credentials at rest using router-specific hardware entropy with portable disaster-recovery capsules.
- **🌍 19-Language Internationalization (i18n)**:
  - Full Web Cockpit, CLI Help Center, and documentation support across 19 languages.

---

### 📦 Project Status, Supported Platforms & Recommended Hardware
- **Current Stage**: Final Pre-Release QA & Hardware Certification (`v1.0` Release Candidate)
- **Supported Operating Systems**: **OpenWrt®** `21.02`, `22.03`, `23.05`, `24.10`, and `25.12` (`apk` & `opkg` compatible across ARM, MIPS, and x86_64 architectures, including **GL.iNet®** routers running stock OpenWrt®-based firmware or vanilla **OpenWrt®**)
- **Recommended Router Hardware**: High-performance ARM64/multi-core Wi-Fi 7 and Wi-Fi 6 routers supporting **OpenWrt®**, including **GL.iNet®** home and travel gateways (*Beryl 7*, *Slate 7*, *Flint 3*, *Flint 2 GL-MT6000*, *Beryl AX GL-MT3000*, *Slate AX GL-AXT1800*) and **Linksys®** WRT series routers
- **License**: **WGOPilot™ Non-Commercial & Commercial Dual License Agreement** *(Free for Personal & Non-Commercial Home Use; Commercial License Required for Commercial, MSP & Fleet Use)*

---

## ⚖️ Legal, Privacy, Warranty, Affiliate & Trademark Notices

**Copyright © 2026 Popeye-D-Sailor (`https://github.com/Popeye-D-Sailor`). All rights reserved.**

1. **Dual License (Personal Free / Commercial Licensed)**:
   - **Personal & Non-Commercial Use (`Free`):** Individuals, hobbyists, and non-profit home users are granted a free, worldwide, royalty-free, non-exclusive, revocable license to download, install, use, and modify **WGOPilot™** on personal routers owned or leased by the user strictly for non-commercial purposes, provided all `WGOPilot™` and `Popeye-D-Sailor` copyright and attribution notices remain intact.
   - **Commercial, MSP & Fleet Use (`Commercial License Required`):** Pre-installing, flashing, or bundling **WGOPilot™** on routers or hardware appliances sold or leased commercially, deploying it as part of a paid IT/MSP service, or operating it within a commercial business requires a separate written Commercial License Agreement from **Popeye-D-Sailor**.
2. **100% Local Zero-Telemetry Privacy Guarantee**:
   - **WGOPilot™** executes 100% locally on the user's router hardware. It contains **zero telemetry, analytics SDKs, tracking beacons, or crash reporters**, and never transmits private keys, credentials, API tokens, or browsing activity off the router to **Popeye-D-Sailor** or any third party. All secrets remain encrypted locally inside the router's AES-256 Hardware Vault (`/etc/wgopilot/vault/`).
3. **Independent Project & Non-Affiliation Disclaimer**:
   - **WGOPilot™** is an independent software project and is **not affiliated with, endorsed by, sponsored by, or officially connected with** Jason A. Donenfeld, OpenVPN Inc., Software in the Public Interest, Inc. (SPI) (including its LuCI web interface framework), Tailscale Inc., ZeroTier, Inc., GL Technologies, Linksys Holdings, Inc., or any commercial VPN or DNS service provider.
4. **FTC Affiliate Disclosure (16 CFR Part 255)**:
   - **WGOPilot™** includes an optional Partner Deals & Recommended Providers directory containing referral/affiliate links for select VPN services. If a user chooses to purchase a subscription through one of those links, the project maintainer may receive an affiliate commission at no additional cost to the user. Provider compatibility, performance benchmarks, and routing features operate identically regardless of how a subscription was obtained.
5. **No Warranty & Responsible Use Notice**:
   - This software is provided **"AS IS"**, without warranty of any kind, express or implied, including without limitation the warranties of merchantability, fitness for a particular purpose, and noninfringement. Users are solely responsible for ensuring that their use of VPN tunneling, routing policies, and DNS settings complies with all applicable local laws, cryptographic regulations, ISP terms of service, and third-party VPN provider subscriber agreements.
6. **Third-Party Trademark Attributions**:
   - **"WGOPilot™"** and the WGOPilot Winged Shield & Jet Crest are trademarks of **Popeye-D-Sailor**.
   - **"WireGuard®"** and the **"WireGuard"** logo are registered trademarks of **Jason A. Donenfeld**.
   - **"OpenVPN®"** is a registered trademark of **OpenVPN Inc.**
   - **"OpenWrt®"** is a registered trademark of **Software in the Public Interest, Inc. (SPI)** (including its **LuCI** web interface framework, which is distributed under the Apache License 2.0).
   - **"Tailscale®"** is a registered trademark of **Tailscale Inc.**
   - **"ZeroTier®"** is a registered trademark of **ZeroTier, Inc.**
   - **"GL.iNet®"** is a registered trademark of **GL Technologies**.
   - **"Linksys®"** is a registered trademark of **Linksys Holdings, Inc.**
   - Commercial VPN, DNS, monitoring, and notification service names (**NordVPN®**, **NordLynx®**, **ExpressVPN®**, **Surfshark®**, **Mullvad®**, **Proton VPN®**, **Private Internet Access®** / **PIA®**, **CyberGhost®**, **Windscribe®**, **IPVanish®**, **Cloudflare®**, **AdGuard®**, **NextDNS®**, **Quad9®**, **Control D™**, **Prometheus®**, **Home Assistant™**, **Discord®**, **Telegram®**, **ntfy.sh™**) are trademarks™ or registered® trademarks of their respective owners and are referenced solely under nominative fair use to indicate user-configured compatibility without implying partnership, affiliation, or endorsement.
