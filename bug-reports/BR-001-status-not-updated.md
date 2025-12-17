# BR-001 – Application status not updated after verification

## Summary
Application status remains incorrect after verification approval.

## Environment
- System: Internal application system
- Environment: Test
- Browser: Chrome 120

## Preconditions
- Application submitted
- Application in "Verification" status

## Steps to Reproduce
1. Log in as Verifier
2. Open an application pending verification
3. Approve the verification
4. Return to application list

## Expected Result
Application status changes to "Ready for Evaluation".

## Actual Result
Application remains in "Verification" status.

## Impact
Blocks application progression to the next stage.

## Severity
High

## Priority
High

