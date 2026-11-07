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

I build business automation on top of AI agents, at work and in my own projects. Mostly analytics and client-facing platforms.

Over three years in the industry: almost a year and a half at a trading company, plus more than two years of freelance work with clients.

I'm a fourth-year Product Management student at IThub College, so I usually start a task from the business problem, not from the code. Right now I'm moving from plugging in ready-made models to designing my own agent systems.

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

A personal AI assistant that lives on my MacBook. I talk to it through Telegram, an Android app or by voice. A coordinator hands tasks to three agents (browser, computer, code), and three background workers (judge, night cleanup, ears) run on their own.

It runs on my own agent loop without a framework, with retries, model fallbacks and loop guards. Memory combines full-text search (SQLite FTS5) and vector search. Speech recognition and the wake word run locally, live conversation goes through Gemini Live, and Claude does the thinking. 1,500+ automated tests.

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

A personal system for tasks, money, food and workouts: a Mac app (Electron) and an Android app (Capacitor) on TypeScript and Next.js. The data lives in a local database (PGlite) on the Mac and leaves it only if you turn on the Claude chat or the Google Sheets mirror.

The AI agent has 131 tools in one registry, available through the chat, a REST API and my own MCP server, so Claude Code and Cursor can work with it too. The agent sees a log of its own past actions in the chat history, so it doesn't forget what it has already done. 3,200+ automated tests.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-black.svg">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-black.svg">
</picture>

### HIREFLOW

[Production](https://hire-flow.website)

<br clear="left">

<div align="justify">

A job search assistant for hh.ru on Python and FastAPI. It reads a résumé, scores vacancies from 0 to 100 with reasons and drafts a cover letter. Batch scoring made matching about 51% cheaper and cut input tokens by 74%. Quality is checked on an eval suite with an LLM judge.

I also distilled the LLM scores into a small local ranking model, which is optional and off by default. An Agent API lets other AI assistants use the service, with key permissions (read, generate, write) and rate limits.

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

My portfolio site on Next.js and PostgreSQL with an AI assistant for recruiters. It answers in text and by voice (OpenAI Realtime API) and can search the web. Tool calls are protected against SSRF, and web content is marked as untrusted.

A separate private API lets my AI agent edit the site's content, with a dry run, an audit log and rollback. I also built the admin panel and self-hosted analytics with bot filtering. The site runs on my own VPS behind nginx and PM2.

</div>

---

<div align="center">

### Experience

</div>

#### Trading company

<div align="justify">

I built an automation system for a marketplace seller from scratch. A Python and Selenium pipeline downloads seller reports in parallel and updates about 16 metrics every few minutes: orders, stock, finances, fines and ads. The data goes to PostgreSQL and Google Sheets.

Claude replies to customer reviews and passes risky ones to a person. I also built a module that finds the same product at competitors by photo (SigLIP2: 89% vs 79% for CLIP), 18 Telegram bots for alerts, team data and reports, and an online store on Next.js for the company's new line of business.

</div>

#### Freelance

<div align="justify">

More than two years of client work: integrations, scripts, Telegram bots and spreadsheet automations. Later I ran whole projects with small teams: education platforms, travel services and online stores.

</div>

---

<div align="center">

### Contact

<a href="https://asto-portfolio.ru"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-site.svg?v=3"></a>&nbsp;&nbsp;
<a href="https://t.me/artemiistorozhevskikh"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-telegram.svg?v=3"></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/artemii-storozhevskikh/"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-linkedin.svg?v=3"></a>&nbsp;&nbsp;
<a href="mailto:astorozhevskikh@gmail.com"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-email.svg?v=3"></a>

</div>
