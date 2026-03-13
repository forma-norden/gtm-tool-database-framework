# tool-taxonomy-normalizer

Use this skill to normalize raw GTM tool lists into a single taxonomy.

## Required Inputs

- raw dataset paths from `data/raw/`
- target motion (outbound, ABM, PLG, hybrid)
- stage context
- hard constraints (budget, compliance, team capacity)

## Canonical Taxonomy

Required top-level categories:

1. list building and discovery
2. email verification
3. enrichment and waterfall
4. signal and intent
5. sequencing and engagement
6. linkedin execution
7. AI and research
8. CRM and pipeline
9. workflow automation
10. call and meeting intelligence
11. content operations
12. AI support agents
13. web and landing infrastructure

## Execution Sequence

1. Ingest raw CSV rows.
2. Normalize vendor names and remove URL-only prefixes.
3. Map each row to canonical category and capability tag.
4. Tag stage fit (`seed`, `series-a`, `series-b-plus`, `enterprise`).
5. Flag unsupported or out-of-scope tools.
6. Export normalized table with quality notes.

## Output Contract

Return:

- normalized_tool_table
- duplicates_removed list
- unmapped_or_conflicted rows
- category_coverage summary

## Failure Conditions

- same vendor split across multiple aliases
- missing stage-fit tags
- no unmapped row handling

