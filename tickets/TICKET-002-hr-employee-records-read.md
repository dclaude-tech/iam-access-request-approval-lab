# TICKET-002: HR employee records access request

## Ticket summary

| Field                  | Details                     |
| ---------------------- | --------------------------- |
| Ticket ID              | TICKET-002                  |
| Requester              | Mia HR                      |
| Requested access       | AP-HR-Employee-Records-Read |
| Backing security group | SG-HR-Employee-Records-Read |
| Resource area          | HR employee records         |
| Access level           | Read-only                   |
| Expected outcome       | Denied                      |
| Ticket status          | Closed                      |

## Business justification

Mia HR requested read-only access to fictional HR employee records to review employee information for department reporting.

## IAM analyst review

The request was reviewed against least privilege, business need, and the sensitivity of HR employee records.

Although the requester provided a business justification, the request did not include enough detail about the specific records, scope, or business purpose required to grant access to sensitive HR employee records.

Because HR employee records may contain sensitive employee information, the request was denied.

## Approval path

| Approval step | Reviewer      | Decision | Notes                                                                                                                                                |
| ------------- | ------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Stage 1       | Riley Manager | Denied   | Request denied because the justification did not provide enough detail about the specific records, scope, or business need required to grant access. |

## Access assignment

Access was not assigned.

No delivered assignment was created for AP-HR-Employee-Records-Read.

## Verification evidence

| Evidence                           | Screenshot                                                                       |
| ---------------------------------- | -------------------------------------------------------------------------------- |
| Request submitted                  | `screenshots/04-ticket-workflows/ticket-002-request-submitted.png`               |
| Request denied                     | `screenshots/04-ticket-workflows/ticket-002-request-denied.png`                  |
| No access package assignment found | `screenshots/05-access-verification/ticket-002-no-access-package-assignment.png` |
| No security group membership found | `screenshots/05-access-verification/ticket-002-group-membership-not-found.png`   |

## Closure notes

TICKET-002 was denied, verified, and closed.

Mia HR did not receive access to AP-HR-Employee-Records-Read and was not added to SG-HR-Employee-Records-Read.
