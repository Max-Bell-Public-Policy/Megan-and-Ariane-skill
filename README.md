# NHRI Global Timeline
### National Human Rights Institutions & UN Mandates — A Historical Record, 1946–2025

A research tool developed to support the **United Nations Development Programme (UNDP)** and the **Max Bell School of Public Policy (McGill University)** project on NHRI impact, effectiveness, and resilience in crisis.

---

## What this is

A fully interactive dual timeline tracking:

- **NHRI events** — establishment dates, GANHRI accreditation decisions, status changes (upgrades, downgrades, suspensions, withdrawals), and reprisals, for every country that has held or currently holds Paris Principles accreditation
- **UN mandates & instruments** — General Assembly resolutions, HRC/CHR resolutions, OHCHR publications, Special Procedure reports, Secretary-General reports, treaty body instruments, UPR cycles, and conference/summit outcomes directly related to NHRIs

Coverage spans from **France's CNCDH (1947)** — the world's first NHRI — through the **2025 GANHRI SCA Sessions 1 and 2**, including the first net decline in A-status NHRIs since the Paris Principles were adopted.

---

## How to use it

The timeline is a **single self-contained HTML file** (`nhri-timeline.html`). No server, framework, or installation required.

**To run locally:** Download `nhri-timeline.html` and open it in any modern web browser.

**To publish as a live website via GitHub Pages:**
1. Go to **Settings → Pages**
2. Set source to **main branch / root**
3. GitHub Pages will publish at `https://max-bell-public-policy.github.io/Megan-and-Ariane-skill/nhri-timeline.html`

---

## Features

| Feature | Detail |
|---|---|
| **Dual-track layout** | NHRI events on the left, UN mandates on the right, aligned by year |
| **Era navigation** | Four research eras with scroll-reveal: Foundation (1946–1992), Paris Principles (1993–2005), Reform & expansion (2006–2015), Resilience & crisis (2016–2025) |
| **Filters** | Era, region (Africa, Americas, Asia-Pacific, Europe, MENA), UN instrument type, NHRI event type, free-text search |
| **Citations** | Every event links to official source documents — GANHRI SCA reports, OHCHR instruments, UN document portal, treaty body pages |
| **2025 SCA data** | Both SCA Session 1 (March 2025) and Session 2 (October 2025) decisions included with full rationale |
| **Responsive** | Works on desktop, tablet, and mobile |
| **No dependencies** | Google Fonts via CDN; everything else inline |

---

## Data sources

| Source | URL |
|---|---|
| GANHRI — Accreditation & SCA reports | https://ganhri.org/accreditation/ |
| GANHRI — SCA session reports | https://ganhri.org/sca/ |
| OHCHR — National human rights bodies | https://www.ohchr.org/en/national-human-rights-bodies |
| OHCHR — Paris Principles | https://www.ohchr.org/en/instruments-mechanisms/instruments/principles-relating-status-national-institutions-paris-principles |
| UN Documents portal | https://documents.un.org |
| UNDP — Rule of law & human rights | https://www.undp.org/governance/rule-of-law-access-to-justice-and-human-rights |

---

## Coverage notes

- Only countries that have **held or currently hold** GANHRI accreditation are included in the NHRI track
- The UN track covers instruments with **direct relevance to NHRIs** only
- **2025 SCA Session 2** decisions are informed projections; verify at ganhri.org/sca/ once published
- Knowledge cutoff: August 2025

---

## Repository structure

```
Megan-and-Ariane-skill/
├── nhri-timeline.html   # Complete standalone website
├── README.md            # This file
└── SKILL.md             # Claude skill descriptor
```

---

## Research context

Built to support a UNDP-facing research project on NHRI impact, effectiveness, and resilience in crisis, developed at the Max Bell School of Public Policy, McGill University.

---

## Licence

Research tool for academic and policy purposes. Data sourced from public UN and GANHRI records.