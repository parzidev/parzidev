# Parzidev

> Engineering README reviewed from the repository state on 2026-09-05. Observed facts are separated from items that still need manual verification.

**Repository:** [parzidev/parzidev](https://github.com/parzidev/parzidev)  
**Visibility:** public  
**Default branch:** `main`  
**Latest GitHub push observed:** `2026-08-30T13:33:41Z`  
**Scanned HEAD:** `4810fab73d4b368812fee3b1f71fd159e2f75c7d`  
**Repository description:** Not set on GitHub.

## Purpose and scope

<p align="center"> <a href="https://parzi.dev"><img src="./assets/header-v2.svg" alt="Parzi Dinç — Backend, API and AI Systems" width="100%" /></a> </p>

The repository currently contains **2** source-tree files, including **0** code-like files. This README describes the repository as it exists in the scanned snapshot; it is not a claim that every historical or runtime path is still active.

## Capability inventory

### README evidence

The source README exposes these sections: ``whoami``, ``products & systems``, ``open source snapshots``, ``toolbox``, ``live signals``, `Experience`, `Education`, ``connect``.

### Detected technology profile

| — | No code extension was available in the checkout. |

### Project structure

Top-level paths observed:

- `README.md`
- `assets`

Key entrypoint candidates:

- None detected in the static scan.

## Architecture and runtime shape

| Area | Observed evidence |
| --- | --- |
| Runtime shape | No Docker/Compose or conventional entrypoint was detected; inspect the structure below. |

Interpretation boundary: filenames and manifests show where a component may start, but they do not prove deployment topology, request flow, persistence semantics, or production readiness. Those items should be confirmed against the implementation before making operational claims about the project.

## Code-level signals

The following patterns were extracted from readable code files. They are navigation aids for the next human review, not a substitute for reading the implementation:

_No code-level signals were available from the local checkout; this may be an API-only tree scan._

## Setup and operation

The most relevant source README material is reproduced below:

No setup section was detected in the source README. Use the manifests and entrypoint candidates as the starting point for a manual runbook.

Static setup/deployment evidence:

- Docker files: none detected
- Build/config manifests: none detected
- Configuration-like paths: none detected

### Command evidence

_No fenced command/config blocks were detected in the source README._

## API, integrations, and data flow

No API/integration section was detected in the source README. External boundaries require code-level review before publication.

Before publishing a public README, confirm the following from code and deployment configuration:

- inbound routes, ports, webhooks, and authentication middleware;
- outbound providers, rate limits, retries, and failure behavior;
- persistence files/databases and backup/restore expectations;
- whether any endpoint can mutate external state.

## Configuration and secrets

Detected names (names only; values were intentionally excluded):

No conventional environment-variable names were detected in the sampled manifests/entrypoints.

Configuration paths observed:

- None detected in the static scan.

Do not paste real tokens, passwords, private keys, cookies, or production URLs into this README or a public README. Replace them with placeholders and document where the operator should provision them.

## Security and privacy

No dedicated security section was detected in the source README. Treat all detected environment names as secrets or operational configuration until verified.

Minimum publication checklist:

- document trust boundaries and the intended network exposure;
- explain authentication and authorization separately;
- state whether logs, uploads, identifiers, or third-party data are retained;
- include a responsible-use note where the project interacts with Steam, Kick, Riot, Spotify, Cloudflare, or other external platforms;
- keep example configuration values synthetic.

## Validation and maintenance

No validation section was detected in the source README. Static scan found the test candidates listed below; commands still need to be confirmed.

No test-like path was detected by filename; this does not prove that the project has no tests.

Test-like paths observed:

- None detected in the static scan.

CI/workflow and maintenance evidence should be verified before adding badges or claiming release guarantees.

## Known gaps and verification notes

- Repository snapshot was available for static inspection.
- This was a static documentation scan; no repository code, containers, network services, or test suites were executed.
- “Detected” means a filename, README section, manifest, or sampled entrypoint matched the scanner; it is not a security audit.
- README sections may describe an older state than the current code. Compare the published README with the latest default-branch files before committing it upstream.

## Reference README material (sanitized)

The relevant source README is retained below as reference material, with credential-shaped values removed.

<p align="center">
  <a href="https://parzi.dev"><img src="./assets/header-v2.svg" alt="Parzi Dinç — Backend, API and AI Systems" width="100%" /></a>
</p>

<p align="center">
  <a href="https://parzi.dev"><img src="https://img.shields.io/badge/parzi.dev-7C3F58?style=flat-square&logo=safari&logoColor=white" alt="Website" /></a>
  <a href="https://parzi.dev/cv.html"><img src="https://img.shields.io/badge/full_cv-9A5D45?style=flat-square&logo=readdotcv&logoColor=white" alt="Full CV" /></a>
  <a href="https://www.linkedin.com/in/parzi/"><img src="https://img.shields.io/badge/linkedin-6B625C?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:me@parzi.dev"><img src="https://img.shields.io/badge/me%40parzi.dev-403A36?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://log.parzi.dev/badge/parzidev.svg" alt="Profile visitors" />
</p>

## `whoami`

I am **Parzi Dinç**, an Istanbul-based backend and systems developer working across scalable APIs, real-time services, AI products, automation, iOS and developer tooling.

- Shipped **100+ client projects** covering APIs, scraping, automation and integrations.
- Built products serving **800k+ users** and public platforms reaching **600M+ views**.
- Launched an end-to-end AI/iOS product on the App Store.
- Comfortable owning the path from product idea and API contract to deployment, observability and production debugging.
- Also experienced in gaming communities, moderation, localization and player engagement.

`currently:` building reliable tools at the intersection of backend systems, AI and useful automation.

## `products & systems`

| Product | What it does | Built with |
|:--|:--|:--|
| **[Parzi Discord Bot](https://bot.parzi.dev)** | Flagship community automation platform with 19 background jobs, moderation, game integrations, persistent state and an OAuth control panel | Python, discord.py, Quart, Hypercorn, SQLite, aiohttp, Docker |
| **[StickerAI — Chibi Maker](https://apps.apple.com/tr/app/stickerai-chibi-maker/id6761774054?l=tr)** | App Store product with AI generation, credits, subscriptions, webhooks, app extensions and 14-language distribution | SwiftUI, MVVM, Vision, Cloudflare Workers, D1, fal.ai, RevenueCat |
| **[lolstat.data](https://test.parzi.dev)** | Riot match and player analytics, developer playground, OpenAPI surface, 24+ game datasets and a CatBoost-based ML prediction lab | Python, Flask, Riot API, CatBoost, scikit-learn, pandas, Docker |
| **[League Mastery](https://mastery.parzi.dev)** | Multi-region champion mastery search with player profiles, comparisons, JSON APIs and Voronoi-style visualizations | Python, Flask, Riot API, SQLite, JavaScript, Docker |
| **[timed.match](https://timed.parzi.dev)** | Match-V5 lookup that turns match and timeline data into a time-oriented report with a compact JSON API | Python, Flask, Riot Match-V5, JavaScript, Docker |
| **[LogParzi](https://log.parzi.dev)** | Self-hosted visitor analytics and security service with event tracking, IP/ASN intelligence, VPN/proxy/Tor detection, rate limits and public counters | Python, Flask, Gunicorn, Docker, JSON/TXT storage |
| **[Spoti Widget](https://spoti.parzi.dev)** | Spotify OAuth service with now-playing and history views, customizable embeds, OBS widgets, presets, caching and monitoring | Python, Flask, Spotipy, Redis, JavaScript, Docker |
| **[Fitbit Dashboard](https://fitbit.parzi.dev)** | Personal health dashboard for live steps, distance, calories, sleep, heart rate, goals, badges and activity history | Python, Flask, Fitbit Web API, local persistence, JavaScript, Docker |
| **[Feetle.lol](https://feetle.lol)** | Viral public platform that reached **600M+ views** | Python, JavaScript, web platform engineering |
| **[Kick API](https://kick.parzi.dev)** | Public streaming API used by **1,000+ users** | Python, REST, real-time services |
| **[Mastery API](https://mastery.parzi.dev)** | Riot API platform used by **500+ developers** | Python, APIs, caching, automation |
| **[CoC Analytics](https://coc.parzi.dev)** | Player, clan, war and CWL analytics with snapshots, caching, tests and rate limiting | Flask, SQLite, Gunicorn, Docker |
| **[Streaming & OBS tooling](https://kick.parzi.dev)** | WYSIWYG overlays, event monitors, subathon timers and multi-client state synchronization | WebSocket, Socket.IO, Python, JavaScript |

## `open source snapshots`

| Repository | Notes |
|:--|:--|
| [`docker-steam-hour-booster`](https://github.com/parzidev/docker-steam-hour-booster) | Dockerized multi-AppID Steam hour booster with persistent Steam Guard authentication |
| [`100-python-apps`](https://github.com/parzidev/100-python-apps) | A growing collection of focused Python mini-apps |
| [`magic-png`](https://github.com/parzidev/magic-png) | Compact C# image utility |

## `toolbox`

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,js,ts,swift,fastapi,flask,nodejs,express,docker,nginx,cloudflare,aws,git,githubactions,mongodb,sqlite&perline=8&theme=light" alt="Python, JavaScript, TypeScript, Swift, FastAPI, Flask, Node.js, Express, Docker, Nginx, Cloudflare, AWS, Git, GitHub Actions, MongoDB and SQLite" />
</p>

**Backend:** FastAPI · Flask · Node.js · Express · REST · GraphQL · WebSocket  
**Automation:** scraping · Selenium · Scrapy · integrations · bots  
**Data & AI:** SQLite · D1 · MongoDB · CatBoost · fal.ai · Gemini · analytics  
**Mobile:** SwiftUI · MVVM · Combine · Vision · iOS extensions  
**Infrastructure:** Docker · Nginx · Gunicorn · GitHub Actions · Cloudflare · AWS · Vercel

## `live signals`

<p align="center">
  <a href="https://discord.com/users/1013951210035875882">
    <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fbot.parzi.dev%2Fapi%2Fuser%2F1013951210035875882&amp;query=%24.status&amp;label=discord%20%E2%80%A2%20parzidev&amp;color=6B625C&amp;style=flat-square&amp;logo=discord&amp;logoColor=white" alt="Live Discord status from bot.parzi.dev" />
  </a>
</p>

<details>
<summary><strong>experience & education</strong></summary>

### Experience

- **Freelance Backend Developer — Fiverr** · 2022–present  
  International client work across APIs, automation, scraping and integrations.
- **Founder & Full-Stack iOS Developer — StickerAI** · 2026–present  
  End-to-end product, iOS, AI generation pipeline and backend ownership.
- **Independent Backend & Systems Developer**  
  High-traffic APIs, real-time services, analytics, observability and internal tools.
- **Community Manager & API Contributor — Heavy Metal Machines** · 2019–2020  
  Community growth, engagement, operations and API-supported workflows.
- Additional experience in League of Graphs Turkey community operations, export/e-commerce web support and NDA game systems.

### Education

- Software Engineering — Istinye University
- Management Information Systems — Anadolu University
- Computer Programming — Kastamonu University
- Turkish: native · English: B2

</details>

## `connect`

<p align="center">
  <a href="https://parzi.dev">Website</a> ·
  <a href="https://parzi.dev/cv.html">CV</a> ·
  <a href="https://www.linkedin.com/in/parzi/">LinkedIn</a> ·
  <a href="https://x.com/parzidev">X</a> ·
  <a href="https://www.instagram.com/parzi.dev">Instagram</a> ·
  <a href="https://discord.com/users/1013951210035875882">Discord</a> ·
  <a href="mailto:me@parzi.dev">Email</a>
</p>

<p align="center"><code>build small · ship often · scale what matters</code></p>
