<h1 align="center">Arpit Raj</h1>
<h3 align="center">Offensive Security Engineer — VAPT & Red Team</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=00FF00&center=true&vCenter=true&width=550&lines=whoami+%3D+red+teamer;kerberoasting+the+domain...;root+access+obtained;still+building." alt="typing-svg" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CRTA-Certified-red?style=flat-square" />
  <img src="https://img.shields.io/badge/AD--RTS-Certified-red?style=flat-square" />
  <img src="https://img.shields.io/badge/HackTheBox-40%2B%20machines-9FEF00?style=flat-square" />
  <img src="https://img.shields.io/badge/TryHackMe-Top%205%25-red?style=flat-square" />
</p>

---

### > whoami

Offensive Security learner, turning theory into working exploits.

CRTA + AD-RTS certified. 40+ HackTheBox machines rooted, top 5% on TryHackMe. I built HackerRecon and PrivChk to actually understand the attacks I was reading about, instead of just running someone else's script.

Currently hunting for a VAPT / Red Team role.

---

### > ls projects/

**[HackerRecon](https://github.com/Arpitraj93/HackerRecon)**
Modular web attack surface analyzer. BFS crawling, WAF/CMS fingerprinting with CVE matching, JS secret scanning, active SQLi/XSS/LFI testing, nmap-style CLI flags. Every real bug found while building it (dedup key collisions, silent JSON save failures, false-positive XSS from SQL error text) was fixed and became something I can explain line by line.

**[PrivChk](https://github.com/Arpitraj93/privchk)**
Linux privilege escalation checker that judges what it finds instead of dumping raw output — scores every finding by severity/confidence against a local GTFOBins + CVE database. Found and fixed a real detection bug after testing against a live vulnerable box (`sudo -l -n` silently failing without a cached credential timestamp).

---

### > cat notes/

Alongside tooling, I keep structured, first-person notes on what I actually ran and what happened — my own working record as I go deeper into each technique:

- **Active Directory Attack Paths** — Kerberoasting, AS-REP Roasting, DCSync, Golden/Silver Ticket, Delegation abuse (unconstrained/constrained/RBCD), ACL abuse, ADCS ESC1-ESC10 — each with exploit/detect/defense breakdowns
- **Windows Privilege Escalation** — token impersonation (JuicyPotato, PrintSpoofer, RoguePotato, GodPotato, SweetPotato), service/registry/scheduled-task abuse
- **Linux Privilege Escalation** — sudo/SUID/SGID/capabilities/cron/PATH hijacking/library hijacking, all cross-referenced against GTFOBins

---

### > cat skills.txt

**Offensive Security:** Active Directory attack paths · Windows & Linux Privilege Escalation · Web App Pentesting (OWASP Top 10 + business logic/SSRF/SSTI) · API Security (BOLA/IDOR, JWT attacks)

**Tools:** BloodHound · Impacket · Mimikatz · Burp Suite · Nmap · Metasploit · Hydra · John the Ripper

**Building with:** Python · PowerShell · Bash

---

### > github --stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Arpitraj93&show_icons=true&theme=github_dark&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Arpitraj93&layout=compact&theme=github_dark&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Arpitraj93&theme=github-dark-blue&hide_border=true" />
</p>

---

### > contact --info

📫 princerajlava@gmail.com · arpitprince9@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/arpit-raj-8127b1372/)

<p align="center"><i>"Enumeration is 90% of the job. This profile is the other 10%."</i></p>
