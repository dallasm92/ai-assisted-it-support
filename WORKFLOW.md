# Workflow: AI-Assisted Incident Handling

## 1) Intake and Framing
Capture:
- What is broken?
- Who is impacted?
- How urgent is it?
- What changed recently?

Output:
- Initial incident statement with impact and priority

## 2) Evidence Collection
Gather facts before asking AI for recommendations:
- Error messages
- Relevant logs
- Basic system/network status checks
- Current configuration snapshots

Output:
- Verified fact set

## 3) AI-Assisted Hypothesis Generation
Use AI to produce:
- Top likely root causes
- Ordered test plan (low risk first)
- Validation criteria for each test

Output:
- Test plan with expected outcomes

## 4) Execute and Validate
Run tests sequentially:
- Record command + output
- Eliminate or confirm each hypothesis
- Apply minimal viable fix

Output:
- Confirmed root cause and implemented fix

## 5) Post-Fix Verification
Validate from both technical and user perspectives:
- Service status healthy
- Error condition resolved
- User workflow restored

Output:
- Closure readiness confirmation

## 6) Documentation and Prevention
Write structured closeout:
- Root cause
- Corrective action
- Validation evidence
- Prevention improvements

Output:
- Reusable case study / ticket notes

## Quality Gates
- No high-risk changes without explicit review
- No closure without validation evidence
- No public artifacts with sensitive data
