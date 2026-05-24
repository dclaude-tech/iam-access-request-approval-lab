# Lab plan

## Project objective

This lab simulates an IAM access request and approval workflow in Microsoft Entra ID for fictional Finance, HR, and IT resources.

The goal is to document how access requests are reviewed, approved or denied, assigned, verified, and closed using IAM Analyst-style evidence and ticket notes.

## Tenant

Northstar Identity Lab

## Planned request workflow

1. User submits or is represented as requesting access.
2. Business justification is reviewed.
3. Approval requirement is checked.
4. Access is approved or denied.
5. Approved access is assigned using Microsoft Entra.
6. Access assignment is verified.
7. Ticket notes are documented and closed.

## Workflow decision

Entitlement management is available in this tenant, so this lab will use Microsoft Entra access packages as the primary access request and approval workflow.

## Planned access packages

| Access package | Purpose |
|---|---|
| AP-Finance-Reports-Read | Read-only access to Finance reporting resources |
| AP-HR-Employee-Records-Read | Read-only access to HR employee records |
| AP-IT-ServiceDesk-Tools | Access to IT service desk tools |

## Supporting security groups

| Security group | Purpose |
|---|---|
| SG-Finance-Reports-Read | Read-only access to Finance reporting resources |
| SG-HR-Employee-Records-Read | Read-only access to HR employee records |
| SG-IT-ServiceDesk-Tools | Access to IT service desk tools |

## Ticket scenarios

| Ticket | Scenario | Expected outcome |
|---|---|---|
| TICKET-001 | Finance reports read-only access request | Approved |
| TICKET-002 | HR employee records access request | Denied |
| TICKET-003 | IT service desk tools access request | Requires manager or resource-owner approval |

## Evidence plan

Screenshots will be collected to document:

- Entitlement management availability
- Security group creation
- Access package configuration
- Request and approval workflow
- Access assignment
- Access verification
- Ticket closure documentation

## Current design decision

Entitlement management availability: Available.

Lab path selected: Access package-based workflow.
