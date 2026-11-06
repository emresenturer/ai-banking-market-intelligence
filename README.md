# AI Banking Market Intelligence

## Live tool

**Try it:** https://emresenturer.github.io/ai-banking-market-intelligence/

A working version of this case study, in a single `index.html`:

1. Paste banking news items, article text or notes (one item per paragraph), or click **Load sample items** (fictional companies).
2. Pick the audience (CEO, Strategy, Product or Risk), the period, and optionally your institution or focus.
3. Add your own Anthropic API key and click **Generate briefing**. No key yet? Click **See example briefing**.
4. Get an executive briefing: top developments, regulatory, fintech and competitors, trends, implications, recommended actions and a watchlist, each point cited to the item numbers it came from.
5. **Copy Markdown**, **Download .md**, or **Print / PDF** (print stylesheet included).

It only summarizes what you paste. It does not browse the web, open links, or check facts.

- **Run locally:** `python3 -m http.server 8000`, then open http://localhost:8000/.
- **Privacy:** your key stays in this browser (localStorage) and is sent only to api.anthropic.com with your pasted text. There is no server.
- **Stack:** plain HTML, CSS and JavaScript, Anthropic Messages API called from the browser. The system prompt builds on [prompts.md](prompts.md).

---

## Overview
This project demonstrates how AI can automate market intelligence
for the banking industry by collecting, analyzing, and summarizing
industry developments.

The system transforms raw news and reports into executive-level insights.

---

## Problem

Market intelligence teams spend significant time manually tracking
industry developments and summarizing trends. This process is slow
and difficult to scale.

---

## Solution

This AI workflow automatically:

• Collects industry news
• Identifies key developments
• Summarizes articles
• Generates executive briefings
• Detects emerging trends

---

## Workflow

1. Collect banking news and reports
2. Feed information into AI analysis pipeline
3. Extract key insights
4. Generate executive summary
5. Store insights in a structured dashboard

---

## Tools Used

Claude
ChatGPT
Notion
Python

---

## Example Output

Weekly AI-generated banking industry briefing including:

• Major bank announcements
• Regulatory developments
• Fintech trends
• Strategic insights

---

## Business Impact

Reduces manual research time by up to 80% while providing
consistent market intelligence updates.
