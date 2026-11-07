# Hey y'all, I'm Ben

**Lead Product Manager, Enterprise Systems & Data** at [Backcountry](https://www.backcountry.com). Based in Austin, TX.

I work on the cutting edge of internal tools and AI. The question I keep coming back to: how does AI become a force multiplier not only for engineers, but for every function in a business? My users range from merchandisers and finance to dropship vendors and the teams at brands we acquire, and most of what I build is about giving them the same leverage engineers get from AI.

## What I'm working on

I own product strategy for the backend of the business: ERP, OMS, PIM, Data, Platform, InfoSec, and internal tools & automation. Two APMs run ERP/OMS, PIM, and internal tools day to day, and I focus on where it all goes next.

A few things I'm proud of:

- **Designed and launched a governed integration platform** that lets employees act on internal systems from the tools they already use: Excel, Python, n8n, web apps, or Claude Code.
- **Designed an internal hosting platform** for the apps business users build with AI, so those tools have a home and InfoSec can see what's running.
- **Shipped an AI incident triage agent with our Platform team**, now used by every engineering team. It restarts apps and blocks attacking IPs on its own, asks before rollbacks, and posts its actions to Slack. Saved over 1,400 incident hours.
- **Designed and shipped a NetSuite MCP server** for that agent, on a dedicated least-privilege role.
- **Made payments routine** with a provider-agnostic layer that took each new payment method from about two months of dev work to about three days.
- **Took dropship from zero to a multi-million dollar channel**, and grew marketplaces from 3 to 7 while cutting onboarding from 2-4 weeks to 3 days.

## How I work

- **Systems first.** Understand the whole system before changing any part of it. In enterprise software, second-order effects usually matter more than first.
- **Abstractions over instances.** A good fix solves one failure; a good abstraction handles the next ten. The first time takes two months so that the next one takes two weeks, and the next one takes two days.
- **Automation-first, client-agnostic.** Whether someone works from Excel, Python, n8n, a web app, or a terminal, they should reach internal systems through the same governed path.
- **Self-serve over service desk.** If a team has to wait on mine to make a change, the better answer is usually letting them make it themselves, safely.
- **Prototype first.** I build a working version of nearly every project, usually with Claude, before engineering builds the real thing.

## Things I build on my own

Most of my personal work lives on [benjaminwyndham.com](https://benjaminwyndham.com). A few highlights:

- **[Fulfillment Tycoon](https://fulfillment-sim.vercel.app/)**: a gamified digital twin of a fulfillment operation. Twelve turns, about 9,000 orders a month, and a realistic pricing model. Python and React.
- **The Eval Gate**: a CI gate for prompt changes. Each PR runs both prompt versions on the same cases several times, and a paired statistical test returns PROMOTE, HOLD, or ROLLBACK with the evidence in a PR comment.
- **Switchback**: a Chrome extension that records a browser workflow once and writes the SOP, one instruction and annotated screenshot per step. Sensitive fields are redacted on your machine. No account, no server.
- **[Tools](https://benjaminwyndham.com/tools)**: working versions of the frameworks I use, including a Value Confidence Calculator, an Experiment Designer for changes you can't A/B test, The Eval Stack for LLM evaluations you can defend, and From Ask to Spec. A written framework asks you to trust the reasoning. A working one lets you argue with it.
- **[Data Analytics Portfolio](https://github.com/bwyndham/Data-Anaytics-Portfolio)** *(2022)*: market basket analysis on 1M+ retail transactions, a FunkSVD candidate generation model, and SARIMA forecasting on FRED retail sales data. Built by hand in Python, before AI coding tools.

**What I reach for:** Python, SQL, BigQuery, FastAPI, React, TypeScript, Postgres, Terraform, Docker, GCP, MCP

## Reading

**Currently reading**

- *The Making of a Manager* by Julie Zhuo
- *Defensive Security Handbook* by Lee Brotherston and Amanda Berlin
- *Threat Modeling: Designing for Security* by Adam Shostack
- *Process Mining* by Wil van der Aalst, which I've been chipping away at for a while

**Recently read**

- *Inventory Optimization* by Nicolas Vandeput
- *Designing Data-Intensive Applications* by Martin Kleppmann
- *Software Architecture in Practice* by Len Bass, Paul Clements, and Rick Kazman
- *Practical Statistics for Data Scientists* by Peter Bruce, Andrew Bruce, and Peter Gedeck
- *The Product Book* by Josh Anon and Carlos Gonzalez de Villaumbrosia

## Say hi

If any of this overlaps with what you're working on, take a look at [benjaminwyndham.com](https://benjaminwyndham.com) or find me on [LinkedIn](https://www.linkedin.com/in/benwyndham/).
