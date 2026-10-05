# Leads Board · لوحة متابعة عملاء العقار

In real estate the deal is usually lost in the follow-up, not in the first call. A client asks about a villa, we promise to call back with options, and a week later nobody remembers who was supposed to call.

This board is my answer to that: every client is a card, every card moves from **New** to **Won** (or Lost), and anything with a follow-up due today turns orange — overdue turns red.

**Try it:** https://noorsl.github.io/real-estate-leads/

![Leads Board](docs/screenshot.png)

## Features

- **Kanban pipeline** – New → Contacted → Viewing → Negotiation → Won / Lost
- **Drag and drop** leads between stages (or use ← → keys, or change the stage in the lead form on mobile)
- **Lead card** – client, budget in SAR, property type, buy/rent, city and district, source, agent, *Hot* flag
- **Follow-ups** – next follow-up date on each lead; *Today* and *overdue* are highlighted, plus a “Next follow-ups” list
- **Business KPIs** – open leads, pipeline value, won value, win rate, average days to close
- **Where leads come from** – leads per source with won / active / lost split and win rate
- **Search and filters** – by agent, property type, source, or only leads with a due follow-up
- **Activity history** for every lead · **Export CSV** · **Reset demo data**

## Run it

Open the [live demo](https://noorsl.github.io/real-estate-leads/) or download `index.html` and open it.
Clients, phone numbers and deals in the demo are made up. Data is saved only in your browser (`localStorage`).

## Tech

HTML · CSS · Vanilla JavaScript · HTML5 Drag and Drop · localStorage

## Roadmap

- WhatsApp message templates for follow-ups
- Shared team board with a backend and sign-in
- Import leads from a CSV or a website form

— Bothynah Alsnany · MIT License
