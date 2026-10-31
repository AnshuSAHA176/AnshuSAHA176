<!-- ═══════════════════════════════════════════════════════════════
     Profile README for github.com/AnshuSAHA176
     Repo must be named exactly: AnshuSAHA176/AnshuSAHA176 (public)
     ═══════════════════════════════════════════════════════════════ -->

<a id="readme-top"></a>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=240&color=0:0f2027,50:2c5364,100:6366f1&text=Anshu%20Saha&fontColor=ffffff&fontSize=58&fontAlignY=38&desc=Backend%20Engineer%20%C2%B7%20AI%20Systems%20Architect&descAlignY=60&descSize=18&animation=fadeIn" alt="Anshu Saha banner" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=818CF8&center=true&vCenter=true&width=720&height=50&lines=Backend+Engineer;AI+Systems+Architect;Distributed+Systems+Builder;Resilient+backends.+Autonomous+agents.+Real-time+pipelines." alt="Typing animation" />
</a>

<br>

<a href="https://github.com/AnshuSAHA176"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="mailto:anshusahaa62@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/in/anshu-saha-161539431/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<img src="https://komarev.com/ghpvc/?username=AnshuSAHA176&label=Profile%20views&color=6366f1&style=for-the-badge" alt="Profile views"/>

<br><br>

<b>
<a href="#focus">Focus</a> &nbsp;·&nbsp;
<a href="#stack">Stack</a> &nbsp;·&nbsp;
<a href="#projects">Projects</a> &nbsp;·&nbsp;
<a href="#stats">Stats</a> &nbsp;·&nbsp;
<a href="#connect">Connect</a>
</b>

</div>

<br>

<a id="focus"></a>

## 🎯 What I Do

<table>
<tr>
<td width="33%" valign="top">

### 🤖 Autonomous AI Agents
LLM-driven workflows that classify, analyze, route, and plan, wired into real backends rather than bolted on.

</td>
<td width="33%" valign="top">

### ⚡ Real-Time Systems
Persistent WebSocket connections and event-driven broadcasts for live dispatch and status updates.

</td>
<td width="33%" valign="top">

### 🧱 Resilient Backends
Constraint-first data modeling and background processing so heavy work never blocks the request path.

</td>
</tr>
</table>

<br>

<a id="stack"></a>

## 🛠️ Technology Stack

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=python,django,postgres,mongodb,redis,docker,linux,nginx,git,github&perline=10" alt="Core tech stack" />
</a>

<br><br>

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=graphql&logoColor=white" alt="LangGraph" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
<img src="https://img.shields.io/badge/Django_REST-A30000?style=for-the-badge&logo=django&logoColor=white" alt="DRF" />
<img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" alt="Celery" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright" />

</div>

<br>

<a id="projects"></a>

## 🚀 Featured Engineering

> 💡 **Click any project to expand** its architecture diagram and core mechanisms.

<details>
<summary><b>🤖 &nbsp;AI Career Intelligence Platform</b> &nbsp;·&nbsp; <i>job-market scraping + LLM skill-gap analysis</i></summary>

<br>

> **End-to-end career intelligence engine combining automated job-market scraping, resume parsing, and LLM-driven skill-gap analysis.**

```mermaid
flowchart LR
    A["Job-market sources"] -->|"Headless scraping"| B["Ingest and normalize"]
    B --> C[("PostgreSQL")]
    D["Resume upload"] -->|"Semantic parsing"| E["Candidate profile"]
    C --> F{{"Skill-gap analysis<br/>LangChain + LLM"}}
    E --> F
    F --> G["Personalized learning trajectory"]
```

**Architecture** &nbsp;
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)

**Core mechanisms**
- 🕸️ Headless scraping pipelines to ingest and normalize live job-market data.
- 📄 Semantic parsing of resumes to benchmark candidate profiles against market demands.
- 🧭 Agentic workflows that generate personalized learning trajectories.

<p align="right"><a href="https://github.com/AnshuSAHA176/AI-Career-Intelligence-Platform"><b>View repository →</b></a></p>

</details>

<details>
<summary><b>🏙️ &nbsp;CivicAI — Real-Time Issue Triage</b> &nbsp;·&nbsp; <i>event-driven reporting with AI agents</i></summary>

<br>

> **Event-driven civic reporting platform powered by intelligent triage workflows and bi-directional WebSocket communication.**

```mermaid
flowchart LR
    A["Citizen report"] --> B["Django API"]
    B --> C{{"AI triage agent<br/>classify · extract metadata · route"}}
    C --> D[("PostgreSQL")]
    C --> E["Redis channel layer"]
    E --> F["Django Channels<br/>WebSocket"]
    F --> G["Live dispatch and<br/>status broadcasts"]
```

**Architecture** &nbsp;
![Django Channels](https://img.shields.io/badge/Django_Channels-092E20?style=flat-square&logo=django&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_Agents-6366F1?style=flat-square)

**Core mechanisms**
- 📡 Real-time dispatch and status broadcasts over persistent WebSocket connections.
- 🧠 AI agents that classify incoming reports, extract metadata, and execute auto-routing.

<p align="right"><a href="https://github.com/AnshuSAHA176"><b>View repository →</b></a></p>

</details>

<details>
<summary><b>🏫 &nbsp;Academic Scheduling Engine</b> &nbsp;·&nbsp; <i>conflict-free timetables at scale</i></summary>

<br>

> **High-concurrency academic ERP backend engineered for conflict-free timetable generation and automated administrative workflows.**

```mermaid
flowchart LR
    A["Scheduling request"] --> B["Django API"]
    B -->|"enqueue"| C["Redis broker"]
    C --> D["Celery workers<br/>timetable computation"]
    D --> E[("PostgreSQL<br/>DB-level constraints")]
    E --> F["No teacher, batch,<br/>or room collisions"]
```

**Architecture** &nbsp;
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Core mechanisms**
- 🔒 Deterministic, DB-level constraints to prevent teacher, batch, and room collisions.
- ⚙️ Asynchronous background execution via Celery to offload heavy timetable computations.

<p align="right"><a href="https://github.com/AnshuSAHA176"><b>View repository →</b></a></p>

</details>

<br>

<a id="stats"></a>

## 📊 GitHub Analytics

<div align="center">

<!-- Cards below are generated into YOUR repo by .github/workflows/stats.yml (no third-party server needed) -->
<img width="49%" src="./profile-summary-card-output/tokyonight/3-stats.svg" alt="GitHub stats" />
<img width="49%" src="./profile-summary-card-output/tokyonight/2-most-commit-language.svg" alt="Top languages by commits" />

<br>

<img width="49%" src="./profile-summary-card-output/tokyonight/1-repos-per-language.svg" alt="Repos per language" />
<img width="49%" src="https://streak-stats.demolab.com?user=AnshuSAHA176&theme=tokyonight&hide_border=true" alt="GitHub streak" />

</div>

<details>
<summary><b>📈 &nbsp;Profile details</b> &nbsp;<i>(click to expand)</i></summary>

<br>

<div align="center">
  <img src="./profile-summary-card-output/tokyonight/0-profile-details.svg" alt="Profile details" width="70%" />
</div>

</details>

<br>

<div align="center">

<!-- Needs the snake.yml GitHub Action (see .github/workflows/snake.yml) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AnshuSAHA176/AnshuSAHA176/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AnshuSAHA176/AnshuSAHA176/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/AnshuSAHA176/AnshuSAHA176/output/github-snake.svg" />
</picture>

</div>

<br>

<a id="connect"></a>

## 🤝 Let's Connect

<div align="center">

I enjoy talking about backend architecture, agent workflows, and real-time systems.

<br>

<a href="mailto:anshusahaa62@gmail.com"><img src="https://img.shields.io/badge/Say_hello-anshusahaa62@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email me"/></a>
<a href="https://www.linkedin.com/in/anshu-saha-161539431/"><img src="https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"/></a>

<br><br>

**How I ship**

```mermaid
flowchart LR
    A["Requirements"] --> B["Architecture"] --> C["Distributed<br/>Processing"] --> D["Production"]
```

<i>⚡ Build. Break. Understand. Improve.</i>

<br>

<a href="#readme-top">⬆ Back to top</a>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:0f2027,50:2c5364,100:6366f1&section=footer" alt="footer" width="100%"/>

</div>
