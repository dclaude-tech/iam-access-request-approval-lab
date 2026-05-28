# TICKET-001: Finance reports read-only access request

## Ticket summary

| Field                  | Details                 |
| ---------------------- | ----------------------- |
| Ticket ID              | TICKET-001              |
| Requester              | Ava Finance             |
| Requested access       | AP-Finance-Reports-Read |
| Backing security group | SG-Finance-Reports-Read |
| Resource area          | Finance reporting       |
| Access level           | Read-only               |
| Expected outcome       | Approved                |
| Ticket status          | Closed                  |

## Business justification

Ava Finance requested read-only access to fictional Finance reporting resources to support monthly reporting review and analysis.

## IAM analyst review

The request aligns with the requester’s fictional Finance role and follows least privilege because the requested access is limited to read-only Finance reporting resources.

The access package policy required business justification and approval before access could be assigned.

## Approval path

| Approval step | Reviewer      | Decision | Notes                                                                                                                   |
| ------------- | ------------- | -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Stage 1       | Riley Manager | Approved | Request approved because the access matched the requester’s fictional Finance role and supported a valid business need. |

## Access assignment

Access was assigned through the AP-Finance-Reports-Read access package after approval.

The access package assignment was delivered to Ava Finance.

## Verification evidence

| Evidence                            | Screenshot                                                                    |
| ----------------------------------- | ----------------------------------------------------------------------------- |
| Request submitted                   | `screenshots/04-ticket-workflows/ticket-001-request-submitted.png`            |
| Request approved                    | `screenshots/04-ticket-workflows/ticket-001-request-approved.png`             |
| Access package assignment delivered | `screenshots/05-access-verification/ticket-001-access-package-assignment.png` |
| Security group membership verified  | `screenshots/05-access-verification/ticket-001-group-membership-verified.png` |

## Closure notes

TICKET-001 was approved, assigned, verified, and closed.

Ava Finance received read-only Finance reporting access through the approved access package workflow. Group membership was verified in SG-Finance-Reports-Read.
