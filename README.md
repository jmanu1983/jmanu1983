# Bonjour, je suis Jean-Manuel 👋

**Ingénieur systèmes de sécurité** spécialisé dans l'intégration de contrôle d'accès et l'infrastructure de sécurité physique.

## À propos

- 🔐 Je conçois et intègre des **systèmes de contrôle d'accès** (Nedap AEOS, DESFire, Wiegand)
- 🏗️ Je développe des outils d'automatisation pour les déploiements de sécurité à grande échelle
- 📅 J'intègre **Microsoft Graph / Outlook** avec les systèmes de sécurité physique
- 🌍 Basé à **Genève, Suisse**
- 💼 Ingénierie de sécurité physique pour des infrastructures critiques

## Stack technique

| Domaine | Technologies |
|---------|-------------|
| **Langages** | Python, PowerShell, JavaScript, SQL |
| **Contrôle d'accès** | Nedap AEOS, APIs SOAP/REST, MIFARE DESFire, Wiegand |
| **Backend** | Flask, FastAPI, SQL Server, SQLite |
| **Cloud** | Microsoft Graph API, MSAL, Azure AD, Outlook Calendars |
| **Automatisation** | Planificateur de tâches Windows, SSH, Import en masse |
| **Cryptographie** | AES-128, CMAC, Diversification de clés (NXP AN10922) |
| **Data** | Pandas, NumPy, Chart.js, détection d'anomalies |
| **Outils** | Git, SoapUI, Wireshark |

## Projets phares

### Plateforme
| Projet | Description | Tech |
|--------|-------------|------|
| [room-access-manager](https://github.com/jmanu1983/room-access-manager) | **Accès automatisé par calendrier Outlook** — Graph API + AEOS SOAP : accorde/révoque l'accès physique selon les réunions | Flask, MSAL, Graph API, Zeep, AEOS SOAP |
| [aeos-dashboard](https://github.com/jmanu1983/aeos-dashboard) | **Dashboard temps réel** — SOAP `findEvent` + vue SQL `vw_AeosEventLog`, WebSocket push | Flask, Zeep, SQL Server, SocketIO, Chart.js |
| [badge-lifecycle-manager](https://github.com/jmanu1983/badge-lifecycle-manager) | **Cycle de vie des badges** — provisionnement → révocation, sync `dbo.[import]` AEOS | FastAPI, SQLAlchemy, SQL Server, pyodbc |
| [access-log-analyzer](https://github.com/jmanu1983/access-log-analyzer) | **Analyse de sécurité** — Z-score, tailgating, rapports HTML, vue `vw_AeosEventLog` | Python, Pandas, NumPy, SQL Server |

### Intégration & automatisation
| Projet | Description | Tech |
|--------|-------------|------|
| [aeos-api](https://github.com/jmanu1983/aeos-api) | Passerelle REST API pour le contrôle d'accès Nedap AEOS | Flask, Zeep, MSAL |
| [aeos-web-client](https://github.com/jmanu1983/aeos-web-client) | Client SOAP navigateur pour AEOS | HTML, JS, CSS |
| [aeos-import-automation](https://github.com/jmanu1983/aeos-import-automation) | Automatisation de production pour l'import de prestataires AEOS | PowerShell, SQL Server |
| [key-diversification](https://github.com/jmanu1983/key-diversification) | Outil de diversification de clés AES/CMAC (NXP AN10922) | Python, PyCryptodome |
| [security-engineering-tools](https://github.com/jmanu1983/security-engineering-tools) | Collection d'utilitaires d'ingénierie sécurité | Python, PowerShell |
| [csv-to-excel-converter](https://github.com/jmanu1983/csv-to-excel-converter) | Convertisseur batch CSV vers Excel | PowerShell |

## Statistiques GitHub

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jmanu1983&show_icons=true&theme=default&hide_border=true)

---

*Construire des ponts entre sécurité physique et ingénierie logicielle.*
