# Dan Hahn

**Product lead for applied AI.** I build AI systems that take the manual work out of how teams run, then hand the tools to the people who do the job and teach them to use them. Portland, Oregon.

[LinkedIn](https://www.linkedin.com/in/dan-hahn-b521a25) · [Astrolabe](https://aportlandcareer.com/astrolabe) · [A Portland Career](https://aportlandcareer.com) · dan@aportlandcareer.com

Most of my work lives in private repositories, because it runs working businesses and holds client data. Here's what's in them, and what you can open below.

## What I'm building

**[Astrolabe](https://aportlandcareer.com/astrolabe)**, an AI workspace where you stay in the driver's seat. You work with an agent that remembers your notes and projects and builds the tools you ask for, your notes become a globe you can walk around, and everything stays as plain files on your own computer. I lead the product with my engineering partner, Danny Bauman.

- We shipped releases on 75 days in 13 weeks, about 2,970 commits.
- About 15 people outside our team use it, most of them daily.
- We agreed on a success measure before we built onboarding (new users get past three drop-off points on their own), built two versions in parallel and merged the best.
- I baselined and overhauled performance: a key data call went from 7 seconds to 0.36, and browser memory growth from 84 MB to 3 MB, with a regression gate before every release.

**The systems behind [A Portland Career](https://aportlandcareer.com)**, a career coaching firm with 10 coaches and more than 800 clients served, which ran entirely by hand a year ago.

- A custom CRM, client portal and intake system, built with AI coding agents. AI drafts the handoffs and plans, and a person reviews every draft before anyone uses it.
- Billing and coach pay went from about a day of spreadsheet work to a few minutes, over three rounds of automation (Google Apps Script, the CRM linked to QuickBooks, then an AI agent).
- A client matching system built around Career Constellation, a computer-adaptive career assessment (Item Response Theory, 405 questions on 45 motivators).
- I tested the matching engine blind against three outside AI models, scored against a coach's ratings. The models won (0.65 to 0.69 against 0.46), so I redesigned how it ranks.
- I rolled each tool out one coach at a time, then to the whole team.

**[Decision Art](https://decisionart.app)**, the companion app and course platform for *Art & Mind*, a book on decision making I co-wrote. A professor's first call became a 42-item plan the same day, and 39 features shipped in nine days for a live term.

## How I build

I plan in product requirement documents and build with AI coding agents (Claude Code, Codex). An outside model (ChatGPT or Gemini) critiques every plan before we build. Then an orchestrator agent and a developer agent work side by side, and each step ends with a written closeout the next step starts from. I've finished 30 of 59 build plans in the past year, with 12 more over 90% done.

## Public work you can open

- **[groundstation](https://github.com/bookbran/groundstation)**: Earth data, agent-ready. An MCP server, a Claude skill and Earth briefings over the cloud-native geospatial stack (STAC, TiTiler).
- **[living-worlds](https://github.com/bookbran/living-worlds)**: walk-in 3D worlds of real places, built from open Earth data.
- **[smart-connections-mcp](https://github.com/bookbran/smart-connections-mcp)**: semantic search and a knowledge graph over Obsidian notes, as an MCP server an agent can use.
- **[magic-broom-chat](https://github.com/bookbran/magic-broom-chat)**: the chat app students in our AI course built and used together.
- **[apc-journeys-data](https://github.com/bookbran/apc-journeys-data)**: the coaching journey data our intake guide, intake system and CRM all read from.

## Teaching

I co-led two cohorts of adults, mostly non-developers, through building and shipping their own software with AI. Every student in our second cohort shipped a working project. One automated his firm's admin with five agents and went from 43 completed tasks a month to 183 with the same staff.

Before this, I was a partner at Mastering Decisions Group, where I set the roadmap for three software teams building real-time group decision software, and I founded Solar Power Rocks, which I sold in 2018. M.S., Industrial and Organizational Psychology, Portland State University.
