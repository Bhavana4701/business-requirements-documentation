# User Stories Template

## Format
As a [type of user]
I want to [perform some action]
So that [I can achieve some goal]

---

## User Story 1 — Data Upload
**As a** business analyst
**I want to** upload a CSV data file to the system
**So that** I can run validation checks on the data

### Acceptance Criteria
- File must be in CSV format
- File size must not exceed 50MB
- System confirms successful upload with message
- Invalid file formats are rejected with clear error message

---

## User Story 2 — Data Validation
**As a** QA analyst
**I want to** run automated validation on uploaded data
**So that** I can identify data quality issues before production

### Acceptance Criteria
- System checks for NULL values in all required fields
- System detects duplicate records
- Validation report generated within 30 seconds
- Report shows pass/fail status per validation rule

---

## User Story 3 — Reporting
**As a** business stakeholder
**I want to** view a validation summary report
**So that** I can make informed release decisions

### Acceptance Criteria
- Report shows total records processed
- Report shows number of issues found
- Report can be exported as PDF
- Report is accessible within 5 seconds
