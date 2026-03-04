# Offensive Cybersecurity

Red team exercises and threat emulation projects developed as part of the **CESAE Digital Network & Cybersecurity Administration** course (Offensive Simulation module).

All exercises were conducted in fully isolated lab environments. No real systems, networks, or individuals were involved.

---

## Projects

### [APT29 — Cozy Bear Full-Chain Threat Emulation](APT29_Cozy_Bear/README.md)
**February 2026**

Full kill-chain simulation of APT29 (Cozy Bear / NOBELIUM) against a fictional Portuguese government organisation (DGSI). Covers the complete Cyber Kill Chain from spearphishing to data exfiltration, with all techniques mapped to MITRE ATT&CK.

**TTPs:** T1566.002 · T1204.002 · T1071.001 · T1547.001 · T1087.002 · T1018 · T1135 · T1134 · T1003.001 · T1021.002 · T1005 · T1039 · T1041

**Tools:** Sliver C2 · Metasploit · Gophish · Mimikatz · msfvenom

**Result:** Full domain compromise in ~3h55m — NT AUTHORITY\SYSTEM on Domain Controller, 5 classified documents exfiltrated.

---

### [APT28 — Spearphishing Attachment (T1566.001)](T1566.001_Spearphishing_Attachment.md)
**January 2026**

Simulation of APT28 (Fancy Bear) spearphishing technique using a malicious Office document with VBA macro delivering a PowerShell reverse shell. Includes IOC analysis and defensive recommendations.

**TTPs:** T1566.001 · T1059.001 · T1204.002

**Tools:** VBA Macros · PowerShell · Metasploit

---

## License

[Creative Commons BY-NC-SA 4.0](LICENSE) — Educational use only.

---

*Jorge Moreira · [Portfolio](https://jorge-moreira-portfolio.vercel.app) · [LinkedIn](https://linkedin.com/in/jormoreira)*
