# Data Guide

This folder contains the Wave 2 GTM tool dataset adapted from the Conigma source.

## Structure

- `raw/` — original category-level CSV files (one per category, no `_all` duplicates)

## Included Categories

1. List Building and Lead Discovery
2. Email Verification Tools
3. Data Enrichment and Waterfall Tools
4. Signal and Intent Detection Tools
5. Cold Email Sequencers
6. LinkedIn Automation and Outreach
7. AI and Research Tools for GTM
8. CRM and Pipeline Management
9. Workflow Automation and Orchestration
10. Call, Meeting, and Revenue Intelligence
11. Content Creation and Design Tools
12. AI Sales and Support Agents
13. Website and Landing Page Builders

## Update Protocol

1. Refresh source files from the Conigma folder.
2. Replace matching CSV files in `raw/`.
3. Run `tool-taxonomy-normalizer` on updated rows.
4. Log notable changes in `CHANGELOG.md`.

## Data Quality Notes

- Treat source verdicts as directional, not final truth.
- Re-validate pricing, limits, and feature claims before production decisions.
- Keep source-to-row traceability when creating normalized outputs.

