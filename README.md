# Awesome-Remote-Desktop-Screen-Sharing-Infrastructure

## Top Remote Desktop & Screen Sharing Infrastructure Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Remote Support, Self-Hosted RDP/VNC Gateways, Cross-Platform Screen Sharing & Secure Remote Access*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Remote Desktop & Screen Sharing Infrastructure**. These systems let users view and control distant desktops—for IT support, remote work, unattended access, and collaboration.

**Examples** include AnyDesk, TeamViewer, Splashtop, LogMeIn Pro, BeyondTrust Remote Support, RustDesk Pro, ConnectWise ScreenConnect, Parsec, RealVNC, Chrome Remote Desktop, and community projects such as Remocn.

**Open-source emphasis**: Self-hosted remote access is strong in open source. **RustDesk**, **Apache Guacamole**, **MeshCentral**, **FreeRDP**, **TigerVNC**, and **noVNC** cover client, server, and gateway roles. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[TeamViewer, AnyDesk, Splashtop, LogMeIn](https://www.teamviewer.com/)**  
  Consumer and business remote desktop products—easy NAT traversal, mobile clients, and commercial support plans.

- **[BeyondTrust Remote Support, ConnectWise ScreenConnect](https://www.beyondtrust.com/)**  
  Enterprise remote support and privileged access platforms—session audit, compliance, and helpdesk workflows.

- **[RustDesk Pro, RealVNC, Parsec](https://rustdesk.com/)**  
  Commercial offerings built on or alongside remote-desktop technology—managed relays, advanced security, or low-latency game/desktop streaming.

- **[Chrome Remote Desktop and browser-centric tools](https://remotedesktop.google.com/)**  
  Lightweight hosted remote access tied to Google accounts and the browser.

- **[Other commercial remote access platforms](https://www.splashtop.com/)**  
  Additional MSP-focused and unattended-access products.

## Open-Source GitHub Projects

### Full Remote Desktop Suites

- **[RustDesk](https://github.com/rustdesk/rustdesk)**  
  Leading open-source remote desktop—cross-platform clients, optional self-hosted ID/relay servers (hbbs/hbbr), end-to-end encryption, and a TeamViewer-like UX (AGPL for server components).

- **[MeshCentral](https://github.com/Ylianst/MeshCentral)**  
  Open self-hosted remote management platform—agents for Windows/Linux/macOS, remote desktop, terminal, files, and fleet-oriented admin (Apache-2.0).

- **[Apache Guacamole](https://github.com/apache/guacamole-server)**  
  Clientless open remote desktop gateway—RDP, VNC, and SSH in the browser with no agent install on the client side.

- **[Remotely](https://github.com/immense/Remotely)**  
  Open remote support and management tool—web-based console, agents, and screen sharing for helpdesk-style use.

### Protocols, Servers & Clients

- **[FreeRDP](https://github.com/FreeRDP/FreeRDP)**  
  Open implementation of the Remote Desktop Protocol—library and clients widely used on Linux and embedded systems.

- **[TigerVNC](https://github.com/TigerVNC/tigervnc)**  
  High-performance open VNC implementation—server and viewer for cross-platform screen sharing.

- **[xrdp](https://github.com/neutrinolabs/xrdp)**  
  Open RDP server for Linux—lets standard Remote Desktop clients connect to Linux desktops.

- **[noVNC](https://github.com/novnc/noVNC)**  
  Open VNC client that runs in the browser—HTML5 canvas-based remote display.

- **[Remmina](https://github.com/FreeRDP/Remmina)**  
  Open multi-protocol remote desktop client for Linux—RDP, VNC, SSH, and more in one GTK app.

- **[X2Go](https://github.com/gnubila-france/x2go)**  
  Open remote desktop suite based on NX—session resilience and efficient Linux remote desktops.

- **[Xpra](https://github.com/Xpra-org/xpra)**  
  Open “screen for X”—persistent remote application and desktop sessions with an HTML5 client.

### Additional & Specialized Tools

- **[ShellHub](https://github.com/shellhub-io/shellhub)**  
  Open gateway for SSH access behind NAT—device management with a central server.

- **[KasmVNC / Kasm Workspaces components](https://github.com/kasmtech/KasmVNC)**  
  Open web-native VNC stack used in containerized desktop delivery.

- **[Waypipe](https://gitlab.freedesktop.org/mstoeckl/waypipe)**  
  Open Wayland application forwarding over SSH—remote individual apps rather than full desktops.

- **[HopToDesk / community forks](https://github.com/search?q=remote+desktop+open+source)**  
  Community remote-desktop tools in the same problem space; verify license and maintenance per repo.

- **[Remocn and similar community projects](https://github.com/search?q=remocn)**  
  Emerging or niche open remote-access projects—evaluate activity and security posture before production use.

### Additional Strong Open-Source Options

- **TeamViewer-like self-hosted**: RustDesk + own hbbs/hbbr.
- **Browser-only access to existing RDP/VNC/SSH**: Apache Guacamole.
- **Fleet / MSP-style agent mesh**: MeshCentral.
- **Linux RDP server**: xrdp + FreeRDP clients.
- **Classic VNC**: TigerVNC + noVNC for web.
- **Composable stacks**: Guacamole in front of RDP/VNC hosts; or RustDesk server for peer-style support; MeshCentral for always-on agents.
- Commercial platforms still lead for global relay infrastructure, compliance certifications, and turnkey mobile support.

**Frameworks for building custom systems**:  
**RustDesk** for end-user remote support you host yourself; **Apache Guacamole** for HTML5 access to many protocols; **MeshCentral** for managed device fleets; **FreeRDP/TigerVNC/xrdp** for protocol-level building blocks.  
Fully open remote desktop infrastructure is production-ready for homes, labs, and many IT teams.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Remote desktop is high risk if misconfigured—require strong authentication, prefer self-hosted relays you control, keep software updated, and audit unattended access. Only connect to machines you are authorized to manage.
- Open-source tools offer transparency and data-path control. Commercial platforms shift relay infrastructure and support to the vendor. Neither replaces network segmentation and least-privilege access policies.

---

**Made for IT support, MSPs, and anyone who needs reliable remote access without giving up control of the pipeline.**  
Let's expand open remote desktop and screen-sharing infrastructure while recognizing the polish and global reach of leading commercial remote-support platforms.
