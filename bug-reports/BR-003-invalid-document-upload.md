# BR-003 – System allows incorrect document upload

## Summary
The system allows uploading a document that does not match the requested document type.

## Environment
- System: Internal scholarship application system
- Environment: Test
- Browser: Chrome

## Preconditions
- User is filling applicant information
- Document upload section is available

## Steps to Reproduce
1. Navigate to applicant information step
2. Go to "Upload Identity Document"
3. Upload a PDF file that is not an identity document
4. Save the form

## Expected Result
The system should validate the document type and display an error message if the uploaded file does not match the required document.

## Actual Result
The system accepts the file without validation.

## Impact
- Incorrect documentation stored
- Risk of invalid application processing
- Data integrity issues

## Severity
Medium

## Priority
Medium

## Evidence
<img width="2003" height="1004" alt="image" src="https://github.com/user-attachments/assets/218bd623-b752-410b-962a-21eaf0f3012f" />

