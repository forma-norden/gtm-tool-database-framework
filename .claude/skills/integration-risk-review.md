# integration-risk-review

Use this skill to audit risk before adopting or replacing GTM tools.

## Required Inputs

- proposed stack
- existing stack
- integration points
- write-path systems (CRM, sequencer, warehouse)

## Risk Dimensions

- data integrity risk
- API dependency risk
- vendor lock-in risk
- operational fragility risk
- migration complexity risk

## Execution Sequence

1. Map all data paths and write responsibilities.
2. Identify single points of failure.
3. Score each risk dimension.
4. Define mitigation controls and rollback paths.
5. Set approval threshold for go-live.

## Output Contract

Return:

- risk_register
- severity score per risk
- mitigation_plan
- rollback_plan
- go_live_decision

## Failure Conditions

- no rollback path for write systems
- unknown field ownership in CRM writes
- migration approved without risk controls

