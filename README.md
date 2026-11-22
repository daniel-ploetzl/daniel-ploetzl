# Daniel Plötzl

[42 Vienna](https://www.42vienna.com/) graduate (June 2026), now in the 42 Mastery programme specialising in Cybersecurity and (Embedded) Systems Programming. 42 Vienna is part of the [42 Network](https://www.42network.org/), the world's largest IT school network (50+ campuses, 30+ countries), ranked 3rd in the 2026 WURI innovation ranking ahead of MIT (5th) and Stanford (7th) on that list.

Hands-on experience with offensive security research and detection analysis: network attack implementation, authentication log analysis, process lifecycle manipulation, ephemeral execution and forensic visibility, endpoint simulation and detection analysis. Security write-ups at [ploetzl.eu/writeups](https://ploetzl.eu/writeups/).

## Core Areas

- **Network security**: ARP spoofing/poisoning, Man-in-the-Middle attack implementation and protocol vulnerability analysis (Layer 2)
- **Embedded security**: ECDSA host authorisation, AES-GCM protection for flash records and signed and encrypted RP2350 firmware with keys provisioned in one time programmable memory
- **Real-time operating systems**: Zephyr on RP2350, thread scheduling and priorities, race conditions, mutexes and priority inheritance
- **Ephemeral execution**: runtime isolation, persistence boundaries in volatile memory, forensic visibility implications
- **Process lifecycle manipulation**: process group control, setsid, signal handling, transient execution analysis
- **Session-level exploitation**: X11 window manager bypass, input grabbing, session takeover without elevated privileges
- **Endpoint simulation**: USB HID input emulation in embedded C, host-side detection of synthetic input
- **Authentication log analysis**: SSH attack pattern recognition, temporal clustering, failed/successful login correlation
- **Linux systems administration**: partitioning, user and permission management, service hardening, firewall configuration
- **Web application security**: WAF (ModSecurity, OWASP CRS), secrets management (HashiCorp Vault)


## Current Focus

- ft_malcolm: ARP spoofing/poisoning implementation and Layer 2 MitM attack analysis (42 Mastery)
- rp2350-hid-security-lab: testing the firmware verifier with valid signatures, a different host key and proofs replayed after reconnect
- zephyr-lab: learning RTOS fundamentals with Zephyr on Raspberry Pi Pico 2 W (RP2350)
- (Embedded) Systems Programming: low-level hardware interaction, USB and WiFi protocol behaviour on RP2350


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

- 💻 [rp2350-hid-security-lab](https://github.com/daniel-ploetzl/rp2350-hid-security-lab) - ECDSA host authorisation, AES-GCM protection for flash records and signed and encrypted RP2350 firmware with keys provisioned in OTP
- 🧵 [zephyr-lab](https://github.com/daniel-ploetzl/zephyr-lab) - Zephyr RTOS in C on Raspberry Pi Pico 2 W (RP2350): thread priorities, race conditions and mutexes
- ⌨️ [hid-lab](https://github.com/daniel-ploetzl/hid-lab) - USB HID input simulation firmware in C for Raspberry Pi Pico 2 and Pico 2 W (RP2350)
- 🔒 [ft_transcendence](https://github.com/daniel-ploetzl/ft_transcendence) - Full-stack team project; own modules: WAF (ModSecurity, OWASP CRS) and secrets management (HashiCorp Vault)
- 🖥️ [x11-lab](https://github.com/daniel-ploetzl/x11-lab) - X11 input grabbing, window manager bypass and session takeover
- ⚙️ [proc-lab](https://github.com/daniel-ploetzl/proc-lab) - Ephemeral process execution: process group detachment, signal handling and forensic visibility analysis
- 💾 [ram-workspace-lab](https://github.com/daniel-ploetzl/ram-workspace-lab) - Runtime isolation and persistence boundary analysis in volatile memory

