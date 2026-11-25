<div align="center">

# Ksawery Bloch

### AI-Driven Developer · Prompt Engineer · Red Team Enthusiast

Full-stack, mobile and backend systems designed end to end — architecture, databases, CI/CD — with LLMs steered to write the code.

[![CV English](https://img.shields.io/badge/CV-English-1f6feb?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](cv/Ksawery_Bloch_CV_EN.pdf)
[![CV Polski](https://img.shields.io/badge/CV-Polski-d93f0b?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](cv/Ksawery_Bloch_CV_PL.pdf)
[![Email](https://img.shields.io/badge/Email-blochksawery%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:blochksawery@gmail.com)

🇬🇧 English · 🇵🇱 [Wersja polska](README.pl.md)

</div>

---

## About me

I build complete software systems as a solo developer. I design the logical architecture, model the data, set up CI/CD and Docker, and orchestrate LLMs to generate the implementation — while keeping every architectural decision, test and review in my own hands. That lets me deliver mobile, full-stack and system-level applications quickly and predictably.

Programming Technician student at **TechniSchools Lublin**. Languages: Polish (native), German (B2), English (B1/B2).

**Work model:** 100% remote, asynchronous, independent. I do my best work on well-scoped, self-contained systems with written communication (specs, issues, pull requests) instead of constant meetings, and I let the delivered work speak for itself. Based in Lublin, Poland; open to employers and clients worldwide.

> 📄 **Looking for a CV?** [English (PDF)](cv/Ksawery_Bloch_CV_EN.pdf) · [Polski (PDF)](cv/Ksawery_Bloch_CV_PL.pdf)

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| ⭐ **[Multimodal Fare Planner](https://github.com/TechniKsawery/multimodal-journey-fare-planner)** · [**live demo**](https://techniksawery.github.io/multimodal-journey-fare-planner/) | Journey planner for Poland and Germany that returns a route **and an explained cost estimate** (rail, city transit, FlixBus, flights; passenger profiles, discounts, city cards). Routing, pricing and UI are separate layers; every fare carries its source and a price-verification flag. **1,000+ tests**, **7 GitHub Actions workflows** (tests, GTFS freshness, fare-source monitoring, Pages deploy). | Python · FastAPI · Streamlit · MOTIS · GTFS/OSM · Docker |
| 📱 **[GradePredictor](https://github.com/TechniKsawery/grade-predictor)** | Cross-platform mobile app that syncs with the Librus school system (verified working) through custom Python extraction scripts, forecasts grade averages with Gemini AI, syncs with Google Calendar. PL/EN/DE. | Flutter · Dart · Riverpod · Supabase · Python · Gemini API |
| 🗂️ **[Mini Jira SaaS](https://github.com/TechniKsawery/mini-jira-team-management)** | Kanban team-management platform: real-time chat and presence (Socket.IO), teams and roles, analytics, attachments, audit trail. Strict layered backend (routes → controllers → services → repositories), JWT + RBAC, Zod validation, PostgreSQL Row Level Security, Docker Compose and CI. | TypeScript · React · Node.js · Supabase · Docker · GitHub Actions |
| ✍️ **[Editorial Workflow Automation](https://github.com/TechniKsawery/editorial-workflow-automation)** | CMS for editorial teams covering the whole article lifecycle (Idea → Draft → Review → Scheduled → Published) with a state machine, role system, calendar, scheduled-publishing worker and real-time WebSocket notifications. Monorepo with npm workspaces. | TypeScript · React · Vite · Prisma · Socket.IO |
| ⚽ **[Scout Pro](https://github.com/TechniKsawery/scout-pro-football-platform)** | Football scouting platform: player CRUD, custom SVG radar charts, reports with transfer recommendation, Gemini-powered analysis with a local fallback generator, watchlist, notifications, video, PDF export, RBAC (Admin / Head Scout / Scout). | TypeScript · React · Node.js · Prisma · Gemini AI |
| 🧪 **[E-Commerce QA Suite](https://github.com/TechniKsawery/sklepczekolada-test-automation)** | End-to-end test automation for a live online shop: 12 documented scenarios — search, filtering, cart, free-shipping threshold, login, registration, parcel-locker delivery, guest and B2B checkout, payment redirect. | Python · pytest · Playwright |

### Cybersecurity (authorized lab work only)

| Project | What it is |
|---|---|
| 🔴 **[Local Network Penetration Test Report](https://github.com/TechniKsawery/local-network-pentest-report)** | Authorized assessment in a controlled lab: LLMNR/NBT-NS poisoning, DHCPv6/IPv6 MITM (mitm6), NTLM relay and ARP poisoning against Windows 10/11. Full report with executive summary, attack-vector table, findings, hardening recommendations — including which defenses held. *Kali · Responder · impacket · bettercap · nmap* |
| 🔴 **[Windows Red Team Labs](https://github.com/TechniKsawery/windows-red-team-lab)** | Hands-on labs on my own hardware: NTFS file carving and data recovery, offline NTLM hash extraction, and an analysis of Windows Hello, TPM 2.0 and BitLocker protections, each with lessons learned. |

### Also

- **[Dental practice website](https://gabinet-powierza-bloch.pages.dev/)** — live site for a dental practice in Lublin: interactive tooth-anatomy diagram, open/closed status computed from opening hours, dark-mode and larger-font toggles. Built with Astro and hosted on Cloudflare Pages.
- **[KSeF 2.0 QR Code Generator](https://github.com/TechniKsawery/ksef-qr-portfolio)** — case study of a commercial B2B PHP module generating official verification QR codes (KOD I) for Polish e-invoices: SHA-256 / Base64URL handling, SVG and PNG output.
- **[Hotel Database](https://github.com/TechniKsawery/hotel-database-management-system)** — MS SQL Server schema with stored procedures, triggers and views, plus a PHP admin dashboard.
- **[PAI2 REST API](https://github.com/TechniKsawery/pai2-rest-api)** — TypeScript + Express + MongoDB API with Swagger docs, Jest tests and a Postman collection.
- **[Deep Space Social App](https://github.com/TechniKsawery/deep-space-social-app)** — Flutter + Supabase social app (auth, realtime feed, storage, i18n) with a glassmorphism UI.
- **[Android Book Manager](https://github.com/TechniKsawery/android-book-manager)** — Kotlin Android app with a data / viewmodel / UI layering.
- **[C++ Console Project](https://github.com/TechniKsawery/cpp-console-project-2025)** — modular C/C++ console app built with CMake and Make.

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![MS SQL](https://img.shields.io/badge/MS_SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)

**Practices:** AI-assisted architecture · advanced prompt engineering · layered architecture (repository pattern) · JWT + RBAC · PostgreSQL Row Level Security · TDD · CI/CD · containerization · UML · authorized penetration testing.

## Contact

- 📧 [blochksawery@gmail.com](mailto:blochksawery@gmail.com)
- 🏫 [u30_ksablo_lbn@technischools.com](mailto:u30_ksablo_lbn@technischools.com)
- 💼 Open to remote roles and freelance projects — especially backend, full-stack, mobile (Flutter) and QA automation.
