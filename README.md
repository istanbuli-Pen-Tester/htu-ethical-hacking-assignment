# Ethical Hacking Assignment – HTU Ethical Hacking Course

**Summative ethical-hacking assessment for HTU’s Ethical Hacking Course: end-to-end pentest workflow with industry-standard tools.**

---

## Scope & Objectives
- **Reconnaissance:** Shodan, nslookup, WHOIS, Nmap  
- **Vulnerability Scanning:** Nessus  
- **Packet Sniffing:** Wireshark  
- **Password Cracking:** Hydra against HTTP login form  
- **Web Exploitation:** SQL injection & XSS with SQLMap & manual payloads  
- **Post-Exploitation:** Meterpreter sessions & msfvenom bind shell  
- **Reporting:** Detailed findings and countermeasure recommendations  

---

## Tools & Techniques
- **Recon:** `shodan`, `nslookup`, `whois`, `nmap`  
- **Scanning:** `nessus`  
- **Sniffing:** `wireshark`  
- **Cracking:** `hydra`  
- **Web Exploits:** `sqlmap`, custom HTTP payloads  
- **Exploitation:** `metasploit`, `msfvenom`  
- **Reporting:** Word document  

---

## Key Learnings
- Orchestrated a full pentest cycle in a live lab  
- Mastered Nmap & Nessus scanning methodologies  
- Analyzed clear-text credentials with Wireshark  
- Automated form brute-forcing with Hydra  
- Crafted custom payloads & Meterpreter shells  
- Structured a professional remediation report  

---

## Files
- `Ethical_Hacking_Assignment.docx` – lab report with methodology, findings & recommendations  
- `shodan-open-ports.png` – screenshot of discovered public ports  
- `nessus-vuln-summary.png` – Nessus scan results overview  
- `hydra-bruteforce.png` – Hydra HTTP brute-force output  
- `sqlmap-dump.png` – SQLMap database dump proof  
- `metasploit-shell.png` – successful Meterpreter session screenshot  
- `bind_shell_payload.sh` – msfvenom bind-shell payload script  

---

## Usage
1. Open **Ethical_Hacking_Assignment.docx** to read the full write-up.  
2. Review each screenshot for visual proof of each pentest phase.  
3. Run `bind_shell_payload.sh` to generate a bind-shell payload with msfvenom.
