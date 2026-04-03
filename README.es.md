# 🛡️ SOC L1 Learning Path — Recursos Gratuitos de TryHackMe

> Ruta de aprendizaje priorizada estratégicamente para aspirantes a **Analista SOC Nivel 1**, construida exclusivamente con rooms **gratuitos de TryHackMe**.  
> Diseñada con foco en el mercado peruano de ciberseguridad (contexto Ley 30096) y perfil de background en Linux/Red Hat.

---

## 📌 Sobre esta ruta

Esta **no** es una lista exhaustiva de todo lo que un analista SOC debería saber — es un **roadmap priorizado** enfocado en las habilidades que importan el Día 1 como SOC L1.

La lógica de secuencia es:
1. **Fundamentos conceptuales primero** — entender el SOC antes de tocar cualquier herramienta.
2. **Herramientas core L1 segundo** — triage, SIEM y threat intel son el pan de cada día.
3. **IR y detección tercero** — respuesta a incidentes y detección.
4. **Habilidades de escalamiento L2 cuarto** — análisis de malware y forense para crecer.
5. **Entornos cloud y corporativos quinto** — Azure/M365, relevante para el sector bancario peruano.
6. **Especialización avanzada al final** — para después de conseguir el rol.


---

## 🟥 Fase 1 — Hacer primero | Base Conceptual SOC

| Room | Dificultad | Duración | Por qué importa |
|------|-----------|----------|----------------|
| [SOC Fundamentals](https://tryhackme.com/r/room/socfundamentals) | 🟢 Fácil | 45 min | Punto de partida. Define qué hace un L1. |
| [Defensive Security Intro](https://tryhackme.com/r/room/defensivesecurityintro) | 🟢 Fácil | 25 min | Mapa mental completo: SIEM, DFIR, Threat Intel. |
| [SOC Role in Blue Team](https://tryhackme.com/r/room/socrolesinblueTeam) | 🟢 Fácil | 30 min | Jerarquía L1→L2→L3 y rutas de carrera. |
| [Security Principles](https://tryhackme.com/r/room/securityprinciples) | 🟢 Fácil | 90 min | CIA triad, modelos — base para cualquier entrevista. |
| [Junior Security Analyst Intro](https://tryhackme.com/r/room/jrsecanalystintrouxo) | 🟢 Fácil | 15 min | Un día real en el trabajo. Contexto motivacional. |

---

## 🟧 Fase 2 — Herramientas Core L1 | Triage, Alertas y SIEM

| Room | Dificultad | Duración | Por qué importa |
|------|-----------|----------|----------------|
| [SOC L1 Alert Triage](https://tryhackme.com/r/room/socl1alerttriage) | 🟢 Fácil | 60 min | Tu trabajo diario en 60 min. Hacer antes que cualquier SIEM. |
| [SOC L1 Alert Reporting](https://tryhackme.com/r/room/socl1alertreporting) | 🟢 Fácil | 60 min | Cómo escalar y documentar. Crítico para tus casos en GitHub. |
| [Log Analysis with SIEM](https://tryhackme.com/r/room/loganalysiswithsiem) | 🟡 Medio | 90 min | Detección de comportamiento malicioso en SIEM. Skill core. |
| [Splunk Basics](https://tryhackme.com/r/room/splunk101) | 🟡 Medio | 60 min | Splunk domina el mercado bancario latinoamericano. |
| [Network Traffic Basics](https://tryhackme.com/r/room/networktrafficanalysis) | 🟢 Fácil | 60 min | Captura y análisis de tráfico. Base antes de Wireshark. |
| [File and Hash Threat Intel](https://tryhackme.com/r/room/filehashinvestigations) | 🟢 Fácil | 64 min | VirusTotal, IOCs — conecta directo con tu repo de casos SOC. |

---

## 🟨 Fase 3 — Respuesta a Incidentes | IR, Playbooks y Detección

| Room | Dificultad | Duración | Por qué importa |
|------|-----------|----------|----------------|
| [IR Playbooks](https://tryhackme.com/r/room/irplaybooks) | 🟢 Fácil | 60 min | Plantillas de respuesta. Útil para documentar casos. |
| [Incident Response Process](https://tryhackme.com/r/room/incidentresponseprocess) | 🟡 Medio | 90 min | NIST lifecycle en workstation Windows comprometida. Muy completo. |
| [Linux Threat Detection 1](https://tryhackme.com/r/room/linuxthreatdetection) | 🟡 Medio | 60 min | Atacantes en Linux + detección en logs. Relevante para tu background. |
| [Linux Logging for SOC](https://tryhackme.com/r/room/linuxloggingfordefenders) | 🟢 Fácil | 45 min | Fuentes de logs Linux para triage. Complementa experiencia Red Hat. |
| [Network Security Essentials](https://tryhackme.com/r/room/networksecurityessentials) | 🟢 Fácil | 60 min | Monitoreo y protección de red. Puente entre tu infra y el SOC. |
| [Introduction to EDR](https://tryhackme.com/r/room/introtoedrandresponse) | 🟢 Fácil | 60 min | EDR es omnipresente en SOCs modernos. Conocerlo da puntos en entrevistas. |

---

## 🟦 Fase 4 — Habilidades de Escalamiento L2 | Malware y Forense

| Room | Dificultad | Duración | Por qué importa |
|------|-----------|----------|----------------|
| [Malware Classification](https://tryhackme.com/r/room/malwareclassification) | 🟢 Fácil | 45 min | Clasificar malware es la habilidad #1 al escalar alertas. |
| [Malware Analysis - Malhare.exe](https://tryhackme.com/r/room/malwareanalysisintro) | 🟢 Fácil | 60 min | Análisis estático/dinámico. Conecta con write-ups en GitHub. |
| [Linux Incident Surface](https://tryhackme.com/r/room/linuxincidentsurface) | 🟢 Fácil | 80 min | Rastros de incidente en Linux. Diferenciador dado tu perfil Red Hat. |
| [Linux Process Analysis](https://tryhackme.com/r/room/linuxprocessanalysis) | 🟢 Fácil | 60 min | Persistencia de atacantes vía procesos. Habilidad crítica. |
| [Intro to Cold System Forensics](https://tryhackme.com/r/room/introtocoldsystemforensics) | 🟢 Fácil | 60 min | DFIR offline. Fundamento antes de Volatility. |
| [Volatility Essentials](https://tryhackme.com/r/room/volatilityessentials) | 🟡 Medio | 60 min | Memory forensics. Habilidad diferenciadora para rol L2. |

---

## 🟪 Fase 5 — Cloud y Entornos Corporativos | Azure / M365

> Especialmente relevante para el sector bancario peruano (BCP, Scotiabank, Interbank, Kyndryl).

| Room | Dificultad | Duración | Por qué importa |
|------|-----------|----------|----------------|
| [M365 Monitoring Basics](https://tryhackme.com/r/room/m365monitoringbasics) | 🟡 Medio | 45 min | Entra ID + M365. Tu entorno actual en banca corporativa. |
| [Entra ID Monitoring](https://tryhackme.com/r/room/entraidmonitoring) | 🟡 Medio | 60 min | Amenazas Azure AD. Directamente aplicable a infra bancaria peruana. |
| [XDR: Introduction](https://tryhackme.com/r/room/xdrintroduction) | 🟡 Medio | 60 min | Microsoft Defender XDR. Estándar en banca latinoamericana. |

---

## ⬛ Fase 6 — Especialización Avanzada | Para después de conseguir el rol

| Room | Dificultad | Duración | Por qué importa |
|------|-----------|----------|----------------|
| [Threat Hunting With YARA](https://tryhackme.com/r/room/yara) | 🟡 Medio | 90 min | YARA es una habilidad diferenciadora. Conecta con tu Wazuh lab. |
| [Linux Server Forensics](https://tryhackme.com/r/room/linuxserverforensics) | 🟡 Medio | 75 min | Servidor Linux comprometido. Nivel L2/L3. |
| [C2 Detection](https://tryhackme.com/r/room/c2detection) | 🟡 Medio | 60 min | PCAP + C2. Habilidad avanzada para Tier 2. |
| [APÌWizards Breach](https://tryhackme.com/r/room/apiwizardsbreach) | 🟡 Medio | 90 min | Investigación completa de breach. Simulación realista. |
| [Malware Analysis - Egg-xecutable](https://tryhackme.com/r/room/malwareanalysisobjectives) | 🟡 Medio | 45 min | Sandbox analysis. Para tu repositorio de casos. |

---

## 🇵🇪 Contexto: Mercado Peruano de Ciberseguridad

Esta ruta está diseñada con el ecosistema peruano en mente:

- 📄 **Ley 30096 (Ley de Delitos Informáticos)** — Entender esta ley te da un diferenciador local al documentar casos y redactar reportes de incidentes. Referenciarla en tus write-ups de GitHub te posiciona como alguien que entiende el marco legal, no solo técnico.
- 🏦 **Foco en sector bancario** — Las Fases 2 y 5 apuntan directamente a ese stack.
- 🐧 **Background Red Hat / Linux** — Las Fases 3 y 4 serán más rápidas para ti que para la mayoría de candidatos. Úsalas para producir mejores write-ups y posicionarte como el especialista Linux del blue team.


## 📊 Resumen de la Ruta

| Fase | Enfoque | Rooms | Tiempo estimado |
|------|---------|-------|-----------------|
| 1 | Fundamentos SOC | 5 | ~3.5 hrs |
| 2 | Triage y SIEM | 6 | ~6 hrs |
| 3 | IR y Detección | 6 | ~6.5 hrs |
| 4 | Malware y Forense | 6 | ~5.5 hrs |
| 5 | Cloud / M365 | 3 | ~2.5 hrs |
| 6 | Avanzado | 5 | ~6.5 hrs |
| **Total** | | **31 rooms** | **~30 hrs** |

---

## ⚠️ Rooms Excluidos Intencionalmente

Los siguientes rooms **no son irrelevantes** — simplemente tienen bajo ROI para un objetivo L1 en esta etapa:

`Cicada-3301` · `Windows Reversing Intro` · `Windows x64 Assembly` · `FAT32 Analysis` · `MBR/GPT Analysis` · `macOS Forensics` · `Nessus` · `Joomify` · `Next.js CVE` · `Security Awareness` · `Módulos AI/ML Security`

> Pertenecen a un roadmap diferente — pentesting, ingeniería inversa o security engineering.

---

## 🔗 Contacto

- **TryHackMe:** [alvarobmp](https://tryhackme.com/p/alvarobmp)
- **LinkedIn:** [alvarobmp](https://www.linkedin.com/in/alvarobmp/)

---

*Construido para la comunidad de ciberseguridad peruana. Solo recursos gratuitos. Sin paywalls.*
