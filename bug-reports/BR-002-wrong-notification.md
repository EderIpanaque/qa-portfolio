# BR-002 – Wrong Notification Sent to Applicant

## Bug Overview
This bug describes an issue where the system sends an incorrect or missing notification to the applicant after an observation is raised during the evaluation process.

---

## Roles Involved
- Applicant (Postulante)
- Supervisor / Evaluator
- System Notification Service

---

## Expected Notification Flow

### Step 1: Observation Raised
- A Supervisor or Evaluator raises an observation on an application.
- The application status changes to **Observed**.

### Step 2: Notification Trigger
- The system triggers a notification event.
- Notification content is generated based on:
  - Application ID
  - Current status
  - Observation details

### Step 3: Notification Delivery
- The applicant receives a notification:
  - Correct message
  - Correct status
  - Correct stage (Verification / Evaluation / Review)

---

## Actual (Buggy) Flow

### Step 1: Observation Raised
- An observation is raised successfully.
- Application status changes to **Observed**.

### Step 2: Notification Trigger (Incorrect)
- The notification event is triggered.
- The system:
  - Sends a wrong message, **or**
  - Does not send any notification, **or**
  - Sends a notification with an incorrect status or stage.

### Step 3: Applicant Impact
- The applicant:
  - Receives misleading information, or
  - Does not know an observation was raised.

---

## Impact
- Applicant is unaware of required corrections.
- Application remains blocked.
- Increases support requests.
- Affects user experience and process efficiency.

---

## Severity
High

## Priority
High

---

## QA Validation Points
- Verify notification is sent every time an observation is raised.
- Validate notification content matches the current application stage.
- Confirm applicant view matches internal system status.
- Test notification delivery across all stages:
  - Verification
  - Evaluation
  - Review
  - Committee

---

## Conclusion
Incorrect notification handling causes user confusion and process delays. 
This bug highlights the importance of validating notification logic against application status transitions.
