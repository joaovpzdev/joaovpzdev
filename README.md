<p align="center">
  <img src="images/climbing.svg" alt="Climbing" />
</p>

# João Victor Paixão Zolim | Cyber Security

**SOC · Pentest** · Ethical Hacker (Cisco) · Oracle Cloud Infrastructure Foundations Associate

I'm changing careers into Information Security. Before this, I was a military firefighter, a reconditioning mechanic, and a welder, and I bring the discipline, the calm under pressure, and the habit of solving problems hands-on from those fields. I learn by building: every project below started as a question I wanted to answer with a working lab.


## Featured Projects


### Blue Team: monitoring, detection, and response

| Project | What it does | Stack |
|---|---|---|
| [zabbix-security-monitoring](https://github.com/joaovpzdev/zabbix-security-monitoring) | Security observation lab on a Windows host. Detects failed logins (Event ID 4625), newly installed services (7045), and Windows Defender being disabled, with email alerts. Includes documented troubleshooting. | Zabbix 7.0, Docker, MySQL, PowerShell |
| [sec-dash-zabbix](https://github.com/joaovpzdev/sec-dash-zabbix) | Dashboard that consumes the Zabbix API and shows the last 24 hours of alerts with severity charts. | Python, Flask, Chart.js |
| [soar-triagem](https://github.com/joaovpzdev/soar-triagem) | Receives SIEM alerts via webhook, enriches the IP with AbuseIPDB, and escalates to Slack according to risk. | Python, Flask, Redis, SQLite, Docker Compose |
| [checklist-hardening](https://github.com/joaovpzdev/checklist-hardening) | Read-only audit of SSH, firewall, updates, and accounts without passwords, with a PASS/WARN/FAIL report. | Bash, Linux |
| [leak-monitor](https://github.com/joaovpzdev/leak-monitor) | Checks emails against data breach databases and alerts only on new leaks. | Node.js, cron, Slack/Discord |

### Red Team: reconnaissance, OSINT, and findings management

| Project | What it does | Stack |
|---|---|---|
| [pentest-findings-dash](https://github.com/joaovpzdev/pentest-findings-dash) | Pentest findings management: imports Nmap, Nuclei, and Burp Suite output, deduplicates re-imports, and tracks remediation. | Node.js, React, PostgreSQL, Prisma |
| [visual-recon](https://github.com/joaovpzdev/visual-recon) | Captures a screenshot, title, and technologies for each host and builds an HTML gallery for visual triage. | Node.js, Headless Chromium |
| [cyber-sec-journey](https://github.com/joaovpzdev/cyber-sec-journey) | Documentation of my studies: pentest methodology, Kali Linux tools, SQL Injection, and Bash. | Kali Linux, Bash |

---

## Stack


**Security and infrastructure**

![Kali](https://img.shields.io/badge/Kali-%23268BEE?style=for-the-badge&logo=kalilinux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-%23FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Zabbix](https://img.shields.io/badge/Zabbix-%23CC0000?style=for-the-badge&logo=zabbix&logoColor=white)
![Python](https://img.shields.io/badge/Python-%233670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/Bash-%234EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Development**

![JavaScript](https://img.shields.io/badge/JavaScript-%23323330?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Node.js](https://img.shields.io/badge/Node.js-%236DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232a?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-%233982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033?style=for-the-badge&logo=git&logoColor=white)

---

## Certifications

- **Ethical Hacker**, Cisco
- **Introduction to Cybersecurity**, Cisco
- **Oracle Cloud Infrastructure Foundations Associate**, Oracle

---

## Work in Progress

- Expand the monitoring lab with Linux agents and encrypted communication (TLS/PSK) between agent and server
- Integrate the triage SOAR with a commercial SIEM
- Document each lesson learned with screenshots and step-by-step reproduction instructions

---

## Ethical Use Notice

The reconnaissance and pentest tools in this profile are educational and must be used **only in environments you own or have written authorization to test**.

---

## Contact

[joaovpz.dev@gmail.com](mailto:joaovpz.dev@gmail.com) · [LinkedIn](https://www.linkedin.com/in/joao-victor-paixao-zolim)

<sub>Away from the computer: climber, runner, and powerlifter.</sub>

![Snake animation](https://github.com/joaovpzdev/joaovpzdev/raw/output/github-contribution-grid-snake.svg)

<footer> ©JoaoVPZDev </footer>
