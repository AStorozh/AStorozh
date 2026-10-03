<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AStorozh/AStorozh/output/github-snake.svg">
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/AStorozh/AStorozh/output/github-snake.svg">
</picture>

</div>

# Artemii Storozhevskikh

**Business Automation & AI Integration Engineer**

I build the unglamorous systems that take manual work out of a business: scheduled data collection, ETL into Postgres, reports that assemble themselves, bots that speak up when something breaks.

Most of my projects start the same way. Someone is copying numbers between a marketplace dashboard, a spreadsheet and a chat, by hand, every morning. I replace that loop with something that runs on a schedule and reports its own failures.

---

## Selected work

**Marketplace analytics pipeline.**
Scheduled collection of every seller report from a Wildberries account into PostgreSQL, then out to Google Sheets as finished pivot tables. Runs unattended. The orchestration is multiprocess, so one scraper hitting a wall doesn't take down the rest of the run.

**Error collection for that pipeline.**
Once it ran unattended, I needed it to tell me when it broke. I wrote a layer that overrides `builtins.print` and the system `excepthook`, normalizes any traceback into one short readable line, and writes it to a shared Postgres table. A Telegram bot watches the table and pushes each new row to subscribers in real time. Small piece of code, but it changed how fast I could debug everything else.

**AI replies to customer reviews.**
Claude Haiku 4.5 answers complaints; templates handle the straightforward positive ones. Structured JSON output, prompt caching and token accounting keep the cost per review predictable. Anything ambiguous is deliberately *not* sent, it's parked for a human. Working out what the model should refuse to do turned out to be the real design problem, not the prompting.

**HIREFLOW, an AI job search service.**
My own project. FastAPI and PostgreSQL with an LLM behind it: it reads a CV, scores vacancies pulled from hh.ru against it, and drafts the cover letter for the ones worth applying to.

**My portfolio site, [asto-portfolio.ru](https://asto-portfolio.ru).**
Also mine end to end. Next.js 16 and React 19 over Postgres with Drizzle. Its own CMS admin, a voice-capable AI assistant on the OpenAI Realtime API that answers questions about my experience, and self-hosted analytics with per-link campaign tracking, which means no third-party scripts and no cookie banner. Three languages.

Alongside these: Telegram bots for shift tracking and report delivery, competitor price collection, and a handful of Google Sheets and Excel automations that quietly saved people a few hours a week.

---

## Tools

Python and PostgreSQL are where I'm most fluent: pandas, Selenium, psycopg2, requests, plus the Google Sheets and Telegram Bot APIs. On the web, TypeScript with Next.js and React. For LLM work, the OpenAI and Anthropic APIs, with function calling, structured output, prompt caching and token cost accounting. Day to day: Git, Linux, SSH, Docker.

## AI in my workflow

I use Claude Code, Cursor and ChatGPT while building, and I also ship LLM features as products. The distinction matters to me: an assistant speeds up the typing, it doesn't choose the architecture and it doesn't excuse me from understanding what shipped.

## Where I am

Fourth-year Product Management student at IThub College. About a year of automation and data work for a trading company, and roughly eighteen months of freelance before that. My English is a work in progress: I read it comfortably, speaking it is the part I'm still building.

I'm looking for Business Automation or Data Automation work, ideally somewhere I own a whole loop rather than isolated tickets.

## Contact

[asto-portfolio.ru](https://asto-portfolio.ru) · [Telegram](https://t.me/artemiistorozhevskikh) · [LinkedIn](https://www.linkedin.com/in/artemii-storozhevskikh/) · astorozhevskikh@gmail.com
