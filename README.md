# Daniel Plötzl

42 Vienna graduate (June 2026), currently in the 42 Mastery programme specialising in Cybersecurity, Systems Programming and embedded systems.

42 Vienna is part of the [42 Network](https://www.42network.org/), the world's largest IT school network, with 50+ campuses across 30+ countries. The network ranked 3rd in the 2026 World University Rankings for Innovation (WURI), ahead of MIT (5th) and Stanford (7th) in that ranking.

My work spans offensive security research, systems programming and embedded security. I investigate trust boundaries, authentication mechanisms, process execution, firmware integrity and security monitoring through hands-on technical projects.

## Current Focus

- **ft_malcolm:** ARP spoofing and poisoning implementation, Layer 2 Man-in-the-Middle attack analysis and network protocol behaviour (C, 42 Mastery).
- **rp2350-hid-security-lab:** ECDSA host authorisation, AES-GCM protection for flash records and signed and encrypted RP2350 firmware with keys provisioned in one-time programmable (OTP) memory. Current testing includes signature verification, host-key binding and replay resistance across reconnects.
- **zephyr-lab:** Learning RTOS fundamentals with Zephyr on Raspberry Pi Pico 2 W (RP2350), including thread scheduling, concurrency and synchronisation.
- **Systems & Embedded Programming:** Low-level hardware interaction, USB and WiFi protocol behaviour on RP2350.

## Technical Areas

- **Network Security:** ARP spoofing and poisoning, Layer 2 Man-in-the-Middle attack implementation and protocol vulnerability analysis.
- **Identity & Authentication Security:** ECDSA-based host authorisation, authentication mechanisms, SSH authentication log analysis and access-control boundaries.
- **Embedded & Firmware Security:** Cryptographic firmware verification, AES-GCM authenticated encryption, key provisioning and secure flash storage on RP2350.
- **Real-Time Systems:** Zephyr RTOS, thread scheduling and priorities, race conditions, mutexes and priority inheritance.
- **Linux Internals & Process Security:** Process group control, session management, signal handling, ephemeral execution and forensic visibility.
- **Session-Level Security Research:** X11 input grabbing, window manager bypass and session takeover without elevated privileges.
- **Endpoint Simulation & Detection:** USB HID input emulation in embedded C and host-side detection of synthetic input.
- **Application Security:** Web Application Firewall implementation with ModSecurity and OWASP Core Rule Set, secrets management with HashiCorp Vault.
- **Security Monitoring & Detection Analysis:** SSH attack pattern recognition, temporal clustering and failed/successful authentication correlation.
- **Linux Systems Administration:** Partitioning, user and permission management, service hardening and firewall configuration.

## Earlier Security Research

- **x11-lab:** X11 session takeover without elevated privileges, input grabbing and window manager bypass.
- **proc-lab:** Ephemeral process execution, process group detachment, signal handling and forensic visibility analysis.
- **ram-workspace-lab:** Runtime isolation and persistence boundary analysis in volatile memory.
- **soc-auth-triage:** SSH authentication log analysis, attack pattern recognition and event correlation.

Technical findings and security-relevant takeaways: [ploetzl.eu/writeups](https://ploetzl.eu/writeups/).

## Developing Professional Focus

My developing professional focus is at the intersection of:

- **Identity and Access Management (IAM):** Identity lifecycle, authentication, authorisation and privileged access.
- **Non-Human Identity Security:** Service accounts, workload identities, application credentials and machine-to-machine authentication.
- **AI Agent Security:** Agent identities, delegated permissions, tool access, trust boundaries and the security implications of autonomous workflows.
- **Offensive Security Validation:** Analysing attack paths and testing whether identity, access-control and security boundaries withstand realistic attacks.
- **Applied & Post-Quantum Cryptography:** Secure key management, cryptographic agility and the implications of post-quantum migration for PKI, device identity and firmware trust.

A central question driving this direction is how autonomous systems obtain, use and delegate permissions, how these relationships can be abused and how their security can be assessed and governed.

## 🛠️ Tech Stack

### Operating Systems

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
![Zephyr](https://img.shields.io/badge/Zephyr-7929D2?style=flat&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjggOCAyNTEgMTQ2Ij48ZyBmaWxsPSIjZmZmIj48cG9seWdvbiBwb2ludHM9IjEzNy4xNTQsMTIxLjYwMSAxMDUuMzEsMTM1LjA0NiAxMzIuMzg1LDE0OC43MiIvPjxwb2x5Z29uIHBvaW50cz0iNjguNDAxLDEzOS40MTkgMzQuNDM0LDEyNi43MDMgNDIuMzA5LDE1My40MDgiLz48cG9seWdvbiBwb2ludHM9Ijg0LjUwOCwxMTUuNTE4IDEwNS4zMSwxMzUuMDQ2IDY4LjQwMSwxMzkuNDE5IiBmaWxsLW9wYWNpdHk9Ii44Ii8%2BPHBvbHlnb24gcG9pbnRzPSIzOC41MzUsOTcuMTY3IDM0LjQzNCwxMjYuNzAzIDguNzU5LDEwMS4wNzYiIGZpbGwtb3BhY2l0eT0iLjgiLz48cG9seWdvbiBwb2ludHM9IjEzNy4xNTQsMTIxLjYwMSAyMjAuOTgyLDQ0LjQ4MiAyNTguNjY2LDk0LjQxNiIvPjxwb2x5Z29uIHBvaW50cz0iMTM3LjE1NCwxMjEuNjAxIDE3Mi45NTksOC4xMyAyMjAuOTgyLDQ0LjQ4MiIgZmlsbC1vcGFjaXR5PSIuODUiLz48cG9seWdvbiBwb2ludHM9IjE3Mi45NTksOC4xMyAyNTguNjY2LDguMTMgMjIwLjk4Miw0NC40ODIiIGZpbGwtb3BhY2l0eT0iLjciLz48cG9seWdvbiBwb2ludHM9IjI1OC42NjYsOTQuNDE2IDI1OC42NjYsOC4xMyAyMjAuOTgyLDQ0LjQ4MiIgZmlsbC1vcGFjaXR5PSIuODUiLz48L2c%2BPC9zdmc%2BCg%3D%3D)

### Security & Analysis

![Wireshark](https://img.shields.io/badge/Wireshark-6C757D?style=flat&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-2496ED?style=flat)

### Coding

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

### Tools & Environment

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat&logo=neovim&logoColor=white)
![Tmux](https://img.shields.io/badge/Tmux-1BB91F?style=flat&logo=tmux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=flat&logo=virtualbox&logoColor=white)
![QEMU/KVM](https://img.shields.io/badge/QEMU%2FKVM-FF6600?style=flat&logo=qemu&logoColor=white)

## 📁 Selected Projects

- 💻 [rp2350-hid-security-lab](https://github.com/daniel-ploetzl/rp2350-hid-security-lab) - ECDSA host authorisation, AES-GCM protection for flash records and signed and encrypted RP2350 firmware with keys provisioned in OTP memory.
- 🧵 [zephyr-lab](https://github.com/daniel-ploetzl/zephyr-lab) - Zephyr RTOS in C on Raspberry Pi Pico 2 W (RP2350), thread priorities, race conditions and mutexes.
- ⌨️ [hid-lab](https://github.com/daniel-ploetzl/hid-lab) - USB HID input simulation firmware in C for Raspberry Pi Pico 2 and Pico 2 W (RP2350).
- 🔒 [ft_transcendence](https://github.com/daniel-ploetzl/ft_transcendence) - Full-stack team project. Led technical architecture and implemented the security layer, including ModSecurity, OWASP CRS and HashiCorp Vault.
- 🖥️ [x11-lab](https://github.com/daniel-ploetzl/x11-lab) - X11 input grabbing, window manager bypass and session takeover.
- ⚙️ [proc-lab](https://github.com/daniel-ploetzl/proc-lab) - Ephemeral process execution, process group detachment, signal handling and forensic visibility analysis.
- 💾 [ram-workspace-lab](https://github.com/daniel-ploetzl/ram-workspace-lab) - Runtime isolation and persistence boundary analysis in volatile memory.
