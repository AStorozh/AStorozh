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

I build business-process automation on top of AI agents, both at work and in my own projects, mostly around analytics and client-facing platforms. Over four years in the industry: almost a year and a half at a trading company and almost four years of independent work with clients.

I'm a fourth-year Product Management student at IThub College. That gives me a second lens: most of my tasks start as a business problem rather than a ticket. Right now I'm moving from integrating off-the-shelf models toward designing my own agentic systems.

</div>

---

<div align="center">

### Pet projects

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/sena-white.svg?v=3">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/sena-black.svg?v=3">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/sena-black.svg?v=3">
</picture>

### Sena

[Production](https://asto-portfolio.ru/s-gh) · [Repository](https://github.com/AStorozh/Sena)

<br clear="left">

<div align="justify">

A personal AI assistant on my MacBook (Python), reachable from Telegram, Android and voice. A Claude-based coordinator delegates tasks to 3 agents (browser, computer, code), while 3 more work in the background (judge, night cleanup, ears). Everything runs on my own agentic loop with no framework: retries, fallback between models, loop guards. Memory is hybrid: SQLite+FTS5 and vector search via reciprocal rank fusion. The voice pipeline is hybrid too: speech recognition and the wake word run locally (whisper.cpp), while live dialogue goes through Gemini Live. 1,500+ automated tests.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/luma-white.svg?v=3">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/luma-black.svg?v=3">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/luma-black.svg?v=3">
</picture>

### Luma

[Production](https://asto-portfolio.ru/l-gh) · [Repository](https://github.com/AStorozh/Luma)

<br clear="left">

<div align="justify">

A personal operating system for life on TypeScript/Next.js: a Mac app (Electron) and a mobile app (Capacitor). Data lives in an embedded local Postgres (PGlite) and never leaves the Mac, except for the Claude chat and the Google Sheets mirror, both optional. The AI advisor on the Claude API reaches 131 tools through a single registry (chat, REST, my own MCP server) and works with Claude Code and Cursor. A log of tool calls is injected into the chat history so the model doesn't forget its own actions.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-white.svg?v=3">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-black.svg?v=3">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-black.svg?v=3">
</picture>

### HIREFLOW

[Production](https://hire-flow.website/) · [Repository](https://github.com/AStorozh/Hire-flow)

<br clear="left">

<div align="justify">

An LLM job-matching service on Python/FastAPI: résumé → hh.ru vacancy scoring → cover letter. Batched LLM scoring (OpenAI API) cut matching cost by about 51% and input tokens by 74%. Prompt contracts are checked in CI, and the full eval suite runs locally. I distilled the LLM's scores into a local ranking model and validated it on a held-out set; it is turned on by a setting. A REST Agent API for external assistants, with key permissions and rate limits.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/asto-a-white.svg?v=3">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/asto-a-black.svg?v=3">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/asto-a-black.svg?v=3">
</picture>

### asto-portfolio.ru

[Production](https://asto-portfolio.ru/a-gh) · [Repository](https://github.com/AStorozh/asto-portfolio)

<br clear="left">

<div align="justify">

A portfolio site on Next.js/PostgreSQL with an AI assistant for recruiters. A voice assistant on the OpenAI Realtime API, web search, my own CMS admin. Tool calling is protected against SSRF, and web content is marked as untrusted to resist prompt injection. A separate private API lets an autonomous AI agent edit the site's content by itself, with a dry-run mode, an audit trail and rollback. Self-hosted analytics with bot filtering, my own VPS behind nginx and PM2.

</div>

---

<div align="center">

### Experience

</div>

#### Trading company

<div align="justify">

Designed an automation system for a marketplace seller from scratch. An ETL pipeline on Python and Selenium downloads seller reports in parallel through 20 browser profiles. It recalculates ~170 metrics for every product (orders, stock, finances, fines, ads) every minute with little human involvement, into PostgreSQL and Google Sheets. An LLM (Claude API) replies to customer reviews automatically. A separate ML module on visual embeddings (SigLIP2) finds the same product cheaper at competitors from a photo, with ~89% accuracy against 79% for CLIP. 18 Telegram bots for alerts, data intake from the team and reports. In parallel, I launched a separate online store on Next.js for the company's second line of business.

</div>

#### Freelance

<div align="justify">

Almost four years of independent client work alongside everything else: integrations, scripts, Telegram bots and custom spreadsheet automations, and later running whole projects with small teams (education platforms, travel services, online stores).

</div>

---

<div align="center">

### Contact

<a href="https://asto-portfolio.ru/gh"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-site.svg?v=3"></a>&nbsp;&nbsp;
<a href="https://t.me/artemiistorozhevskikh"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-telegram.svg?v=4"></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/artemii-storozhevskikh/"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-linkedin.svg?v=3"></a>&nbsp;&nbsp;
<a href="mailto:astorozhevskikh@gmail.com"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-email.svg?v=3"></a>

</div>
