# Test: stack-lifecycle-review

Load skill: `.claude/skills/stack-lifecycle-review.md`

## Prompt

```text
Read .claude/skills/stack-lifecycle-review.md

Inputs:
- active stack: HubSpot, Clay, Smartlead, n8n, Albacross
- monthly cost baseline: 8200 USD
- last quarter incidents: 5 integration failures in enrichment and routing
- usage report: two tools under 20% utilization

Return status matrix, cost-vs-value summary, and next-quarter action plan.
```

## Must Pass Checklist

- [ ] Classifies each tool as retain/optimize/replace/sunset
- [ ] Includes cost-vs-value analysis
- [ ] Identifies replace or sunset candidates
- [ ] Includes owner and due date per action
- [ ] Includes migration step for replacement actions

## Failure Indicators

- no classification per tool
- no owner assignment
- replacement suggestion with no migration path

