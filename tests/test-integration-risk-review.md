# Test: integration-risk-review

Load skill: `.claude/skills/integration-risk-review.md`

## Prompt

```text
Read .claude/skills/integration-risk-review.md

Inputs:
- proposed stack: Clay, Smartlead, HubSpot, n8n
- existing stack: HubSpot, Apollo
- write systems: HubSpot contact and deal objects
- planned changes: replace Apollo sequencing with Smartlead

Return risk register, mitigations, rollback plan, and go-live decision.
```

## Must Pass Checklist

- [ ] Maps write paths and ownership
- [ ] Scores multiple risk dimensions
- [ ] Includes mitigation plan
- [ ] Includes rollback plan
- [ ] Returns explicit go or no-go

## Failure Indicators

- no rollback step for write systems
- missing data ownership mapping
- decision without mitigation requirements

