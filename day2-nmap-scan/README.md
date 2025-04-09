# 🔍 Day 2 – Nmap Port Scanning for Healthcare Cybersecurity

This project demonstrates how port scanning can reveal vulnerabilities that ransomware might exploit in healthcare systems.

## 🛠 Tools Used

- **Nmap** – Network scanning tool used by cybersecurity professionals
- **Kali Linux** – Linux distribution for penetration testing and ethical hacking

## 🎯 Objective

To understand how open ports can lead to potential ransomware attacks in healthcare networks.

## 📋 Scan Performed

```bash
nmap -v scanme.nmap.org
```

- Target: `scanme.nmap.org` (legal testing host)
- Output saved as: `scan_output.txt`
- Summary provided in `scan-summary.md`

## 💡 Key Learnings

- Open ports like 22 (SSH) or 80 (HTTP) are common.
- In real hospital environments, open SMB (445) or RDP (3389) ports are high risk.
- Regular scanning is essential for early detection and prevention.

---

*This is part of my cybersecurity portfolio documenting my hands-on learning.*  
*— Nikhil Reddy Chitkula*
