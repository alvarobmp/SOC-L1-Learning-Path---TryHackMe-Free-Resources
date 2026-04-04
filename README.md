# 🛡️ SOC Analyst Roadmap — TryHackMe (Free Rooms Only)

> **A curated, priority-ordered list of free TryHackMe rooms for anyone building toward their first SOC Analyst role.**
> Built from 4 free room lists (All, Purple, Red, Blue tags) and organized by a real-world SOC skill progression.
>
> This roadmap works for **two types of people** — choose your path below.

---

## 🧭 Choose Your Starting Point

### 🟢 Path A — "I'm new to IT / I have no technical background"

You've never worked in IT, you're studying on your own, or you're coming from a completely different field. That's totally fine — this roadmap has you covered. You'll just need to spend more time on the foundational phases before moving into SOC-specific content.

**Your journey:** Pre-Security (TryHackMe Learning Path) → Phase 0 → Phase 1 → Phase 2 → Phase 3 → ...

**Before you start this roadmap, complete these free TryHackMe Learning Paths first:**
- [Pre-Security](https://tryhackme.com/path/outline/presecurity) — How the web works, networking basics, Linux and Windows fundamentals (completely free, ~40 hours)
- [Introduction to Cybersecurity](https://tryhackme.com/path/outline/introtocybersecurity) — What cybersecurity is, careers, first hands-on labs (~24 hours)

Once you finish those, come back and **start at Phase 0** of this roadmap.

**Estimated total time:** 22–28 weeks of focused study (including pre-security content)

---

### 🔵 Path B — "I already work or have worked in IT"

You've been a sysadmin, network engineer, helpdesk tech, developer, or have any hands-on IT experience. You already understand networks, operating systems, and command lines. You don't need to start from zero.

**Your journey:** Skip or skim Phase 0 and Phase 2 → Start at Phase 1 → Fast-track to Phase 3

**Rooms you can safely skip or skim very fast:**
- Networking Concepts / OSI model
- Linux & Windows Fundamentals
- DNS / HTTP in Detail
- What is Networking?
- Bash Scripting basics
- Inside a Computer System / Operating Systems Introduction

**Jump straight to Phase 3** (SIEM, log analysis, alert triage) after a quick pass through Phase 1. That's where the real SOC-specific learning begins.

**Estimated total time:** 10–17 weeks of focused study

---

## 📊 Overview

| Stat | Value |
|------|-------|
| Total rooms | 80+ |
| Cost | 100% Free |
| Phases | 6 + Phase 0 |
| Target role | SOC Analyst L1 → L2 |
| Estimated time (Path A) | 22–28 weeks |
| Estimated time (Path B) | 10–17 weeks |

---

## 🗺️ The Roadmap

---

### ⬜ Phase 0 — Absolute Foundations *(Path A only)*
*For people with zero IT background · do this before anything else*

> **Path B users:** You can skip this phase entirely. If you want to revisit any specific concept, feel free — but don't spend time here if you already know it.

| Room | Difficulty | Why it matters |
|------|-----------|----------------|
| Inside a Computer System | Easy | How computers work — CPU, RAM, storage |
| Computer Types | Easy | Servers, desktops, embedded systems |
| Operating Systems: Introduction | Easy | What an OS does and why it matters for security |
| What is Networking? | Info | How computers talk to each other |
| How Websites Work | Easy | What happens when you open a browser |
| Putting it all together | Easy | How the web works end-to-end |
| The CIA Triad | Easy | The 3 core principles of cybersecurity |
| Security Awareness | Info | Threat actors and why security matters |
| Cryptography for Dummies | Easy | Encryption basics — you'll see this everywhere in SOC |
| Search Skills | Easy | How to research effectively as a security professional |
| Linux Fundamentals Part 1 | Info | Essential Linux commands — you'll use these daily |
| Windows Fundamentals 1 & 2 | Info | Windows internals — most corporate environments run Windows |
| Introductory Networking | Easy | Networking tools: ping, traceroute, basic analysis |
| Introductory Researching | Easy | Research skills for investigating security incidents |

---

### Phase 1 — SOC Role & Security Foundations
*Week 1–2 (Path B) · After Phase 0 (Path A) · Understand the role before the tools*

| Room | Difficulty | Why it matters |
|------|-----------|----------------|
| SOC Fundamentals | Easy | SOC team structure, processes — read this first |
| SOC Role in Blue Team | Easy | L1/L2/L3 levels, career path, daily expectations |
| Starting Out In Cyber Sec | Easy | Career paths and growth routes in cybersecurity |
| Security Principles | Easy | CIA Triad, security models — foundation for all decisions |
| Vulnerabilities 101 | Easy | CVEs, CVSS, vulnerability databases |
| IR Philosophy and Ethics | Easy | Incident response philosophy and ethics |
| Training Impact on Teams | Info | How security training fits inside organizations |

---

### Phase 2 — Networks, OS & Base Tools
*Week 3–4 (Path B) · Covered in Phase 0 for Path A — just reinforce what you need*

> **Path A users:** You covered most of this in Phase 0 and the Pre-Security path. Focus on rooms marked ★ which go deeper than the basics.
>
> **Path B users:** Skim what you know, spend time on what's new. The ★ rooms are worth doing regardless of experience.

| Room | Difficulty | Why it matters |
|------|-----------|----------------|
| Networking Concepts | Easy | OSI/TCP-IP model in depth |
| DNS in Detail | Easy | DNS: attack vector and key forensic artifact |
| HTTP in Detail | Easy | HTTP protocol — base for web traffic analysis |
| ★ Network Traffic Basics | Easy | Traffic capture and analysis with SOC tools |
| ★ Nmap | Easy | Network scanning — recognize attacker reconnaissance |
| Windows Basics | Easy | System navigation and Windows tools |
| Linux Strength Training | Easy | Build Linux CLI speed for incident work |
| ★ Linux CLI - Shells Bells | Easy | Advanced Linux CLI for incident investigation |
| ★ Bash Scripting | Easy | Automate repetitive SOC triage tasks |
| ★ CyberChef: The Basics | Easy | Essential tool for decoding IOCs and payloads |
| Regular Expressions | Medium | Pattern matching — used in SIEM rules and log parsing |
| Cryptography Basics | Easy | Encryption in practice — relevant to analyzing malicious traffic |

---

### Phase 3 — SIEM, Log Analysis, Alert Triage & Threat Intel
*Week 5–8 (Path B) · Week 9–13 (Path A) · Core of daily SOC L1 work — this is the most important phase*

> This is where the real SOC training begins for everyone. Do not skip any of the rooms in bold.

| Room | Difficulty | Why it matters |
|------|-----------|----------------|
| **SOC L1 Alert Triage** | Easy | Systematic triage methodology — the exact L1 daily process |
| **SOC L1 Alert Reporting** | Easy | How to escalate and document high-risk alerts |
| **SOC Alert Triaging - Tinsel Triage** | Medium | Real alert triage in Microsoft Sentinel |
| **Intro to Log Analysis** | Easy | Log analysis best practices and essential tools |
| **Log Analysis with SIEM** | Medium | Detect malicious behavior using SIEM |
| **Splunk Basics - Did you SIEM?** | Medium | Splunk: most requested SIEM in SOC job listings |
| Wazuh | Medium | Open-source SIEM: detection rules, dashboards, free to use |
| M365 Monitoring Basics | Medium | Entra ID and M365 logs — essential in corporate environments |
| Entra ID Monitoring | Medium | Threats and detection in Azure AD environments |
| XDR: Introduction | Medium | Microsoft Defender XDR — modern SOC standard platform |
| Introduction to EDR | Easy | EDR fundamentals and detection capabilities |
| **Threat Intelligence for SOC** | Medium | Integrate CTI into detection and response pipeline |
| **Pyramid Of Pain** | Easy | Model for prioritizing and categorizing IOCs — memorize this |
| File and Hash Threat Intel | Easy | Enrich file and hash IOCs with threat intelligence |
| Shodan.io | Easy | Exposed asset discovery for threat hunting |
| Linux Logging for SOC | Easy | Key Linux log sources for SOC triage |
| **Windows Threat Detection 1** | Medium | Detect Initial Access techniques on Windows |
| **Linux Threat Detection 1** | Medium | Detect Linux attacks by reading system logs |

> 💡 **Rooms in bold** are highest priority — do these before anything else in this phase.

---

### Phase 4 — Malware Analysis, Phishing & Incident Response
*Week 9–12 (Path B) · Week 14–17 (Path A) · Respond to the most common SOC incidents*

| Room | Difficulty | Why it matters |
|------|-----------|----------------|
| **Malware Classification** | Easy | Identify and classify common malware types |
| History of Malware | Info | How malware evolved — context for understanding modern threats |
| **Phishing - Phishmas Greetings** | Medium | Phishing is the #1 alert vector in SOC — learn to detect it |
| **C2 Detection - Command & Carol** | Medium | Detect C2 in large PCAPs — skill that separates L1 from L2 |
| **Incident Response Process** | Medium | NIST IR lifecycle on a compromised Windows workstation |
| Malware Analysis - Malhare.exe | Easy | Malware analysis and basic forensics |
| Malware Analysis - Egg-xecutable | Medium | Sandbox tooling for real malware analysis |
| APIWizards Breach | Medium | Investigate a real security breach end-to-end |
| Linux Incident Surface | Easy | Attacker footprints and incident surfaces on Linux |
| Linux Process Analysis | Easy | Process analysis to detect attacker persistence |
| Linux Server Forensics | Medium | Forensic artifacts on compromised Linux servers |
| Intro to Cold System Forensics | Easy | Offline forensics: DFIR concepts and methodology |

---

### Phase 5 — Web Vulnerabilities, CVEs & Advanced Detection
*Week 13–16 (Path B) · Week 18–22 (Path A) · Understand what attackers exploit*

| Room | Difficulty | Why it matters |
|------|-----------|----------------|
| Web Security Essentials | Easy | Common web app risks — every SOC analyst needs this |
| Broken Access Control | Easy | OWASP #1 — most frequent flaw in web alerts |
| OWASP Top 10 2025: IAAA Failures | Easy | A01, A07, A09 of the updated OWASP Top 10 |
| XSS - Merry XSSMas | Easy | XSS: types, detection and prevention |
| SSRF | Medium | Internal attacks from web apps — critical impact |
| SSTI | Medium | Server-side template injection — common attack vector |
| TryHack3M: Sch3Ma D3Mon | Medium | SQL injection — learn it to detect it in logs |
| YARA Rules | Medium | Anomaly detection with YARA rules |
| Threat Hunting With YARA | Medium | Active threat hunting using YARA in SOC |
| Follina MSDT (CVE-2022-30190) | Medium | Critical CVE with detection and remediation included |
| Outlook NTLM Leak (CVE-2023-23397) | Easy | Hash theft via email — heavily exploited in AD environments |
| CVE-2022-26923 (AD Cert Services) | Easy | Active Directory Certificate Services exploitation |
| Next.js CVE-2025-29927 | Easy | Authorization bypass in modern frameworks |
| Confluence CVE-2023-22515 | Easy | Admin bypass in Confluence — common corporate attack |
| APT28 Inception Theory | Medium | Real threat actor TTPs — advanced CTI perspective |
| AppSec IR | Medium | Intersection of AppSec and Incident Response |
| Chaining Vulnerabilities | Easy | How attacks escalate — full kill chain view |

---

### Phase 6 — Cloud, Modern Environments & Specialization
*Week 17+ (Path B) · Week 23+ (Path A) · SOC in the cloud*

| Room | Difficulty | Why it matters |
|------|-----------|----------------|
| AWS Basic Concepts | Easy | Mandatory foundation for AWS cloud environments |
| AWS IAM Initial Access | Medium | How attackers target IAM — critical for cloud alerts |
| STS Credentials Lab | Medium | Temporary credentials and privilege escalation in AWS |
| AWS S3 - Attack and Defense | Medium | S3 attacks: misconfigurations frequently seen in alerts |
| AWS API Gateway | Medium | Security and common attacks on API Gateway |
| AWS Lambda | Medium | Security aspects of AWS serverless service |
| Amazon EC2 - Attack & Defense | Medium | Compromise and defend EC2 instances |
| Lambda - Data Exfiltration | Medium | Exfiltration via serverless — growing attack vector |
| Intro to Containerisation | Easy | Container technology — understand the environment |
| Insekube | Easy | Kubernetes exploitation via Grafana LFI |
| K8s Best Security Practices | Medium | Kubernetes security best practices |
| AI/ML Security Threats | Easy | AI threats that SOC teams are already seeing |
| AI in Security | Easy | Using AI as a defensive tool in SOC |
| Nessus | Easy | Vulnerability scanner: interpret and prioritize findings |

---

## 🎯 Forensics Deep Dive (SOC L2 Skills)
*Optional — do these alongside Phase 4 or after, to level up toward L2*

| Room | Difficulty | Why it matters |
|------|-----------|----------------|
| Volatility Essentials | Medium | Memory forensics — core DFIR skill, very valued at L2 |
| KAPE | Medium | Forensic artifact collection and processing |
| Critical | Easy | Memory dump analysis in a practical scenario |
| MBR and GPT Analysis | Medium | Boot process forensics — detect bootkits |
| macOS Forensics: The Basics | Easy | macOS forensics: preparation and methodology |
| macOS Forensics: Artefacts | Hard | Advanced macOS forensic artifact analysis |
| Mobile Acquisition | Easy | Mobile device forensic acquisition |
| Legal Considerations in DFIR | Medium | Legal framework for digital evidence handling |
| FAT32 Analysis | Hard | FAT32 filesystem from a forensic perspective |

---

## 🗝️ Key Tags Legend

| Tag | Meaning |
|-----|---------|
| 🔵 Blue | Blue Team / Defensive / SOC focused |
| 🟣 Purple | Mixed offensive + defensive |
| 🔴 Red | Offensive / Red Team |
| ⚪ General | Platform-wide / fundamentals |

---

## 💡 Tips for Getting Your First SOC Job

1. **Document everything.** Every lab you do, screenshot it and push it to GitHub. Recruiters look at your repos.
2. **Build a home lab.** Wazuh SIEM is free and open source. A working SIEM lab beats 10 certifications on a resume.
3. **Learn the vocabulary.** Before interviews, make sure you can explain: IOC, TTP, kill chain, MITRE ATT&CK, false positive, escalation, triage.
4. **Use MITRE ATT&CK.** When you complete any room involving an attack technique, look it up in the ATT&CK framework. This builds pattern recognition fast.
5. **Apply early (Path B).** Phases 1–3 completed + a home lab is enough to start interviewing for L1 roles.
6. **Apply when ready (Path A).** Finish at least Phases 0–3 before applying. Use LetsDefend and CyberDefenders to practice real scenarios before interviews.

---

## 📚 Complementary Free Resources

| Resource | Best for |
|----------|----------|
| [MITRE ATT&CK Framework](https://attack.mitre.org/) | Adversary tactics and techniques — reference constantly |
| [CyberDefenders](https://cyberdefenders.org/) | Free Blue Team CTF labs — great for practice |
| [Blue Team Labs Online](https://blueteamlabs.online/) | SOC scenario practice |
| [LetsDefend](https://letsdefend.io/) | SOC simulation platform (free tier) — closest to real SOC work |
| [Cisco Networking Academy](https://www.netacad.com/) | Free cybersecurity courses — CyberOps Associate is excellent |
| [SANS Poster Collection](https://www.sans.org/posters/) | Free reference cheat sheets |
| [Professor Messer](https://www.professormesser.com/) | Free CompTIA Security+ study material — good for Path A |

---

## 🤝 Contributing

Found a room that should be on the list? Think a room should move to a different phase? Have suggestions for Path A resources?

- Open an issue describing the room and where you think it fits
- Submit a PR with your suggested change and a brief justification
- All suggestions welcome — especially from people currently working in SOC roles or who recently landed their first SOC job

---

## 👤 About This Project

This roadmap was built by cross-referencing 4 TryHackMe free room lists (All, Purple, Red, Blue tags) and applying a real-world SOC analyst skill progression — prioritizing what a L1 analyst actually does on day one, not just what sounds impressive on paper.

The two-path structure exists because the cybersecurity community is diverse: some people come from IT infrastructure, helpdesk, or networking backgrounds, while others are making a complete career change from unrelated fields. Both groups deserve a clear, honest path — not one-size-fits-all advice.

The goal is simple: give anyone a clear, no-nonsense, 100% free path into their first SOC role.

If this helped you, consider starring the repo ⭐ so others can find it.

---

---
---

# 🛡️ Roadmap Analista SOC — TryHackMe (Solo Rooms Gratuitos)

> **Lista curada y ordenada por prioridad de rooms gratuitos de TryHackMe para quienes buscan su primer empleo como Analista SOC.**
> Construida a partir de 4 listas de rooms gratuitos (tags: All, Purple, Red, Blue) y organizada según la progresión real de habilidades SOC.
>
> Este roadmap sirve para **dos tipos de personas** — elige tu ruta abajo.

---

## 🧭 Elige tu punto de partida

### 🟢 Ruta A — "Soy nuevo en TI / No tengo background técnico"

Nunca has trabajado en TI, estás estudiando por tu cuenta, o vienes de un campo completamente diferente. No hay problema — este roadmap te cubre. Solo necesitarás dedicar más tiempo a las fases fundacionales antes de entrar al contenido específico de SOC.

**Tu camino:** Pre-Security (Learning Path THM) → Fase 0 → Fase 1 → Fase 2 → Fase 3 → ...

**Antes de empezar este roadmap, completa estas rutas de aprendizaje gratuitas de TryHackMe:**
- [Pre-Security](https://tryhackme.com/path/outline/presecurity) — Cómo funciona la web, redes básicas, fundamentos de Linux y Windows (100% gratuito, ~40 horas)
- [Introduction to Cybersecurity](https://tryhackme.com/path/outline/introtocybersecurity) — Qué es la ciberseguridad, carreras, primeros labs prácticos (~24 horas)

Una vez termines esas rutas, vuelve aquí y **empieza en la Fase 0** de este roadmap.

**Tiempo total estimado:** 22–28 semanas de estudio enfocado (incluyendo el contenido pre-seguridad)

---

### 🔵 Ruta B — "Ya trabajo o he trabajado en TI"

Has sido sysadmin, técnico de redes, helpdesk, desarrollador, o tienes cualquier experiencia práctica en TI. Ya entiendes redes, sistemas operativos y línea de comandos. No necesitas empezar desde cero.

**Tu camino:** Omite o revisa rápido la Fase 0 y la Fase 2 → Empieza en la Fase 1 → Acelera hacia la Fase 3

**Rooms que puedes omitir o repasar muy rápido:**
- Conceptos de redes / modelo OSI
- Fundamentos de Linux y Windows
- DNS / HTTP en detalle
- What is Networking?
- Bash Scripting básico
- Inside a Computer System / Operating Systems Introduction

**Salta directamente a la Fase 3** (SIEM, análisis de logs, triage de alertas) después de un repaso rápido por la Fase 1. Ahí empieza el aprendizaje real específico de SOC.

**Tiempo total estimado:** 10–17 semanas de estudio enfocado

---

## 📊 Resumen

| Dato | Valor |
|------|-------|
| Rooms totales | 80+ |
| Costo | 100% Gratuito |
| Fases | 6 + Fase 0 |
| Rol objetivo | Analista SOC L1 → L2 |
| Tiempo estimado (Ruta A) | 22–28 semanas |
| Tiempo estimado (Ruta B) | 10–17 semanas |

---

## 🗺️ El Roadmap

---

### ⬜ Fase 0 — Fundamentos absolutos *(Solo Ruta A)*
*Para personas sin background en TI · haz esto antes que cualquier otra cosa*

> **Usuarios Ruta B:** Puedes saltarte esta fase por completo. Si quieres repasar algún concepto específico, adelante — pero no pierdas tiempo aquí si ya lo dominas.

| Room | Dificultad | Por qué importa |
|------|-----------|-----------------|
| Inside a Computer System | Fácil | Cómo funciona una computadora — CPU, RAM, almacenamiento |
| Computer Types | Fácil | Servidores, desktops, sistemas embebidos |
| Operating Systems: Introduction | Fácil | Qué hace un sistema operativo y por qué importa en seguridad |
| What is Networking? | Info | Cómo se comunican las computadoras entre sí |
| How Websites Work | Fácil | Qué pasa cuando abres un navegador |
| Putting it all together | Fácil | Cómo funciona la web de extremo a extremo |
| The CIA Triad | Fácil | Los 3 principios core de la ciberseguridad |
| Security Awareness | Info | Actores de amenaza y por qué importa la seguridad |
| Cryptography for Dummies | Fácil | Bases de cifrado — lo verás en todas partes en SOC |
| Search Skills | Fácil | Cómo investigar efectivamente como profesional de seguridad |
| Linux Fundamentals Part 1 | Info | Comandos Linux esenciales — los usarás todos los días |
| Windows Fundamentals 1 y 2 | Info | Windows por dentro — la mayoría de entornos corporativos usan Windows |
| Introductory Networking | Fácil | Herramientas de red: ping, traceroute, análisis básico |
| Introductory Researching | Fácil | Habilidades de investigación para incidentes de seguridad |

---

### Fase 1 — Rol SOC y fundamentos de seguridad
*Semana 1–2 (Ruta B) · Después de la Fase 0 (Ruta A) · Entiende el rol antes que las herramientas*

| Room | Dificultad | Por qué importa |
|------|-----------|-----------------|
| SOC Fundamentals | Fácil | Estructura del equipo SOC, procesos — leer primero |
| SOC Role in Blue Team | Fácil | Niveles L1/L2/L3, carrera y expectativas del rol |
| Starting Out In Cyber Sec | Fácil | Rutas de carrera y crecimiento en ciberseguridad |
| Security Principles | Fácil | CIA Triad, modelos de seguridad — base de toda decisión |
| Vulnerabilities 101 | Fácil | CVEs, CVSS, bases de datos de vulnerabilidades |
| IR Philosophy and Ethics | Fácil | Filosofía y ética de la respuesta a incidentes |
| Training Impact on Teams | Info | Cómo encaja la formación en seguridad dentro de las organizaciones |

---

### Fase 2 — Redes, sistemas operativos y herramientas base
*Semana 3–4 (Ruta B) · Cubierto en Fase 0 para Ruta A — solo refuerza lo que necesites*

> **Usuarios Ruta A:** Ya cubriste la mayoría de esto en la Fase 0 y el Pre-Security. Enfócate en los rooms marcados con ★ que van más profundo que lo básico.
>
> **Usuarios Ruta B:** Repasa lo que ya sabes, dedica tiempo a lo nuevo. Los rooms con ★ vale hacerlos sin importar tu experiencia previa.

| Room | Dificultad | Por qué importa |
|------|-----------|-----------------|
| Networking Concepts | Fácil | Modelo OSI/TCP-IP en detalle |
| DNS in Detail | Fácil | DNS: vector de ataque y artefacto forense clave |
| HTTP in Detail | Fácil | Protocolo HTTP — base para análisis de tráfico web |
| ★ Network Traffic Basics | Fácil | Captura y análisis de tráfico con herramientas SOC |
| ★ Nmap | Fácil | Escaneo de red — reconocer reconocimiento del atacante |
| Windows Basics | Fácil | Navegación y herramientas del sistema Windows |
| Linux Strength Training | Fácil | Ganar velocidad en CLI Linux para trabajo de incidentes |
| ★ Linux CLI - Shells Bells | Fácil | CLI avanzado Linux para investigación de incidentes |
| ★ Bash Scripting | Fácil | Automatizar tareas repetitivas de triage en SOC |
| ★ CyberChef: The Basics | Fácil | Herramienta imprescindible para decodificar IOCs y payloads |
| Regular Expressions | Medio | Coincidencia de patrones — se usa en reglas SIEM y parseo de logs |
| Cryptography Basics | Fácil | Cifrado en práctica — relevante para analizar tráfico malicioso |

---

### Fase 3 — SIEM, análisis de logs, triage de alertas e inteligencia de amenazas
*Semana 5–8 (Ruta B) · Semana 9–13 (Ruta A) · Núcleo del trabajo diario SOC L1 — la fase más importante*

> Aquí empieza el entrenamiento SOC real para todos. No omitas ninguno de los rooms en negrita.

| Room | Dificultad | Por qué importa |
|------|-----------|-----------------|
| **SOC L1 Alert Triage** | Fácil | Metodología sistemática de triage — el proceso exacto del día a día L1 |
| **SOC L1 Alert Reporting** | Fácil | Cómo escalar y documentar alertas de alto riesgo |
| **SOC Alert Triaging - Tinsel Triage** | Medio | Triage real de alertas en Microsoft Sentinel |
| **Intro to Log Analysis** | Fácil | Mejores prácticas de análisis de logs y herramientas esenciales |
| **Log Analysis with SIEM** | Medio | Detectar comportamiento malicioso usando SIEM |
| **Splunk Basics - Did you SIEM?** | Medio | Splunk: el SIEM más pedido en ofertas de empleo SOC |
| Wazuh | Medio | SIEM open-source: reglas de detección, dashboards, gratuito |
| M365 Monitoring Basics | Medio | Logs de Entra ID y M365 — esenciales en entornos corporativos |
| Entra ID Monitoring | Medio | Amenazas y detección en entornos Azure AD |
| XDR: Introduction | Medio | Microsoft Defender XDR — plataforma SOC moderna estándar |
| Introduction to EDR | Fácil | Fundamentos de EDR y capacidades de detección |
| **Threat Intelligence for SOC** | Medio | Integrar CTI al pipeline de detección y respuesta |
| **Pyramid Of Pain** | Fácil | Modelo para priorizar y categorizar IOCs — memoriza este |
| File and Hash Threat Intel | Fácil | Enriquecer IOCs de archivos y hashes con inteligencia |
| Shodan.io | Fácil | Búsqueda de activos expuestos para threat hunting |
| Linux Logging for SOC | Fácil | Fuentes de logs Linux clave para triage SOC |
| **Windows Threat Detection 1** | Medio | Detectar técnicas de Initial Access en Windows |
| **Linux Threat Detection 1** | Medio | Detectar ataques a Linux leyendo logs del sistema |

> 💡 Los **rooms en negrita** son máxima prioridad — hazlos antes que cualquier otro en esta fase.

---

### Fase 4 — Malware, phishing y respuesta a incidentes
*Semana 9–12 (Ruta B) · Semana 14–17 (Ruta A) · Responde a los incidentes más frecuentes en SOC*

| Room | Dificultad | Por qué importa |
|------|-----------|-----------------|
| **Malware Classification** | Fácil | Identificar y clasificar tipos comunes de malware |
| History of Malware | Info | Cómo evolucionó el malware — contexto para entender amenazas modernas |
| **Phishing - Phishmas Greetings** | Medio | Phishing es el vector #1 de alertas en SOC — aprende a detectarlo |
| **C2 Detection - Command & Carol** | Medio | Detectar C2 en PCAPs grandes — habilidad que separa L1 de L2 |
| **Incident Response Process** | Medio | Ciclo de vida NIST IR en workstation comprometida |
| Malware Analysis - Malhare.exe | Fácil | Análisis de malware y forense básico |
| Malware Analysis - Egg-xecutable | Medio | Herramientas de sandbox para análisis real de malware |
| APIWizards Breach | Medio | Investigar una brecha real de principio a fin |
| Linux Incident Surface | Fácil | Huellas del atacante y superficies de incidente en Linux |
| Linux Process Analysis | Fácil | Análisis de procesos para detectar persistencia del atacante |
| Linux Server Forensics | Medio | Artefactos forenses en servidores Linux comprometidos |
| Intro to Cold System Forensics | Fácil | Forense offline: conceptos y metodología DFIR |

---

### Fase 5 — Vulnerabilidades web, CVEs y detección avanzada
*Semana 13–16 (Ruta B) · Semana 18–22 (Ruta A) · Conoce lo que los atacantes explotan*

| Room | Dificultad | Por qué importa |
|------|-----------|-----------------|
| Web Security Essentials | Fácil | Riesgos comunes en apps web — todo analista SOC necesita esto |
| Broken Access Control | Fácil | OWASP #1 — falla más frecuente en alertas web |
| OWASP Top 10 2025: IAAA Failures | Fácil | A01, A07, A09 del OWASP Top 10 actualizado |
| XSS - Merry XSSMas | Fácil | XSS: tipos, detección y prevención |
| SSRF | Medio | Ataques internos desde apps web — impacto crítico |
| SSTI | Medio | Inyección en templates de servidor — vector común |
| TryHack3M: Sch3Ma D3Mon | Medio | SQL Injection — aprenderla para detectarla en logs |
| YARA Rules | Medio | Detección de anomalías con reglas YARA |
| Threat Hunting With YARA | Medio | Threat hunting activo con YARA en SOC |
| Follina MSDT (CVE-2022-30190) | Medio | CVE crítico de Windows con detección y remediación incluidas |
| Outlook NTLM Leak (CVE-2023-23397) | Fácil | Robo de hashes vía email — muy explotado en entornos con AD |
| CVE-2022-26923 (AD Cert Services) | Fácil | Explotación de Active Directory Certificate Services |
| Next.js CVE-2025-29927 | Fácil | Bypass de autorización en frameworks modernos |
| Confluence CVE-2023-22515 | Fácil | Admin bypass en Confluence — ataque corporativo común |
| APT28 Inception Theory | Medio | TTPs de un threat actor real — perspectiva CTI avanzada |
| AppSec IR | Medio | Intersección entre AppSec y respuesta a incidentes |
| Chaining Vulnerabilities | Fácil | Cómo escalan los ataques — visión kill chain completa |

---

### Fase 6 — Cloud, entornos modernos y especialización
*Semana 17+ (Ruta B) · Semana 23+ (Ruta A) · SOC en la nube*

| Room | Dificultad | Por qué importa |
|------|-----------|-----------------|
| AWS Basic Concepts | Fácil | Base obligatoria para entornos cloud AWS |
| AWS IAM Initial Access | Medio | Cómo atacan IAM — crucial para alertas cloud |
| STS Credentials Lab | Medio | Credenciales temporales y escalación de privilegios en AWS |
| AWS S3 - Attack and Defense | Medio | Ataques a S3: misconfiguraciones frecuentes en alertas |
| AWS API Gateway | Medio | Seguridad y ataques comunes al API Gateway |
| AWS Lambda | Medio | Aspectos de seguridad del servicio serverless de AWS |
| Amazon EC2 - Attack & Defense | Medio | Comprometer y defender instancias EC2 |
| Lambda - Data Exfiltration | Medio | Exfiltración vía serverless — vector creciente |
| Intro to Containerisation | Fácil | Tecnología de contenedores — entender el entorno |
| Insekube | Fácil | Explotación de Kubernetes vía LFI en Grafana |
| K8s Best Security Practices | Medio | Mejores prácticas de seguridad en Kubernetes |
| AI/ML Security Threats | Fácil | Amenazas de IA que el SOC moderno ya enfrenta |
| AI in Security | Fácil | Uso de IA como herramienta defensiva en SOC |
| Nessus | Fácil | Escáner de vulnerabilidades: interpretar y priorizar hallazgos |

---

## 🎯 Forense avanzado (habilidades SOC L2)
*Opcional — hazlos junto a la Fase 4 o después para escalar hacia L2*

| Room | Dificultad | Por qué importa |
|------|-----------|-----------------|
| Volatility Essentials | Medio | Forense de memoria — skill core DFIR, muy valorado en L2 |
| KAPE | Medio | Recolección y procesamiento de artefactos forenses |
| Critical | Fácil | Análisis de volcado de memoria en escenario práctico |
| MBR and GPT Analysis | Medio | Forense del proceso de arranque — detectar bootkits |
| macOS Forensics: The Basics | Fácil | Forense en macOS: preparación y metodología |
| macOS Forensics: Artefacts | Difícil | Análisis avanzado de artefactos forenses en macOS |
| Mobile Acquisition | Fácil | Adquisición forense de dispositivos móviles |
| Legal Considerations in DFIR | Medio | Marco legal para el manejo de evidencia digital |
| FAT32 Analysis | Difícil | Sistema de archivos FAT32 desde perspectiva forense |

---

## 💡 Consejos para conseguir tu primer empleo SOC

1. **Documenta todo.** Cada lab que hagas, tómale capturas y súbelo a GitHub. Los reclutadores revisan tus repos.
2. **Arma un home lab.** Wazuh SIEM es gratuito y open source. Un SIEM funcionando en tu lab vale más que 10 certificaciones en el CV.
3. **Aprende el vocabulario.** Antes de entrevistas, asegúrate de poder explicar: IOC, TTP, kill chain, MITRE ATT&CK, falso positivo, escalación, triage.
4. **Usa MITRE ATT&CK.** Cuando completes un room con una técnica de ataque, búscala en el framework ATT&CK. Construye reconocimiento de patrones rápidamente.
5. **Postula temprano (Ruta B).** Las Fases 1–3 completadas + un home lab es suficiente para empezar a entrevistar para roles L1.
6. **Postula cuando estés listo (Ruta A).** Termina al menos las Fases 0–3 antes de aplicar. Usa LetsDefend y CyberDefenders para practicar escenarios reales antes de entrevistas.

---

## 📚 Recursos gratuitos complementarios

| Recurso | Mejor para |
|---------|-----------|
| [MITRE ATT&CK Framework](https://attack.mitre.org/) | Tácticas y técnicas de adversarios — referencia constante |
| [CyberDefenders](https://cyberdefenders.org/) | Labs Blue Team gratuitos tipo CTF — excelente para práctica |
| [Blue Team Labs Online](https://blueteamlabs.online/) | Práctica de escenarios SOC |
| [LetsDefend](https://letsdefend.io/) | Simulación SOC (tier gratuito) — lo más parecido al trabajo real |
| [Cisco Networking Academy](https://www.netacad.com/) | Cursos gratuitos — CyberOps Associate es excelente |
| [SANS Poster Collection](https://www.sans.org/posters/) | Cheat sheets de referencia gratuitos |
| [Professor Messer](https://www.professormesser.com/) | Material gratuito CompTIA Security+ — bueno para Ruta A |

---

## 🤝 Contribuciones

¿Encontraste un room que debería estar en la lista? ¿Crees que algún room debería estar en una fase diferente? ¿Tienes sugerencias para recursos de la Ruta A?

- Abre un issue describiendo el room y dónde crees que encaja
- Envía un PR con tu sugerencia y una justificación breve
- Toda sugerencia es bienvenida — especialmente de personas que trabajan actualmente en SOC o que recientemente consiguieron su primer empleo SOC

---

## 👤 Acerca de este proyecto

Este roadmap fue construido cruzando 4 listas de rooms gratuitos de TryHackMe (tags: All, Purple, Red, Blue) y aplicando un marco de progresión de habilidades SOC real — priorizando lo que un analista L1 realmente hace el primer día de trabajo, no solo lo que suena impresionante en papel.

La estructura de dos rutas existe porque la comunidad de ciberseguridad es diversa: algunas personas vienen de infraestructura TI, helpdesk o redes, mientras otras hacen un cambio de carrera completo desde campos no relacionados. Ambos grupos merecen un camino claro y honesto — no consejos de talla única.

El objetivo es simple: darle a cualquier persona un camino claro, sin rodeos y 100% gratuito hacia su primer rol SOC.

Si esto te ayudó, considera darle una estrella al repo ⭐ para que otros puedan encontrarlo.

---

*Made with 💙 for the LATAM cybersecurity community*
