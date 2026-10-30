# Lesson 6 Assessment
# Handling API Responses, Errors, and Rate Limits

## 1. Assessment Overview

This assessment evaluates your ability to design, build, test, and validate resilient n8n API integration workflows by applying retry logic, Continue on Fail behavior, pagination, request throttling, and global error handling. The assessment is based on the provided Requirement Document and Implementation Guide.

## 2. Assessment Objective

Demonstrate your ability to build robust API workflows that gracefully handle transient failures, process paginated API responses, prevent rate-limit issues, and capture execution failures using a dedicated Error Trigger workflow.

## 3. Prerequisites

- Review the Requirement Document before starting.
- Review the Implementation Guide.
- Complete Topics 1–5.
- Have an active n8n instance.
- Access to public APIs such as ReqRes, JSONPlaceholder, or Postman Echo.

## 4. Assessment Tasks

- Exercise 1 – Configure HTTP Request Retries: Configure retry attempts and retry delay for an HTTP Request node and validate retry execution.
- Exercise 2 – Implement Continue on Fail: Enable Continue on Fail and verify workflow execution continues with error output.
- Exercise 3 – Build Pagination Workflow: Implement page-offset or cursor pagination with a safe loop limit.
- Exercise 4 – Prevent Rate Limiting: Insert a Wait node to throttle API requests.
- Exercise 5 – Configure Global Error Workflow: Create an Error Trigger workflow capturing execution ID, workflow ID, failed node, and error message, then validate end-to-end execution.

## 5. Practical Assessment Checklist

- [ ] HTTP Request retry configuration implemented
- [ ] Continue on Fail configured and validated
- [ ] Pagination loop implemented
- [ ] Loop safety limit configured
- [ ] Wait node added for throttling
- [ ] Global Error Trigger workflow created
- [ ] Workflow execution validated
- [ ] Documentation completed

## 6. Assessment Success Criteria

- Configure resilient API requests using retries.
- Handle node failures without terminating the workflow.
- Retrieve multi-page API data safely.
- Prevent HTTP 429 errors through throttling.
- Capture and log workflow execution errors.
- Submit all required deliverables.

## 7. Required Deliverables

- Loom/YouTube Demo Video — Mandatory
- Workflow Source Code / Export (.json) — Mandatory
- GitHub Repository (if used) — Recommended
- Description / Additional Comments — Recommended
- Supporting Documents — Optional

## 8. Submission Guidelines

- A Loom or YouTube video demonstrating retries, Continue on Fail, pagination, Wait node, and Error Trigger workflow.
- The exported n8n workflow (.json) or GitHub repository containing the workflow.
- In the Description field, mention challenges, assumptions, limitations, and additional enhancements.

## 9. Final Submission Checklist

- [ ] Completed all assessment exercises
- [ ] Verified workflow execution
- [ ] Exported latest workflow/source code
- [ ] Uploaded demo video
- [ ] Added comments for the assessor
- [ ] Reviewed all deliverables

## 10. Important Note

Before submitting in the LMS, ensure you have provided:
1. A Loom or YouTube demonstration video.
2. The exported workflow source code (.json) or accessible GitHub repository.
3. Additional comments describing challenges, assumptions, limitations, or extra features.
Submissions without the required demonstration video and source code may be considered incomplete.
