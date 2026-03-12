# CLAUDE.md - gtm-tool-database-framework

This repo defines the evaluation framework for selecting and maintaining GTM
tools as a system, not as disconnected point solutions.

## Skills in This Repo

| Skill | When to use it |
|-------|---------------|
| `tool-taxonomy-normalizer` | mapping raw tool lists into a canonical GTM capability taxonomy |
| `tool-evaluation-scorecard` | scoring tools by stage-fit, risk, integration, and cost |
| `stack-design-by-stage` | assembling recommended stacks by company stage and motion |
| `integration-risk-review` | identifying interoperability, lock-in, and data-integrity risk |
| `shortlist-decision-brief` | producing decision memos and pilot plans for final selection |
| `stack-lifecycle-review` | running quarterly retain, replace, and consolidation reviews |

## Output Rule

Every output must include:

- explicit criteria and weights
- ranked options with rationale
- risk and mitigation section
- execution recommendation with owner and timeline

## Testing Rule

Run tests from the `tests/` folder before production use.

