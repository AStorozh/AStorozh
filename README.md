<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/output/github-snake.svg">
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/AStorozh/AStorozh/output/github-snake.svg">
</picture>

</div>

# Artemii Storozhevskikh

**Business Automation & AI Integration Engineer**

I design systems where business processes, data and AI meet: internal platforms that collect and structure information, automation that takes manual work out of daily operations, and LLM-driven services that make decisions inside a process rather than beside it.

Close to four years in the industry — over a year and a half in a trading company and more than two years of independent client work before and alongside it. What interests me is the whole loop rather than the isolated task: understand the process, find where it actually leaks time and money, instrument it, automate it, and make it explain itself when something breaks.

---

## Selected work

### My portfolio platform — [asto-portfolio.ru](https://asto-portfolio.ru)

Built end to end, and the place where I get to do things properly rather than quickly. Next.js 16 and React 19 over PostgreSQL with Drizzle, a CMS admin I wrote myself, a voice-capable AI assistant on the OpenAI Realtime API that answers questions about my experience, and self-hosted analytics with per-link campaign attribution — no third-party scripts and no cookie banner, because the data never leaves my own database. Three languages, deployed on my own VPS behind nginx and PM2.

### IA — a personal network of AI agents *(in development)*

Not a single assistant but a set of cooperating agents with shared memory, each owning a part of the work. It runs on its own database with persistent long-term memory, continuous voice capture and speech recognition, and a defined character: it holds opinions and pushes back instead of answering neutrally. Through a tool layer the agents reach the browser, the desktop, the phone and connected accounts, and hand tasks to each other depending on what is being asked.

The interesting problems here are not the model calls. They are orchestration between agents, deciding what is worth remembering and what should be forgotten, keeping an always-on system from becoming noisy or expensive, and giving it enough judgement to act without supervision. This is where most of my own time goes right now.

### Marketplace analytics platform

A full internal data loop for a trading company: every seller report pulled from the marketplace on a schedule, normalized into PostgreSQL, and published as finished pivot tables in Google Sheets and dashboards. Multiprocess orchestration with a shared logging protocol, so one scraper hitting a wall doesn't take down the run. It replaced a daily routine of manual downloads and copy-paste entirely.

### AI responses to customer reviews

A language model answers complaints while templates handle the straightforward positive ones. Structured JSON output, prompt caching and token accounting keep the cost per review predictable at volume. Anything ambiguous is deliberately *not* sent — it is parked for a human. Deciding what the model must refuse to do turned out to be the real design work, well ahead of the prompting.

### Self-reporting error layer

Once the data platform ran unattended, it needed to tell me when it broke. I wrote a layer that overrides `builtins.print` and the system `excepthook`, normalizes any traceback into one short readable line and writes it to a shared Postgres table, with a Telegram bot pushing each new row to subscribers in real time. A small piece of code that changed how fast I could debug everything around it.

### HIREFLOW — an AI job search service

My own project. FastAPI and PostgreSQL with an LLM behind it: it reads a CV, scores vacancies pulled from hh.ru against it, and drafts the cover letter for the ones worth applying to.

Alongside these: an e-commerce storefront and admin panel on Next.js, Telegram bots for shift tracking, reporting and alerting, competitor price monitoring, and a number of Google Sheets and Excel automations that quietly gave people back a few hours a week.

---

## How I work

Python and PostgreSQL are where I'm most fluent: pandas, Selenium, psycopg2, requests, FastAPI, plus the Google Sheets and Telegram Bot APIs. On the web, TypeScript with Next.js and React. For LLM work, the OpenAI and Anthropic APIs — function calling, structured output, prompt caching, token cost accounting and agent orchestration. Infrastructure day to day: Git, Linux, SSH, Docker, my own VPS.

I use Claude Code, Cursor and ChatGPT while building, and I also ship LLM features as products. The distinction matters to me: an assistant speeds up the typing, it doesn't choose the architecture and it doesn't excuse me from understanding what shipped.

## Where I am

Fourth-year Product Management student at IThub College, which is a useful second lens: most of my work starts as a business problem rather than a ticket. My English is a work in progress — I read it comfortably, speaking it is the part I'm still building.

I'm looking for Business Automation, Data Automation or AI Integration work, ideally somewhere I own a whole loop rather than isolated tasks.

## Contact

[asto-portfolio.ru](https://asto-portfolio.ru) · [Telegram](https://t.me/artemiistorozhevskikh) · [LinkedIn](https://www.linkedin.com/in/artemii-storozhevskikh/) · astorozhevskikh@gmail.com
