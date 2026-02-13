# Troubleshooting Prompts

## A) Root-Cause Candidate Builder
You are helping with IT support triage.
Issue: <describe symptom>
Environment: <OS, role, network, service versions>
Recent changes: <what changed>

Give me:
1) Top 5 likely root causes (ranked)
2) Low-risk tests to confirm/refute each cause
3) Expected outputs for each test
4) Decision tree for next action based on results

## B) Safe Change Plan
Given this issue and confirmed findings:
<findings>

Create a low-risk remediation plan with:
- pre-checks
- exact execution order
- verification checks
- rollback steps

## C) Communication Draft
Draft a user-facing update for this incident:
- what happened
- what was affected
- what was done
- current status
- prevention/next steps
Keep it concise and non-technical.
