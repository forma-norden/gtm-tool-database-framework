# GTM Tool Database Framework

Framework-plus-data repository for GTM tool selection and lifecycle management.
It adapts the large Conigma tool database into a practical system you can run:
taxonomy normalization, weighted scoring, stack design by stage, risk review,
decision briefs, and quarterly consolidation workflows.

## What's Inside

| File | What it does |
|------|-------------|
| `.claude/skills/tool-taxonomy-normalizer.md` | Converts raw vendor lists into a canonical GTM taxonomy. |
| `.claude/skills/tool-evaluation-scorecard.md` | Scores tools using weighted operational criteria. |
| `.claude/skills/stack-design-by-stage.md` | Designs stage-appropriate stacks with ownership and rollout sequencing. |
| `.claude/skills/integration-risk-review.md` | Evaluates migration and interoperability risk before adoption. |
| `.claude/skills/shortlist-decision-brief.md` | Produces decision memo and pilot plan for final selection. |
| `.claude/skills/stack-lifecycle-review.md` | Runs quarterly retain/replace/sunset reviews to reduce stack sprawl. |
| `data/raw/` | Imported category-level source CSVs from the Wave 2 Conigma database. |
| `data/README.md` | Data coverage, quality notes, and update protocol. |
| `tests/` | Prompt-based tests and validation checklists for all six skills. |

## Prerequisites

- [ ] Current GTM stack inventory
- [ ] Clear stage and motion definition
- [ ] Budget and compliance constraints
- [ ] Access to tool usage and incident data
- [ ] Decision owner for final vendor selection

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/forma-norden/gtm-tool-database-framework.git
   ```
2. Copy `.claude/skills/` into your project:
   ```bash
   cp -r gtm-tool-database-framework/.claude/skills your-project/.claude/
   ```
3. Use `data/raw/` as the source for taxonomy and scorecard workflows.

## Usage

```text
Read .claude/skills/tool-evaluation-scorecard.md

Inputs:
- capability: workflow automation
- candidates: n8n, Make, Zapier
- constraints: self-hosting preferred, budget <= 10k/year
- weights:
  - integration depth: 30
  - operational complexity: 20
  - cost: 20
  - flexibility: 20
  - vendor risk: 10

Return:
1) weighted score table
2) ranked shortlist
3) disqualifications and risks
4) recommendation for pilot
```

Expected output:

- weighted and ranked shortlist
- explicit tradeoffs and risk notes
- pilot-ready recommendation with owner

## Who This Is For

GTM engineers, RevOps leads, VP Sales, and founders at B2B companies with 50 to 500 employees who are building or consolidating their
outbound infrastructure and want to reduce tool sprawl through
better-engineered GTM systems.

---

---

## From the Forma NÃ´rden GTM Library

This is a free resource from the Forma NÃ´rden open-source GTM library, built by 
[Yananai A. Chiwuta](https://yananaichiwuta.com/), GTM engineer and founder of 
[Forma NÃ´rden](https://formanorden.com/).

- [Open-source GTM systems](https://github.com/forma-norden): all repos in the library  
- [GTM engineering blog](https://formanorden.com/blog/): strategy, systems, and outbound deep-dives  
- [All resources](https://formanorden.com/resources/): guides, frameworks, and templates  

If this saves you time, star the repo and follow 
[Forma NÃ´rden on LinkedIn](https://www.linkedin.com/company/formanorden/).

Built by [Forma NÃ´rden](https://formanorden.com/): GTM engineering for B2B companies.
