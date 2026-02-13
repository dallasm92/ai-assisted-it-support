# Case Study: AI-Assisted Windows Network Connectivity Fix

## Scenario
Windows endpoint had inconsistent connectivity to internal resources after configuration changes.

## User Impact
- User could not reliably reach required internal services.
- Normal support and admin tasks were delayed.

## Business Impact
- Increased downtime and support overhead.
- Risk of misdiagnosis due to partial connectivity.

## AI-Assisted Role
AI was used to:
- generate a structured test sequence
- prioritize low-risk diagnostics before configuration changes
- draft concise user-facing and technical summaries

## Human Validation Steps
- Verified interface/IP/DNS state.
- Tested gateway and target reachability.
- Checked host/firewall/profile settings.
- Confirmed post-fix behavior with repeated tests.

## Root Cause
A network configuration mismatch (interface/profile/DNS path) caused inconsistent connectivity.

## Resolution
Applied targeted network configuration corrections and revalidated path continuity.

## Outcome
- Connectivity restored.
- Documentation captured for repeat incidents.

## Interview Angle
Demonstrates disciplined troubleshooting under uncertainty: gather facts first, test hypotheses, apply minimal changes, validate results.
