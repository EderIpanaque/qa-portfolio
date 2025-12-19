# TC-001 – Application status updates successfully after verification approval

## Summary
Application status is updated correctly after verification approval.

## Environment
- System: Internal application system
- Environment: Test
- Browser: Chrome 120

## Preconditions
- Application has been submitted
- Application is in **"Verification"** status

## Steps
1. Log in as Verifier
2. Open an application pending verification
3. Approve the verification
4. Return to the application list

## Expected Result
- Application status changes to **"Ready for Evaluation"**
- Application is available for the next processing stage

## Actual Result
- Application status is updated successfully to **"Ready for Evaluation"**

## Status
Pass ✅
