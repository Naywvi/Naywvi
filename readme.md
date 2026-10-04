<h1 align="center">Naywvi</h1>

<p align="center">
  Systems & network administrator, full stack developer, security practitioner.<br>
  I build tools, run infrastructure, and attack my own labs to learn how to defend them.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Based%20in-%C3%8Ele--de--France-1f2328?style=flat-square" alt="Location">
  <img src="https://img.shields.io/badge/Focus-Blue%20Team%20%2F%20SOC-0969da?style=flat-square" alt="Focus">
  <img src="https://img.shields.io/badge/Studying-M2%20Cybersecurity%20%26%20Systems%20Architecture-1f2328?style=flat-square" alt="Studies">
  <img src="https://img.shields.io/badge/Languages-FR%20%7C%20EN-1f2328?style=flat-square" alt="Languages">
</p>

---

## About

I work as an IT systems and network administrator, with a mix of employment and freelance missions across several client sites. Day to day that means Windows and Linux infrastructure, Active Directory, firewalls, remote access, deployment and user support.

Outside of missions I write code, run a Proxmox homelab, and do detection engineering and offensive labs. I am finishing a Master's level degree (Bac+5) in cybersecurity and systems architecture, and I am aiming for a SOC / Blue Team analyst position.

## Skills at a glance

| Domain | What I do |
| --- | --- |
| Systems and networks | Windows Server, Active Directory, GPO, Linux administration, virtualisation, firewalls, VPN and remote access, imaging and deployment |
| Defensive security | SIEM, case management and SOAR, detection rules mapped to MITRE ATT&CK, Sysmon, Sigma, Suricata, log analysis |
| Offensive security | Web and AD penetration testing, C2 frameworks, CTF, professional reporting with CVSS and OWASP |
| Development | Full stack web, desktop apps, mobile apps, APIs, backend services in Go and Node.js |
| Automation and DevOps | Docker, reverse proxies, CI with GitHub Actions, job queues, scripting in Bash and PowerShell |

## Tech stack

**Languages**

<p>
  <img src="https://skillicons.dev/icons?i=go,rust,ts,js,py,cs,c,cpp,php,swift,bash,powershell" alt="Languages">
</p>

**Web, mobile and desktop**

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,tailwind,sass,html,css,dotnet" alt="Web, mobile and desktop">
</p>

React Native with Expo, C# WPF (.NET 8), Windows Graphics Capture API with Direct3D 11, Express with http-proxy-middleware, BullMQ.

**Infrastructure**

<p>
  <img src="https://skillicons.dev/icons?i=linux,debian,ubuntu,kali,windows,proxmox,vmware,docker,nginx,cisco" alt="Infrastructure">
</p>

**Data**

<p>
  <img src="https://skillicons.dev/icons?i=mongodb,mysql,sqlite,redis" alt="Databases">
</p>

**Workflow**

<p>
  <img src="https://skillicons.dev/icons?i=github,githubactions,notion,obsidian,trello,discord" alt="Workflow">
</p>

## Security toolbox

| Area | Tools and topics |
| --- | --- |
| SIEM and SOC | Wazuh, TheHive, Shuffle, Suricata (EVE JSON), Sysmon, Sigma rules, MITRE ATT&CK |
| Network security | OPNsense, FortiGate, firewall design, syslog integration, segmentation |
| Offensive | Kali Linux, Mythic C2, shellcode techniques, GOAD (Active Directory lab), OSCP and OSEP style labs |
| Practice | CTF challenges, Hackazon web penetration testing, vulnerability reporting (CVSS scoring, OWASP classification, remediation advice) |
| Identity | Active Directory, Kerberos, DNS troubleshooting, secure channel issues |
| Studies | Network security, quantum computing, NLP and cybersecurity, law and cybercrime |

## Systems and administration

- **Windows**: Server, Active Directory, Group Policy (including agent rollout site by site), Sysprep and master images for capture and deployment.
- **Imaging and deployment**: FOG Project server, generalised Windows masters, PXE and TFTP workflows.
- **Linux**: Debian and Ubuntu servers, Nginx, PM2, Certbot and TLS, AppArmor, xrdp and XFCE on VMs.
- **Virtualisation**: Proxmox VE (QEMU images, networking, port forwarding), VMware.
- **Network**: Cisco (CCNA track), FortiGate for remote access across sites, OPNsense, VPN, wifi and PoE design for my home rack.
- **Hardware and support**: fleet troubleshooting on a Lenovo ThinkBook park, firmware and driver issues, PC builds.

## Projects

| Project | What it does | Tech |
| --- | --- | --- |
| Malware analysis sandbox | Multi-tenant platform with Sysmon event collection through Windows services, a custom Sigma engine, MITRE ATT&CK mapping and a 0 to 100 risk score | Go, MongoDB, JWT |
| Mini SOC homelab | Detection engineering lab: Wazuh as SIEM, TheHive for cases, Shuffle for automation, Suricata for the network layer, custom rules mapped to ATT&CK. Presented at a school defence | Proxmox, Debian, Windows |
| Infrastructure monitoring "Carnets" | Polls client sites and generates PDF reports for long term tracking of an IT estate, with a job queue that isolates failures per site | Node.js, BullMQ, Redis |
| Nayflix | Self-hosted streaming platform with a React Native and web client, an in-app admin panel to manage Docker services, and a full media stack behind a reverse proxy | React Native, Expo, Docker, Jellyfin |
| Rust companion overlay | Desktop overlay for the Rust+ WebSocket API (Protobuf, rate limiting, map data) | C# WPF, .NET 8 |
| VirtualCompositor | Screen capture and compositing using the Windows Graphics Capture API | C#, Direct3D 11 |
| Clan dashboard | Server and player dashboard built on the BattleMetrics and Steam APIs | Web, Node.js |
| Naval route planner | Route planning tool | Web |
| Work sites sorting tool | Internal web app that pulls work site data from a database, lets me triage from an Excel file and exports the result | Python, web |
| Satellite R&D | Software defined radio reception (Meteor-M LRPT, CCSDS, Iridium, QO-100) and a motorised telescope mount carrying a Yagi antenna for tracking | SDR, antennas |
| Personal web | Migration of a personal site from plain HTML to Next.js App Router with Tailwind CSS | Next.js, Tailwind |
| Production VPS | Debian server with Nginx, Node.js, PM2, MongoDB and Certbot for a live service | Linux |

<!-- Add a link to each repo once it is public, for example [Malware analysis sandbox](https://github.com/Naywvi/your-repo) -->

## Homelab

A Proxmox cluster for the SOC lab, a self-hosted media and services stack in Docker, and a home rack being rebuilt around an OPNsense firewall, a silent PoE switch and a UniFi WiFi 7 access point on a 2.3 Gbps symmetric fibre line.

## Certifications and education

- Cisco CCNA: Introduction to Networks
- Cisco CCNA: Switching, Routing, and Wireless Essentials
- Cisco CCNA: Enterprise Networking, Security, and Automation
- Master's level degree (Bac+5) in cybersecurity and systems architecture, ESGI Paris (in progress)

## Open source

Reported and diagnosed a re-run bug in the FOG Project installer (Kea DHCP config path and subnet detection), fixed upstream: [FOGProject/fogproject#1747](https://github.com/FOGProject/fogproject/issues/1747).

## GitHub activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Naywvi&layout=compact&hide_border=true&theme=transparent" alt="Top languages">
  <img height="170" src="https://streak-stats.demolab.com/?user=Naywvi&hide_border=true&theme=transparent" alt="Streak">
</p>

## Contact

<p>
  <a href="https://github.com/Naywvi"><img src="https://img.shields.io/badge/GitHub-Naywvi-181717?style=flat-square&logo=github" alt="GitHub"></a>
  <a href="mailto:nagib.lakhdari.pro@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-ea4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>
