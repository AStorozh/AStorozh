<div align="center">


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/combined-white.svg?v=7">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/combined-black.svg?v=7">
  <img alt="asto — Artemii Storozhevskikh" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/combined-black.svg?v=7" width="480">
</picture>

---

**AI Automation Engineer & AI Agent Engineer**

</div>

<div align="justify">

I build business-process automation on top of AI agents — both at work and in my own projects, mostly around analytics and client-facing platforms. Over three years in the industry: a year in a trading company, plus two years before that working independently with clients.

Fourth-year Product Management student at IThub College — a second lens that makes most of my tasks start as a business problem rather than a ticket. Right now I'm moving from integrating off-the-shelf models toward designing my own agentic systems.

</div>

---

<div align="center">

### Pet projects

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/sena-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/sena-black.svg">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/sena-black.svg">
</picture>

### Sena

[Presentation](https://asto-portfolio.ru/sena/)

<br clear="left">

<div align="justify">

A personal AI assistant on my MacBook, reachable from Telegram, Android and voice. A coordinator hands work to 3 agents (browser, computer, code), and 3 background workers (judge, night cleanup, ears) run on their own. Everything runs on my own agentic loop with no framework: retries, model fallbacks, loop guards. Memory is hybrid: SQLite+FTS5 plus vector search via reciprocal rank fusion. Speech recognition, the wake word and the fallback voice run locally (whisper.cpp, Piper, openWakeWord); live conversation goes through Gemini Live, while Claude does the thinking. 1,500+ automated tests.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/luma-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/luma-black.svg">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/luma-black.svg">
</picture>

### Luma

[Presentation](https://asto-portfolio.ru/luma/)

<br clear="left">

<div align="justify">

A personal operating system for life on TypeScript/Next.js: a Mac app (Electron) and mobile (Capacitor). Data lives in an embedded local Postgres (PGlite). Data stays on the Mac; only the optional Claude chat and the optional two-way Google Sheets mirror send anything out. The AI advisor reaches 131 tools through one registry — chat, REST, my own MCP server — compatible with Claude Code and Cursor. A log of tool calls is injected into the chat history so the model doesn't forget its own actions.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-black.svg">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-black.svg">
</picture>

### HIREFLOW

<br clear="left">

<div align="justify">

An LLM-based job-matching service on Python/FastAPI: résumé → hh.ru vacancy scoring → cover letter. Batched LLM scoring (OpenAI API) cut matching cost by ~51% and input tokens by ~74%. Prompt contracts run in CI; the full eval suite runs locally on recorded answers. Distilled the LLM's scores into a small local ranking model, validated on a held-out set; it ships behind a feature flag. A REST Agent API lets external assistants use it, with scope-based keys (read / generate / write), rate limits and idempotent paid calls.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/asto-a-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/asto-a-black.svg">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/asto-a-black.svg">
</picture>

### asto-portfolio.ru

[Production](https://asto-portfolio.ru)

<br clear="left">

<div align="justify">

A portfolio site on Next.js/PostgreSQL with an AI assistant for recruiters. A voice assistant on the OpenAI Realtime API, web search, a CMS admin I built myself. Tool calling has an SSRF guard, and web content is marked as untrusted to resist prompt injection. A separate private API lets an autonomous AI agent edit the site's own content — with a dry-run mode, an audit trail and rollback. Self-hosted analytics with bot filtering, own VPS behind nginx and PM2.

</div>

---

<div align="center">

### Experience

</div>

#### Trading company

<div align="justify">

Designed an automation system for a marketplace seller from scratch. A Python/Selenium ETL pipeline downloads seller reports in parallel through 20 browser profiles. It updates ~16 metrics (orders, stock, finances, fines, ads), refreshed every few minutes with little human involvement, into PostgreSQL and Google Sheets. An LLM (Claude API) automatically replies to customer reviews. Built a module that finds the same product at competitors by photo (SigLIP2: 89% vs 79% for CLIP). 18 Telegram bots for alerts, data intake from the team and reports. In parallel, launched a separate online store on Next.js for the company's second line of business.

</div>

#### Freelance

<div align="justify">

More than two years of independent client work alongside everything else: integrations, scripts, Telegram bots and custom spreadsheet automations, plus running projects with small teams (education platforms, travel services, online stores).

</div>

---

<div align="center">

### Contact

<a href="https://asto-portfolio.ru"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-site.svg?v=3"></a>&nbsp;&nbsp;
<a href="https://t.me/artemiistorozhevskikh"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-telegram.svg?v=3"></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/artemii-storozhevskikh/"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-linkedin.svg?v=3"></a>&nbsp;&nbsp;
<a href="mailto:astorozhevskikh@gmail.com"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-email.svg?v=3"></a>

</div>
