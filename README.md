<p align="center">
  <img src="images/climbing.svg" alt="Climbing" />
</p>

# João Victor Paixão Zolim | Cyber Security

**SOC · Pentest** · Ethical Hacker (Cisco) · Oracle Cloud Infrastructure Foundations Associate

Estou em transição de carreira para Segurança da Informação. Antes disso fui bombeiro militar, mecânico de retífica e soldador, e trago dessas áreas a disciplina, a calma sob pressão e o hábito de resolver problema na prática. Aprendo construindo: cada projeto abaixo nasceu de uma pergunta que eu quis responder com um laboratório funcionando.

> **EN:** Career changer into Information Security, focused on Blue Team (SOC and monitoring) and pentesting. Former military firefighter, self-taught, English C1 (reading/listening) and B2 (speaking). I build hands-on labs and document what I learn.


## Projetos em destaque

### Blue Team: monitoramento, detecção e resposta

| Projeto | O que faz | Stack |
|---|---|---|
| [zabbix-security-monitoring](https://github.com/joaovpzdev/zabbix-security-monitoring) | Laboratório de observação de segurança em um host Windows. Detecta login falho (Event ID 4625), novo serviço instalado (7045) e Windows Defender desativado, com alerta por e-mail. Inclui o troubleshooting documentado. | Zabbix 7.0, Docker, MySQL, PowerShell |
| [sec-dash-zabbix](https://github.com/joaovpzdev/sec-dash-zabbix) | Dashboard que consome a API do Zabbix e mostra os alertas das últimas 24 horas com gráficos de severidade. | Python, Flask, Chart.js |
| [soar-triagem](https://github.com/joaovpzdev/soar-triagem) | Recebe alertas de um SIEM por webhook, enriquece o IP com AbuseIPDB e escala no Slack conforme o risco. | Python, Flask, Redis, SQLite, Docker Compose |
| [checklist-hardening](https://github.com/joaovpzdev/checklist-hardening) | Audita, sem alterar o sistema, SSH, firewall, atualizações e contas sem senha, com relatório PASS/WARN/FAIL. | Bash, Linux |
| [leak-monitor](https://github.com/joaovpzdev/leak-monitor) | Verifica e-mails em bases de vazamento e alerta apenas sobre vazamentos novos. | Node.js, cron, Slack/Discord |

### Red Team: reconhecimento, OSINT e gestão de achados

| Projeto | O que faz | Stack |
|---|---|---|
| [pentest-findings-dash](https://github.com/joaovpzdev/pentest-findings-dash) | Gestão de achados de pentest: importa Nmap, Nuclei e Burp Suite, deduplica reimportações e acompanha a remediação. | Node.js, React, PostgreSQL, Prisma |
| [visual-recon](https://github.com/joaovpzdev/visual-recon) | Captura screenshot, título e tecnologias de cada host e monta uma galeria HTML para triagem visual. | Node.js, Chromium headless |
| [cyber-sec-journey](https://github.com/joaovpzdev/cyber-sec-journey) | Documentação do meu estudo: metodologia de pentest, ferramentas do Kali Linux, SQL Injection e Bash. | Kali Linux, Bash |

---

## Stack

**Segurança e infraestrutura**

![Kali](https://img.shields.io/badge/Kali-%23268BEE?style=for-the-badge&logo=kalilinux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-%23FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Zabbix](https://img.shields.io/badge/Zabbix-%23CC0000?style=for-the-badge&logo=zabbix&logoColor=white)
![Python](https://img.shields.io/badge/Python-%233670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/Bash-%234EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Desenvolvimento**

![JavaScript](https://img.shields.io/badge/JavaScript-%23323330?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Node.js](https://img.shields.io/badge/Node.js-%236DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232a?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-%233982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033?style=for-the-badge&logo=git&logoColor=white)

---

## Certificações

- **Ethical Hacker**, Cisco
- **Introduction to Cybersecurity**, Cisco
- **Oracle Cloud Infrastructure Foundations Associate**, Oracle

---

## Em evolução

- Ampliar o laboratório de monitoramento com agentes Linux e comunicação criptografada (TLS/PSK) entre agente e servidor
- Integrar o SOAR de triagem a um SIEM de mercado
- Documentar cada aprendizado com prints e passo a passo para reproduzir

---

## Aviso de uso ético

As ferramentas de reconhecimento e pentest deste perfil são educacionais e devem ser usadas **apenas em ambientes que você possui ou tem autorização por escrito para testar**.

---

## Contato

[joaovpz.dev@gmail.com](mailto:joaovpz.dev@gmail.com) · [LinkedIn](https://www.linkedin.com/in/joao-victor-paixao-zolim)

<sub>Fora do computador: escalador, corredor e powerlifter.</sub>

![Snake animation](https://github.com/joaovpzdev/joaovpzdev/blob/output/github-contribution-grid-snake.svg)

<footer> ©JoaoVPZDev </footer>

