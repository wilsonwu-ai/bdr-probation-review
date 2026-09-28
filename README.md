# BDR 3-Month Probation Review

Interactive scoring tool for a new business development rep's 3-month probation review. Companion to the [BDR Annual Performance Review](https://wilsonwu-ai.github.io/bdr-performance-review/).

**Live:** https://wilsonwu-ai.github.io/bdr-probation-review/

## How it scores

100 points across four pillars, each metric scored from evidence inside the probation window:

| Pillar | Points | What it measures |
|---|---|---|
| Activity and Pipeline Build | 35 | Demos completed, recorded client conversations, deals logged, first wins |
| Call Quality and Sales Craft | 30 | Good / Base / Bad call mix, Cold Call Scorecard, Sales Development Framework, product and pricing knowledge |
| Process, Integrity and CRM | 20 | Pricing authority, recording discipline, CRM hygiene, follow-through |
| Coachability and Trajectory | 15 | Month 1 to month 3 trend, applies coaching, reliability and team fit |

Recommended outcome: 80+ Confirm, 65 to 79 Confirm with a development plan, 50 to 64 Extend 30 days, under 50 Do not confirm.
A Pricing Authority score of 0, or any pillar under 40% of its points, caps the outcome at Extend 30 days.
The outcome only appears once every metric is scored. The manager records the final decision separately.

## Using it

- Everything stays in your browser. The review autosaves to local storage on this device only.
- **Save Review File** downloads a `.json` copy; **Open Review File** loads one back. Use this to keep one file per BD.
- **Export as PDF** opens the print dialog; choose "Save as PDF". The print layout shows every selected answer and note in full, with signature lines.
- **Clear All** wipes the form and the local copy.

Single static `index.html`, no build step, served by GitHub Pages.
