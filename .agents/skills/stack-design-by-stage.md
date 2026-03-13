# stack-design-by-stage

Use this skill to design stage-appropriate GTM stacks from normalized options.

## Required Inputs

- company stage
- GTM motion profile
- team size and technical capacity
- budget envelope
- existing systems to preserve

## Design Rules

- start with minimum viable stack, not maximum coverage
- prioritize integration depth over tool count
- avoid overlapping tools for same capability unless transition is planned
- include one primary owner per stack layer

## Execution Sequence

1. Select mandatory layers by stage and motion.
2. Pick primary and backup options per layer.
3. Define integration map and data flow.
4. Flag consolidation opportunities.
5. Produce 30-60-90 day rollout plan.

## Output Contract

Return:

- recommended_stack_table
- layer_ownership map
- integration_map
- rollout_plan_30_60_90
- consolidation_notes

## Failure Conditions

- no owner per layer
- tool overlap without transition path
- rollout plan missing dependency order

