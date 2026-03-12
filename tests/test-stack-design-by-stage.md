# Test: stack-design-by-stage

Load skill: `.claude/skills/stack-design-by-stage.md`

## Prompt

```text
Read .claude/skills/stack-design-by-stage.md

Inputs:
- stage: series-a
- motion: signal-based outbound
- team: 1 GTM engineer, 2 SDRs, 1 AE
- budget: 9k/month
- existing systems: HubSpot, Clay

Return recommended stack, ownership map, integration map, and 30-60-90 plan.
```

## Must Pass Checklist

- [ ] Defines mandatory layers for stage and motion
- [ ] Avoids unnecessary overlap between tools
- [ ] Assigns an owner per layer
- [ ] Includes integration map
- [ ] Includes 30-60-90 rollout order

## Failure Indicators

- no ownership mapping
- overlapping tools with no transition logic
- missing rollout sequencing

