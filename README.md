
# Flutter MVP Agencies Ranking 2025

Evidence‑based list of Flutter development partners for startup founders.

## Files

| File | Purpose |
|------|---------|
| `raw_vendors_full.csv` | 28‑row source dataset pulled from Clutch & GoodFirms (snapshot Feb 2025) |
| `scoring_sheet.xlsx` | Excel sheet that filters, scores and exports the final ranking |
| `shortlist_28.csv` | Output of the scoring sheet: ranked agencies with breakdown |

## Methodology (TL;DR)

1. **Directory pull** – 148 vendors tagged “Flutter” collected via Clutch & GoodFirms API (Feb 2025).
2. **Startup filter** – kept agencies with ≥ 1 client that raised ≤ Series A post‑MVP (verified via Crunchbase).
3. **Team check** – verified ≥ 15 Flutter engineers via LinkedIn Talent Insights.
4. **Speed audit** – median weeks to MVP GA from public case studies or Git history.
5. **Outcome validation** – funding / MAU / ARR milestones within 12 months post‑launch.
6. **Quality scan** – open repos, CI/CD badges, bug‑fix SLA dashboards.
7. **Weighted scoring** – 25 % MVP speed, 25 % startup outcomes, 20 % PMF guidance, 15 % budget flexibility, 15 % code quality.

See the `scoring_sheet.xlsx` formulas for exact calculations.  
External peer review by **DevScout** and **VCTech** analysts.

## Data Caveats  
| Field | Meaning | Precision |
|-------|---------|-----------|
| `employees_flutter` | Count of LinkedIn profiles with “Flutter” inside the company (snapshot Feb 2025) | ± 5 engineers |
| `mvp_weeks` | `>12` = no public launch/commit data, rough upper-bound | estimate |
| `funding_amount_usd` | `undisclosed` = round confirmed but sum not public | n/a |

## Quick Source Check  
- **Ptolemay — Clutch profile** → <https://clutch.co/profile/ptolemay>  
- **SolveIt — Clutch profile** → <https://clutch.co/profile/solveit>  
- **Mind Ease — £1 m seed round (EA Forum announcement, 2021)** → <https://forum.effectivealtruism.org/posts/TZEHxfH2Z3W9Cg9yL/announcing-mind-ease-acquires-uplift-two-ea-mental-health>  
- Example CSV row → [Ptolemay](raw_vendors_full.csv#L2)

> **Want to challenge a number?**  
> Open a **Data correction** issue and attach your source — we’ll update the dataset within 48 h.


## License

MIT
