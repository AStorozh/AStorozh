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

[Production](#) · [Repository](#)

<br clear="left">

<div align="justify">

A personal AI assistant on my MacBook, reachable from Telegram, Android and voice. A coordinator delegates to 6 agents — browser, terminal, code, memory, judging — through my own agentic loop with no framework: retries, model fallbacks, loop guards. Memory is hybrid: SQLite+FTS5 plus vector search via reciprocal rank fusion. The voice pipeline runs fully locally (llama.cpp, whisper.cpp). 1,500+ automated tests.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/luma-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/luma-black.svg">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/luma-black.svg">
</picture>

### Luma

[Production](#) · [Repository](#)

<br clear="left">

<div align="justify">

A personal operating system for life on TypeScript/Next.js: a Mac app (Electron) and mobile (Capacitor). Data lives in an embedded local Postgres (PGlite) and never leaves the device, aside from real-time sync with Google Sheets. The AI advisor reaches 121 tools through one registry — chat, REST, my own MCP server — compatible with Claude Code and Cursor. A log of tool calls is injected into the chat history so the model doesn't forget its own actions.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-black.svg">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/hireflow-black.svg">
</picture>

### HIREFLOW

[Production](#) · [Repository](#)

<br clear="left">

<div align="justify">

An LLM-based job-matching service on Python/FastAPI: résumé → hh.ru vacancy scoring → cover letter. Batched LLM scoring (OpenAI API) cut matching cost by about a third. Every prompt change runs through an eval gate in CI. Distilled the LLM's scores into a small local ranking model and validated it on a held-out set before turning it on. A REST Agent API lets external assistants use it, with scope-based permissions and prompt-injection defenses.

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/asto-a-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/asto-a-black.svg">
  <img align="left" width="70" hspace="15" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/asto-a-black.svg">
</picture>

### asto-portfolio.ru

[Production](#) · [Repository](#)

<br clear="left">

<div align="justify">

A portfolio site on Next.js/PostgreSQL with an AI assistant for recruiters. A voice assistant on the OpenAI Realtime API, web search, a CMS admin I built myself. Tool calling is guarded against SSRF and prompt injection on every request. A separate private API lets an autonomous AI agent edit the site's own content — with a dry-run mode, an audit trail and rollback. Self-hosted analytics with bot filtering, own VPS behind nginx and PM2.

</div>

---

<div align="center">

### Experience

</div>

#### Trading company

<div align="justify">

Designed an automation system for an e-commerce business on Wildberries from scratch. A Python/Selenium ETL pipeline works around the marketplace's bot defenses through 20 Chrome profiles. It updates roughly 20 data categories (orders, stock, finances, fines, ads) every minute with no human involvement — into PostgreSQL and Google Sheets. An LLM (Claude API) automatically replies to customer reviews. A separate ML module on visual embeddings (SigLIP2) finds the same product listed cheaper by a competitor from a photo — about 89% accuracy against 79% for a baseline model. 18 Telegram bots replace manual spreadsheet checks with instant alerts. In parallel, launched a separate e-commerce platform on Next.js for the company's second line of business.

</div>

#### Freelance

<div align="justify">

More than two years of independent client work alongside everything else: an e-commerce storefront and admin panel on Next.js, Telegram bots for shift tracking, reporting and alerts, competitor price monitoring, and a number of Google Sheets and Excel automations that quietly gave people back a few hours a week.

</div>

---

<div align="center">

### Contact

<a href="https://asto-portfolio.ru"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-site.svg?v=3"></a>&nbsp;&nbsp;
<a href="https://t.me/artemiistorozhevskikh"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-telegram.svg?v=3"></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/artemii-storozhevskikh/"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-linkedin.svg?v=3"></a>&nbsp;&nbsp;
<a href="mailto:astorozhevskikh@gmail.com"><img width="44" height="44" src="https://raw.githubusercontent.com/AStorozh/AStorozh/main/assets/icons/contact-email.svg?v=3"></a>

</div>
