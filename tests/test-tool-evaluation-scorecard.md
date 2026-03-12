# Test: tool-evaluation-scorecard

Load skill: `.claude/skills/tool-evaluation-scorecard.md`

## Prompt

```text
Read .claude/skills/tool-evaluation-scorecard.md

Inputs:
- capability: cold email sequencing
- candidates: Instantly, Smartlead, Lemlist
- weights:
  - deliverability reliability: 30
  - integration fit: 25
  - operational complexity: 15
  - cost: 20
  - vendor risk: 10

Return weighted scorecard, ranking, and disqualification notes.
```

## Must Pass Checklist

- [ ] Uses weighted scoring totaling 100
- [ ] Scores each candidate across all criteria
- [ ] Produces ranked list
- [ ] Includes confidence or evidence quality note
- [ ] Includes disqualification logic

## Failure Indicators

- missing criteria scores
- no weighted totals
- no confidence handling

