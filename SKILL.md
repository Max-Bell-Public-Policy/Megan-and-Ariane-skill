---
name: nhri-timeline
description: >
  Use this skill whenever working on research, analysis, policy, or visualisations
  related to national human rights institutions (NHRIs), GANHRI accreditation,
  UN human rights mandates, democratic backsliding and NHRI resilience, or UNDP
  rule-of-law programming. This skill provides a comprehensive dual timeline of
  NHRI accreditation events and UN instruments from 1946 to 2025, including all
  GANHRI SCA session decisions, Paris Principles history, and UN General Assembly,
  HRC, OHCHR, Special Procedure, Secretary-General, treaty body, UPR, and
  conference/summit records directly relevant to NHRIs. Trigger on any mention of:
  NHRIs, Paris Principles, GANHRI, ICC accreditation, OHCHR national human rights
  bodies, democratic backsliding and human rights institutions, NHRI resilience,
  UPR and NHRIs, SDG 16 accountability institutions, or UNDP human rights programming.
license: Research tool — Max Bell School of Public Policy, McGill University / UNDP
---

## What this skill delivers

A **complete interactive dual timeline** covering:

### NHRI track
Every country that has held or currently holds GANHRI accreditation (A, B, or C status):
- Establishment dates and founding legislation
- Initial accreditation decisions
- Upgrades and downgrades with documented rationale
- Suspensions and status reviews (conflict, coups, reprisals)
- Full withdrawals: Russia 2024, Nicaragua 2021, Afghanistan 2023, Myanmar/Sudan/Burkina Faso 2025
- 2025 SCA Session 1 (March) and Session 2 (October) decisions

### UN track
All instruments with direct relevance to NHRIs:
- **GA resolutions** from Res. 33/46 (1978) through Pact for the Future (2024) and 2025 SR proposal
- **HRC/CHR resolutions** on NHRI independence, civic space, conflict access, democratic backsliding
- **OHCHR** publications, handbooks, thematic reports, and 2025 OHCHR–UNDP resilience report
- **Special Procedures** — SR on HRDs, SR on torture/NPMs, SR on democracy, SR on civic space
- **Secretary-General** annual reports (A/55/283 through A/80/261)
- **Treaty bodies** — ICCPR, ICESCR, CEDAW, CAT, OPCAT, CRC and relevant General Comments
- **UPR** cycles 1–4 with NHRI engagement milestones
- **Conferences/Summits** — Paris 1991, Vienna 1993, World Summit 2005, SDGs 2015, Summit of the Future 2024

---

## How to use

Single self-contained HTML file — open in any browser. No installation required.

**GitHub Pages:** Go to Settings → Pages → Source: main branch / root to publish as a live website.

## Filters

| Filter | Options |
|---|---|
| Era | Foundation / Paris Principles / Reform & expansion / Resilience & crisis |
| Region | Africa / Americas / Asia-Pacific / Europe / MENA |
| UN type | GA / HRC / OHCHR / SP / SC / TRT / UPR / CONF |
| NHRI event | EST / A / B / C / UPG / DWG / SUS / W |
| Free text | Search by country, institution, document title, or reference |

---

## Data schema

### NHRI event
```js
{
  y: 2025,                    // year
  country: "Sri Lanka",       // country name
  inst: "HRCSL",              // institution abbreviation
  region: "Asia-Pacific",     // Africa | Americas | Asia-Pacific | Europe | MENA
  type: "UPG",                // EST | A | B | C | UPG | DWG | SUS | W
  status: "A",                // A | B | C | W
  is2025: true,               // marks 2025 SCA decisions (optional)
  note: "Upgraded B to A...", // full note with rationale
  links: [{ l: "Label", u: "https://..." }]
}
```

### UN instrument
```js
{
  y: 1993,
  type: "GA",                 // GA | HRC | OHCHR | SP | SC | TRT | UPR | CONF
  title: "Paris Principles formally adopted",
  ref: "GA Res. 48/134, 20 Dec 1993",
  note: "Constitutional document of the global NHRI system...",
  links: [{ l: "Label", u: "https://..." }]
}
```

---

## Primary sources

| Source | URL |
|---|---|
| GANHRI accreditation | https://ganhri.org/accreditation/ |
| GANHRI SCA reports | https://ganhri.org/sca/ |
| OHCHR NHRIs | https://www.ohchr.org/en/national-human-rights-bodies |
| Paris Principles | https://www.ohchr.org/en/instruments-mechanisms/instruments/principles-relating-status-national-institutions-paris-principles |
| UN Documents | https://documents.un.org |
| UNDP rule of law | https://www.undp.org/governance/rule-of-law-access-to-justice-and-human-rights |

---

## Coverage notes

- Only countries with GANHRI accreditation history included in NHRI track
- 2025 SCA Session 2 decisions are informed projections; verify at ganhri.org/sca/
- Knowledge cutoff: August 2025
- Research context: UNDP / Max Bell School of Public Policy, McGill University