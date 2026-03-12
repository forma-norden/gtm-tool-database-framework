# Test: shortlist-decision-brief

Load skill: `.claude/skills/shortlist-decision-brief.md`

## Prompt

```text
Read .claude/skills/shortlist-decision-brief.md

Inputs:
- top options: n8n, Make
- risk summary: moderate migration risk, low vendor lock-in risk for n8n
- budget cap: 12k/year
- decision deadline: 14 days

Return decision brief and 30-day pilot plan with success and stop criteria.
```

## Must Pass Checklist

- [ ] Includes recommendation and alternatives
- [ ] Includes rejection rationale
- [ ] Includes pilot success metrics
- [ ] Includes explicit stop criteria
- [ ] Assigns owner and review checkpoint

## Failure Indicators

- recommendation with no tradeoff table
- no stop conditions
- no owner assignment

