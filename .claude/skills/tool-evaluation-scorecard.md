# tool-evaluation-scorecard

Use this skill to score GTM tools against operational requirements.

## Required Inputs

- shortlist candidates
- use case definition
- weighted criteria model
- constraints: budget, compliance, implementation window

## Default Criteria Model

- data quality and reliability
- integration and API fit
- operational complexity
- delivery speed to value
- total cost of ownership
- vendor risk and roadmap confidence

## Execution Sequence

1. Confirm criteria weights add to 100.
2. Score each candidate 1 to 5 per criterion.
3. Compute weighted final score.
4. Add confidence modifier if source evidence is weak.
5. Generate ranked output plus sensitivity check.

## Output Contract

Return:

- scored_table with weighted totals
- ranking
- confidence flags
- disqualifications
- tie-break rule recommendation

## Failure Conditions

- criteria missing weights
- pricing ignored in score
- no confidence or evidence quality handling

