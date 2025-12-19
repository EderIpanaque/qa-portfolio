# TC-003 – Upload Valid Identity Document

## Test Case ID
TC-003

## Title
Validate successful upload of a valid identity document.

## Related Requirement
The system must allow uploading a valid identity document in the applicant information step.

## Pre-conditions
- User is logged into the system
- User is filling the scholarship application form
- User is on the "Applicant Information" step
- Document upload section is available

## Test Data
- File type: PDF
- File name: DNI_Postulante.pdf (valid identity document)

## Test Steps
1. Navigate to the "Applicant Information" step
2. Locate the section "Upload Identity Document"
3. Click on "Upload Document"
4. Select a valid identity document file (PDF)
5. Save or continue the form

## Expected Result
- The system accepts the uploaded document
- The document is displayed in the uploaded files list
- No error messages are shown
- User can continue to the next step successfully

## Actual Result
Document is uploaded successfully and displayed correctly.

## Status
Pass

## Severity
N/A

## Priority
N/A

## Notes
This test case validates the correct behavior of the document upload functionality when valid data is provided.
