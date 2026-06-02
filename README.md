> Passionate about ethical hacking, penetration testing, and CTF challenges.
> Currently building my skills through hands-on lab environments and vulnerable machines.

---

## About Me

I'm a self-taught cybersecurity enthusiast focused on penetration testing and offensive security.
I learn by doing, setting up home labs, hacking vulnerable VMs, and documenting every step of the process.

---

## Skills & Tools

### Reconnaissance
- `nmap` port scanning and service enumeration
- `netdiscover` / `arp-scan` host discovery
- `enum4linux` SMB/Windows enumeration
- `gobuster` directory and file brute forcing

### Exploitation
- `Metasploit` exploit framework
- `Hydra` brute force attacks (SSH, FTP, HTTP)
- Manual exploitation command injection, file upload, LFI

### Privilege Escalation
- Kernel exploits (overlayfs, vmsplice)
- SUID binary abuse
- Sudo misconfiguration (GTFOBins)
- Linux Capabilities (`cap_dac_read_search`)

### Web Application
- Command Injection
- SQL Injection (basic)
- Directory enumeration
- Source code analysis
- Brainfuck / cipher decoding

### Networking
- TCP/IP fundamentals
- pcap analysis (Wireshark, strings)
- FTP, SSH, SMB, HTTP protocols
- Virtual network configuration (VMware NAT/Host-Only)

---

## 🏆 CTF Writeups

| Machine | Difficulty | Platform | Key Techniques | Status |
|---------|------------|----------|---------------|--------|
| [Metasploitable 2](writeups/Metasploitable2.md) | Easy | VulnHub | FTP anon, Command Injection, vsftpd backdoor, Samba exploit | ✅ Rooted |
| [Tr0ll 1](writeups/Tr0ll1.md) | Easy | VulnHub | FTP anon, pcap analysis, Gobuster, SSH, Kernel exploit (overlayfs) | ✅ Rooted |
| [HackathonCTF 2](writeups/HackathonCTF2.md) | Easy | VulnHub | FTP, Hidden HTML comments, Hydra SSH brute force, Sudo vim privesc | ✅ Rooted |
| [Empire: Breakout](writeups/EmpireBreakout.md) | Easy | VulnHub | enum4linux, Brainfuck decode, Usermin, tar capabilities privesc | ✅ Rooted |

---

## Home Lab Setup

| Component | Details |
|-----------|---------|
| **Hypervisor** | VMware Workstation |
| **Attacker Machine** | Kali Linux |
| **Network** | VMware NAT (isolated) |
| **Target VMs** | Metasploitable 2, Tr0ll 1, HackathonCTF 2, Empire: Breakout |
