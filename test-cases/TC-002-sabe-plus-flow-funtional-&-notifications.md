# TC-002 sabe plus flow funtional & notifications

## Overview
This document describes the application status flow of the SABE+ system, including the different roles involved and the transitions between each process stage.

The objective of this flow is to ensure proper validation, evaluation, and approval of applications through multiple control stages.

---

## Roles Involved
- **Applicant (Postulante):** Submits the application and receives notifications.
- **Supervisor:** Reviews applications and initiates observations.
- **Verifier (Verificador):** Validates documentation and eligibility.
- **Evaluator:** Performs socio-economic evaluation.
- **Reviewer (Revisor):** Reviews final cases before committee decision.
- **Quality Committee:** Makes the final decision.
- **Dispatch:** Issues official documentation.

---

## Application Flow Diagram
![SABE+ Status Flow]
<img width="1250" height="1581" alt="estados-sabe_v1 1" src="https://github.com/user-attachments/assets/c66db1b8-f211-4929-8705-24d460a581fb" />


---

## Flow Description by Stage

### 1. Application Submission
- The applicant submits a new application.
- Initial status: **Sin estado**
- Once submitted, the application moves to **En supervisión**.

---

### 2. Supervision Stage
- The supervisor reviews the application.
- Possible outcomes:
  - Forward to **Verification**
  - Raise an observation (application returns to the applicant)

---

### 3. Verification Stage
- The verifier checks documentation and requirements.
- Possible outcomes:
  - **Observed** → Applicant is notified
  - **Not eligible (No apto)** → Application is rejected
  - **Approved for evaluation** → Moves to Evaluation stage

---

### 4. Evaluation Stage (Socio-economic Evaluation)
- The evaluator performs a detailed assessment.
- Possible outcomes:
  - **Observed** → Applicant is notified
  - **Approved for review** → Moves to Review stage

---

### 5. Review Stage
- The reviewer performs a final review.
- Possible outcomes:
  - **Observed** → Applicant is notified
  - **Approved for Quality Committee**

---

### 6. Quality Committee Stage
- The committee reviews the application.
- Possible outcomes:
  - **Observed** → Observation logged in the system
  - **Approved for dispatch**

---

### 7. Dispatch Stage
- Final decision is issued.
- Official documentation is generated.
- Application status becomes **Finalized**.

---

## Notifications
- Notifications are sent to the applicant whenever an observation is raised.
- Each role can generate observations during their respective stages.

---

## QA Considerations
- Validate correct status transitions between stages.
- Ensure notifications are sent at each observation event.
- Verify role-based access and permissions.
- Confirm final status consistency between applicant and internal views.

---

## Conclusion
This flow ensures traceability, validation, and quality control throughout the SABE+ application lifecycle.
