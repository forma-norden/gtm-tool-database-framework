# Test: tool-taxonomy-normalizer

Load skill: `.claude/skills/tool-taxonomy-normalizer.md`

## Prompt

```text
Read .claude/skills/tool-taxonomy-normalizer.md

Inputs:
- dataset path: data/raw/
- motion: outbound + revops
- stage: series-a
- constraints: budget medium, no enterprise lock-in in first year

Return normalized table, duplicate handling, and category coverage summary.
```

## Must Pass Checklist

- [ ] Maps tools to canonical 13-category taxonomy
- [ ] Handles duplicate vendor names cleanly
- [ ] Adds stage-fit tags
- [ ] Flags unmapped rows
- [ ] Outputs category coverage summary

## Failure Indicators

- duplicate vendors unresolved
- category mapping missing
- no handling for unmapped entries

