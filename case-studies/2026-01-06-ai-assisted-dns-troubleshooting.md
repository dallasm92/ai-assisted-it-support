# Case Study: AI-Assisted DNS Troubleshooting (Pi-hole + Browser DoH)

## Scenario
User reported intermittent failures loading major sites. Initial assumption was DNS filtering failure.

## User Impact
- Access to key web services was unreliable.
- Repeated failures created workflow disruption.

## Business Impact
- Higher support time due to intermittent and misleading symptoms.
- Delayed restoration because root cause was not obvious.

## AI-Assisted Role
AI was used to:
- propose likely causes in ranked order
- suggest low-risk tests to isolate resolver path issues
- structure validation and closeout notes

## Human Validation Steps
- Verified client resolver with command-line checks.
- Compared browser behavior with and without DoH.
- Confirmed Pi-hole query visibility during testing.

## Root Cause
- Client DNS path bypassed intended resolver behavior.
- Browser DNS-over-HTTPS settings conflicted with system DNS expectations.

## Resolution
- Corrected client DNS path.
- Standardized browser DNS behavior for this environment.
- Re-validated service access and resolver logs.

## Outcome
- Stable access restored.
- Repeatable troubleshooting sequence documented.

## Interview Angle
This case shows layered troubleshooting: network resolver path + application/browser behavior + evidence-based validation.
