# AI Usage Policy (IT Support)

## Objective
Use AI to improve support speed and clarity while maintaining human accountability, security, and validation quality.

## Allowed Use
- Drafting troubleshooting hypotheses
- Building test plans and command checklists
- Drafting ticket notes and post-incident summaries
- Organizing root-cause analysis and prevention actions

## Required Validation
Before implementing AI-generated advice:
- Confirm environment details (OS, role, network, service versions)
- Run direct checks (logs, status commands, connectivity tests)
- Validate fix in a controlled/low-risk sequence
- Confirm user/service outcome after change

## Not Allowed
- Blind execution of high-risk or destructive commands
- Sharing credentials/tokens/private keys with AI tools
- Publishing internal identifiers or sensitive data in public docs
- Treating AI output as authoritative without verification

## Security Requirements
- Redact sensitive data in prompts and evidence
- Use least privilege for all changes
- Keep audit trail of commands/actions taken
- Prefer reversible changes when possible

## Documentation Standard
Every incident summary should include:
- Issue
- User and business impact
- Environment
- Troubleshooting steps
- Resolution
- Validation
- Prevention notes

## Accountability
Human operator remains responsible for:
- Change approval
- Execution order
- Risk decisions
- Final validation and communication
