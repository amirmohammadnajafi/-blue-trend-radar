# BLUE Engineering — Mini Trend Radar (Rail)

R&D Intern take-home: a mini Trend Radar for the **rail** sector (6 trends, 5–10 year horizon), with one recommended R&D project (T2: AI-driven bogie digital twin).

## Contents

- `writeup/writeup.tex` — LaTeX source of the 2-page write-up (template: `11pt/a4paper`, 2.5 cm margins)
- `writeup/writeup.pdf` — compiled PDF (must match the source; compile with Overleaf or TeX Live)
- `data/trends.json` — the 6 trends: description, TRL + justification, core/adjacent/transformative category, key sources (URL + year), horizon; `recommended: true` marks T2
- `dashboard/index.html` — offline single-file dashboard (radar chart, trend table, recommended-project panel); data embedded mirrors `data/trends.json`

## How to open / run

1. Dashboard: double-click `dashboard/index.html` (no server, no install, works offline). Click a dot for trend details.
2. Write-up: upload `writeup/writeup.tex` to Overleaf → Recompile (twice, for references) → download `writeup.pdf`.
3. Data file: any JSON reader; `trend_count: 6`, `recommendation: "T2"`.

## Notes and assumptions

- TRLs are author assessments per EC Horizon Europe FAQ 2890 and EURAXESS hardware scale (papers rarely state TRL).
- Turnover figures (~EUR 18.7M, 2025) are from public Italian business registries, unconfirmed by BLUE.
- Kaggle/HuggingFace items are prototyping aids for the dashboard demo, not TRL evidence.
