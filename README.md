<div align="center">

# Reza Hashemian

**Backend Engineer · Python & Django · M.Sc. in Artificial Intelligence**

I design backend systems that stay correct under load — clean service boundaries,<br/>
money that always balances, and data models built for billions of rows.

<br/>

<a href="https://www.linkedin.com/in/rezahashemian"><img src="https://img.shields.io/badge/LinkedIn-1f2328?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iIzBBNjZDMiIgZD0iTTIwLjQ1IDIwLjQ1aC0zLjU2di01LjU3YzAtMS4zMy0uMDItMy4wNC0xLjg1LTMuMDQtMS44NSAwLTIuMTQgMS40NS0yLjE0IDIuOTR2NS42N0g5LjM1VjloMy40MXYxLjU2aC4wNWMuNDgtLjkgMS42NC0xLjg1IDMuMzctMS44NSAzLjYgMCA0LjI3IDIuMzcgNC4yNyA1LjQ2djYuMjh6TTUuMzQgNy40M2EyLjA2IDIuMDYgMCAxIDEgMC00LjEzIDIuMDYgMi4wNiAwIDAgMSAwIDQuMTN6TTcuMTIgMjAuNDVIMy41NlY5aDMuNTZ2MTEuNDV6TTIyLjIyIDBIMS43N0MuNzkgMCAwIC43NyAwIDEuNzN2MjAuNTRDMCAyMy4yMy43OSAyNCAxLjc3IDI0aDIwLjQ1Yy45OCAwIDEuNzgtLjc3IDEuNzgtMS43M1YxLjczQzI0IC43NyAyMy4yIDAgMjIuMjIgMHoiLz48L3N2Zz4%3D" alt="LinkedIn" /></a>
<a href="https://www.youtube.com/@learnbytes"><img src="https://img.shields.io/badge/YouTube-1f2328?style=flat-square&logo=youtube&logoColor=FF0000" alt="YouTube" /></a>
<a href="https://t.me/rezauplink"><img src="https://img.shields.io/badge/Telegram-1f2328?style=flat-square&logo=telegram&logoColor=26A5E4" alt="Telegram" /></a>
<a href="https://instagram.com/rezauplink"><img src="https://img.shields.io/badge/Instagram-1f2328?style=flat-square&logo=instagram&logoColor=E4405F" alt="Instagram" /></a>
<a href="https://gitlab.com/reza-hashemian"><img src="https://img.shields.io/badge/GitLab-1f2328?style=flat-square&logo=gitlab&logoColor=FC6D26" alt="GitLab" /></a>

</div>

<br/>

## About

I am a backend engineer based in Isfahan, Iran. Django is my primary framework; around it I build
distributed systems with message queues, search engines and caching layers, and in my own time I
write desktop tools in Python, Rust and Dart.

- 🎓 M.Sc. in Artificial Intelligence — Islamic Azad University, Isfahan (Khorasgan); B.Sc. in Computer Networks
- 🏆 1st place, National Information Technology Olympiad
- 🎥 Teaching programming on [Learn Bytes](https://www.youtube.com/@learnbytes)

## Featured work

### Noqrina — commerce & ERP platform &nbsp;<sub><code>private</code></sub>

A multi-seller commerce platform that grew into a full business suite: online marketplace,
in-store point of sale, settlement, double-entry accounting, CRM, HR and manufacturing — one
codebase, run as independent services.

| | |
| --- | --- |
| **Architecture** | 15+ Django apps acting as microservices, each on its own PostgreSQL database; they talk only through RabbitMQ events with a transactional outbox and idempotent consumers |
| **Scale** | Partitioned ledgers and running-balance snapshots instead of summing history; a nightly health engine detects and repairs drift |
| **Finance** | Double-entry accounting with Jalali fiscal years, period locks, cost centers and year-end closing; seller settlement with held and released balances |
| **Delivery** | Typesense search, Varnish for public APIs, Redis for private ones, Celery workers, MinIO storage, Docker |
| **Quality** | 350k+ lines of Python covered by 6,500+ tests |

<sub>Django · DRF · PostgreSQL · RabbitMQ · Celery · Redis · Typesense · Varnish · Nginx · Docker</sub>

## Open source

| Project | Description | Stack |
| --- | --- | --- |
| [**tondar**](https://github.com/reza-hashemian/tondar) | Download manager with multi-connection resumable downloads, playlists, a scheduler and a browser extension | Python |
| [**amvault**](https://github.com/reza-hashemian/amvault) | Offline password and SSH key vault in KeePass format — desktop GUI, CLI and temporary ssh-agent loading | Python |
| [**eyecare-theme**](https://github.com/reza-hashemian/eyecare-theme) | Eye-comfort themes applied across terminals and editors at once, ranked by measured WCAG contrast | Python |
| [**dastbedast**](https://github.com/reza-hashemian/dastbedast) | Cross-device file transfer for Windows, Linux and Android — pair once, no server | Rust |
| [**nava**](https://github.com/reza-hashemian/nava) | A calm music and video player built on Slint and libmpv | Rust |
| [**varagh**](https://github.com/reza-hashemian/varagh) | PDF and EPUB reader with highlights, notes, notebooks and Trello-style tasks | Dart |
| [**shellter**](https://github.com/reza-hashemian/shellter) | One-script zsh setup that restores the same shell on any fresh machine | Shell |

## Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-1f2328?style=flat-square&logo=python&logoColor=3776AB" alt="Python" />
  <img src="https://img.shields.io/badge/Django-1f2328?style=flat-square&logo=django&logoColor=44B78B" alt="Django" />
  <img src="https://img.shields.io/badge/DRF-1f2328?style=flat-square&logo=django&logoColor=A30000" alt="Django REST Framework" />
  <img src="https://img.shields.io/badge/Celery-1f2328?style=flat-square&logo=celery&logoColor=37814A" alt="Celery" />
  <img src="https://img.shields.io/badge/Rust-1f2328?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Dart-1f2328?style=flat-square&logo=dart&logoColor=0175C2" alt="Dart" />
</p>
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-1f2328?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-1f2328?style=flat-square&logo=redis&logoColor=DC382D" alt="Redis" />
  <img src="https://img.shields.io/badge/RabbitMQ-1f2328?style=flat-square&logo=rabbitmq&logoColor=FF6600" alt="RabbitMQ" />
  <img src="https://img.shields.io/badge/Typesense-1f2328?style=flat-square" alt="Typesense" />
  <img src="https://img.shields.io/badge/MongoDB-1f2328?style=flat-square&logo=mongodb&logoColor=47A248" alt="MongoDB" />
</p>
<p>
  <img src="https://img.shields.io/badge/Docker-1f2328?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
  <img src="https://img.shields.io/badge/Nginx-1f2328?style=flat-square&logo=nginx&logoColor=009639" alt="Nginx" />
  <img src="https://img.shields.io/badge/Varnish-1f2328?style=flat-square" alt="Varnish" />
  <img src="https://img.shields.io/badge/Linux-1f2328?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-1f2328?style=flat-square&logo=git&logoColor=F05032" alt="Git" />
  <img src="https://img.shields.io/badge/Neovim-1f2328?style=flat-square&logo=neovim&logoColor=57A143" alt="Neovim" />
</p>

## Activity

<!-- Cards are generated daily into this repo by .github/workflows/profile-cards.yml -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile-summary-card-output/github_dark/3-stats.svg" />
    <img height="170" src="./profile-summary-card-output/github/3-stats.svg" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile-summary-card-output/github_dark/2-most-commit-language.svg" />
    <img height="170" src="./profile-summary-card-output/github/2-most-commit-language.svg" alt="Most committed languages" />
  </picture>
</div>

<br/>

<div align="center">
  <sub>Open to backend engineering roles and collaboration · Reach me on <a href="https://www.linkedin.com/in/rezahashemian">LinkedIn</a> or <a href="https://t.me/rezauplink">Telegram</a></sub>
</div>
