# Ecosystem: gtm-tool-database-framework

How this repo connects to the rest of the Forma Norden GTM library.

## Works With

| Repo | Relationship | When to use together |
|------|-------------|---------------------|
| `claude-code-gtm-operator-workflow` | Parallel | Operator patterns used during tool evaluation |
| `n8n-gtm-workflow-pack` | Downstream | Tool decisions determine which n8n integrations to build |
| `clay-claude-code-skill-pack` | Downstream | Clay evaluated as part of enrichment stack design |

## Suggested Skill Chains

1. Stack audit: taxonomy > scorecard > integration-risk > shortlist > lifecycle
