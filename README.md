# Penetration Testing Using Kali Linux
**MSIS567 – Data Communications**  
Project: Penetration testing tutorial & lab report

**Authors:** Himamshu Aluru, Stephen Bickel, Siri Gundlapally, Meghana Meka, Yash Shah  
**Institution:** Marist College – School of Computer Science and Mathematics

---

## Summary
This repository contains the project report, step-by-step commands, and notes for "Penetration Testing Using Kali Linux" (MSIS567). The work documents reconnaissance, scanning, exploitation and post-exploitation using tools such as Nmap, Wireshark, and Metasploit.

**Keywords:** Penetration Testing, Kali Linux, Nmap, Metasploit, Wireshark

---

## Files in this repo
- `Project Report Draft.docx` — original report (uploaded).  
- `README.md` — project overview (this file).  
- `lab-commands.md` — exact commands used during the lab (see below).  
- `images/` — screenshots (add if available).  
- `.gitignore` — typical ignores.

---

## Important legal & ethical note
All scans and exploits in these notes were performed in a lab/controlled environment with permission. **Do not** run these commands against systems you do not own or explicitly have permission to test.

---

## Procedure (high level)
1. **Information gathering** — identify target IPs, hostnames, and services.  
2. **Target identification** — use ping sweeps and port scanning.  
3. **Vulnerability analysis** — discover service versions, misconfigurations.  
4. **Exploitation** — use Metasploit and other exploits to confirm vulnerabilities.  
5. **Post-exploitation & cleanup** — maintain access only when permitted, document findings.

Detailed commands are in `lab-commands.md`.

---

## Results (summary)
- Discovered open services and versions via Nmap.  
- Successfully exploited sample services (FTP, VNC, Samba) on the target VM to demonstrate how vulnerabilities can be exploited in a lab.  
- Root access was confirmed (example `whoami` returned `root` during lab).

---

## References
See references cited in the uploaded `Project Report Draft.docx`.

---

## Contact
If you want to discuss this project: Himamshu Aluru(Linkedln) 
