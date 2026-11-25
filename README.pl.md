<div align="center">

# Ksawery Bloch

### AI-Driven Developer · Prompt Engineer · Pasjonat Red Team

Systemy full-stack, mobilne i backendowe projektowane od A do Z — architektura, bazy danych, CI/CD — z modelami LLM sterowanymi do pisania kodu.

[![CV English](https://img.shields.io/badge/CV-English-1f6feb?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](cv/Ksawery_Bloch_CV_EN.pdf)
[![CV Polski](https://img.shields.io/badge/CV-Polski-d93f0b?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](cv/Ksawery_Bloch_CV_PL.pdf)
[![Email](https://img.shields.io/badge/Email-blochksawery%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:blochksawery@gmail.com)

🇵🇱 Polski · 🇬🇧 [English version](README.md)

</div>

---

## O mnie

Buduję kompletne systemy informatyczne jako solo developer. Projektuję architekturę logiczną, modeluję dane, konfiguruję CI/CD i Dockera, a implementację generuję, sterując modelami LLM — przy czym każda decyzja architektoniczna, test i przegląd kodu zostaje w moich rękach. Dzięki temu szybko i terminowo dostarczam aplikacje mobilne, full-stackowe i systemowe.

Uczeń technikum, profil Technik Programista, **TechniSchools Lublin**. Języki: polski (ojczysty), niemiecki (B2), angielski (B1/B2).

**Model pracy:** 100% zdalnie, asynchronicznie, samodzielnie. Najlepiej pracuje mi się nad dobrze określonymi, zamkniętymi systemami, przy komunikacji pisemnej (specyfikacje, issues, pull requesty) zamiast ciągłych spotkań — niech mówi za mnie dostarczona robota. Lublin; otwarty na współpracę z firmami i klientami z całego świata.

> 📄 **Szukasz CV?** [Polski (PDF)](cv/Ksawery_Bloch_CV_PL.pdf) · [English (PDF)](cv/Ksawery_Bloch_CV_EN.pdf)

## Wybrane projekty

| Projekt | Opis | Stack |
|---|---|---|
| ⭐ **[Multimodal Fare Planner](https://github.com/TechniKsawery/multimodal-journey-fare-planner)** · [**demo na żywo**](https://techniksawery.github.io/multimodal-journey-fare-planner/) | Planer podróży Polska–Niemcy, który zwraca trasę **oraz wyjaśniony szacunek kosztu** (kolej, transport miejski, FlixBus, loty; profile pasażerów, ulgi, karty miejskie). Routing, wycena i UI to osobne warstwy, a każda taryfa ma wskazane źródło i flagę weryfikacji ceny. **Ponad 1000 testów**, **7 workflow GitHub Actions** (testy, aktualność GTFS, monitoring źródeł taryf, deploy na Pages). | Python · FastAPI · Streamlit · MOTIS · GTFS/OSM · Docker |
| 🦷 **[Strona gabinetu stomatologicznego](https://gabinet-powierza-bloch.pages.dev/)** · [**strona na żywo**](https://gabinet-powierza-bloch.pages.dev/) | Działająca, produkcyjna strona gabinetu stomatologicznego w Lublinie: interaktywny rysunek budowy zęba, status „otwarte/zamknięte” liczony na żywo z godzin przyjęć, przełączniki ciemnego motywu i większej czcionki (zapamiętywane), odnośniki do mapy i opinii. | Astro · JavaScript · HTML/CSS · Cloudflare Pages |
| 📱 **[GradePredictor](https://github.com/TechniKsawery/grade-predictor)** | Wieloplatformowa aplikacja mobilna synchronizowana z Librusem (działanie potwierdzone) przez autorskie skrypty Pythona, prognozuje średnie ocen z Gemini AI, synchronizuje się z Google Calendar. PL/EN/DE. | Flutter · Dart · Riverpod · Supabase · Python · Gemini API |
| 🗂️ **[Mini Jira SaaS](https://github.com/TechniKsawery/mini-jira-team-management)** | Platforma Kanban do zarządzania zespołem: czat i status online w czasie rzeczywistym (Socket.IO), zespoły i role, analityka, załączniki, historia aktywności. Rygorystyczny backend warstwowy (routes → controllers → services → repositories), JWT + RBAC, walidacja Zod, PostgreSQL Row Level Security, Docker Compose i CI. | TypeScript · React · Node.js · Supabase · Docker · GitHub Actions |
| ✍️ **[Editorial Workflow Automation](https://github.com/TechniKsawery/editorial-workflow-automation)** | CMS dla redakcji obejmujący cały cykl życia artykułu (Idea → Draft → Review → Scheduled → Published): maszyna stanów, role, kalendarz, worker zaplanowanych publikacji i powiadomienia WebSocket. Monorepo z npm workspaces. | TypeScript · React · Vite · Prisma · Socket.IO |
| ⚽ **[Scout Pro](https://github.com/TechniKsawery/scout-pro-football-platform)** | Platforma scoutingowa dla klubów piłkarskich: CRUD zawodników, autorskie wykresy radarowe SVG, raporty z rekomendacją transferową, analiza Gemini z lokalnym generatorem awaryjnym, watchlista, powiadomienia, wideo, eksport PDF, RBAC (Admin / Head Scout / Scout). | TypeScript · React · Node.js · Prisma · Gemini AI |
| 🧪 **[E-Commerce QA Suite](https://github.com/TechniKsawery/sklepczekolada-test-automation)** | Automatyzacja testów E2E działającego sklepu internetowego: 12 udokumentowanych scenariuszy — wyszukiwanie, filtrowanie, koszyk, próg darmowej dostawy, logowanie, rejestracja, paczkomat, zamówienia gościa i B2B, przekierowanie do płatności. | Python · pytest · Playwright |

### Cyberbezpieczeństwo (wyłącznie autoryzowane laboratoria)

| Projekt | Opis |
|---|---|
| 🔴 **[Raport z testów penetracyjnych sieci lokalnej](https://github.com/TechniKsawery/local-network-pentest-report)** | Autoryzowany audyt w kontrolowanym środowisku: poisoning LLMNR/NBT-NS, DHCPv6/IPv6 MITM (mitm6), NTLM relay i ARP poisoning wobec Windows 10/11. Pełny raport ze streszczeniem wykonawczym, tabelą wektorów ataku, wynikami i rekomendacjami — także tym, co zadziałało po stronie obrony. *Kali · Responder · impacket · bettercap · nmap* |
| 🔴 **[Windows Red Team Labs](https://github.com/TechniKsawery/windows-red-team-lab)** | Laboratoria na własnym sprzęcie: file carving i odzyskiwanie danych z NTFS, offline'owa ekstrakcja hashy NTLM oraz analiza zabezpieczeń Windows Hello, TPM 2.0 i BitLocker, każde z wnioskami. |

### Dodatkowo

- **[Generator QR KSeF 2.0](https://github.com/TechniKsawery/ksef-qr-portfolio)** — studium przypadku komercyjnego modułu PHP (zlecenie B2B) generującego oficjalne kody weryfikacyjne QR (KOD I) dla polskich e-faktur: SHA-256 / Base64URL, wyjście SVG i PNG.
- **[Baza danych hotelu](https://github.com/TechniKsawery/hotel-database-management-system)** — schemat MS SQL Server z procedurami, wyzwalaczami i widokami oraz panel administracyjny w PHP.
- **[PAI2 REST API](https://github.com/TechniKsawery/pai2-rest-api)** — API w TypeScript + Express + MongoDB z dokumentacją Swagger, testami Jest i kolekcją Postman.
- **[Deep Space Social App](https://github.com/TechniKsawery/deep-space-social-app)** — aplikacja społecznościowa we Flutterze + Supabase (auth, feed realtime, storage, i18n) w stylu glassmorphism.
- **[Android Book Manager](https://github.com/TechniKsawery/android-book-manager)** — aplikacja na Androida w Kotlinie z warstwami data / viewmodel / UI.
- **[Projekt konsolowy C++](https://github.com/TechniKsawery/cpp-console-project-2025)** — modularna aplikacja C/C++ budowana CMake i Make.

## Technologie

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

**Praktyki:** architektura wspierana przez AI · zaawansowany prompt engineering · architektura warstwowa (wzorzec repozytorium) · JWT + RBAC · PostgreSQL Row Level Security · TDD · CI/CD · konteneryzacja · UML · autoryzowane testy penetracyjne.

## Kontakt

- 📧 [blochksawery@gmail.com](mailto:blochksawery@gmail.com)
- 🏫 [u30_ksablo_lbn@technischools.com](mailto:u30_ksablo_lbn@technischools.com)
- 💼 Otwarty na zdalne zatrudnienie i projekty freelance — szczególnie backend, full-stack, mobile (Flutter) i automatyzacja testów.
