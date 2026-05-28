# IAM Access Request and Approval Lab

## Project summary

This project is a fictional Microsoft Entra ID IAM lab that simulates an access request and approval workflow for Finance, HR, and IT resources.

The lab documents how access requests are reviewed, approved or denied, assigned, verified, and closed using IAM Analyst-style documentation.

## Business scenario

Northstar Identity Lab is a fictional organization using Microsoft Entra ID to manage access to internal resources. Users submit access requests for department-specific resources such as Finance reports, HR employee records, and IT service desk tools.

Each request is reviewed based on business justification, least privilege, approval requirements, and access verification evidence.

## Tools used

- Microsoft Entra ID
- Microsoft Entra security groups
- Microsoft Entra entitlement management
- GitHub
- Markdown documentation

## IAM skills demonstrated

- Access request review
- Approval workflow documentation
- Least privilege analysis
- Group-based access assignment
- Access verification
- Ticket documentation
- Access denial documentation
- IAM evidence collection
- Ticket closure notes

## Planned ticket scenarios

| Ticket | Scenario | Expected outcome |
|---|---|---|
| TICKET-001 | Finance reports read-only access request | Approved |
| TICKET-002 | HR employee records access request | Denied |
| TICKET-003 | IT service desk tools access request | Requires manager or resource-owner approval |

## Supporting access groups

| Security group | Purpose | Access level |
|---|---|---|
| SG-Finance-Reports-Read | Provides access to fictional Finance reporting resources | Read-only |
| SG-HR-Employee-Records-Read | Provides access to fictional HR employee records resources | Read-only |
| SG-IT-ServiceDesk-Tools | Provides access to fictional IT service desk tools | Standard user access |

These groups are intentionally created without members at the start of the lab. Access will be assigned later through the access request and approval workflow.

## Access packages

| Access package | Connected security group | Purpose |
|---|---|---|
| AP-Finance-Reports-Read | SG-Finance-Reports-Read | Request-based access to fictional Finance reporting resources |
| AP-HR-Employee-Records-Read | SG-HR-Employee-Records-Read | Request-based access to fictional HR employee records resources |
| AP-IT-ServiceDesk-Tools | SG-IT-ServiceDesk-Tools | Request-based access to fictional IT service desk tools |

Each access package is connected to a dedicated Microsoft Entra security group. Request and approval policies will be configured separately to support the ticket scenarios.

## Lab identities

| User | Role in lab | Ticket use |
|---|---|---|
| Ava Finance | Finance requester | TICKET-001 approved Finance reports access |
| Mia HR | HR requester | TICKET-002 denied HR employee records access |
| Leo IT | IT requester | TICKET-003 IT service desk tools request |
| Riley Manager | Approver/resource owner | Approval review for access requests |

These are fictional lab identities created only for portfolio documentation and IAM workflow simulation.

## Repository structure

| Folder | Purpose |
|---|---|
| docs | Supporting lab documentation and process notes |
| screenshots | Visual evidence collected throughout the lab |
| screenshots/01-repository-setup | Repository setup evidence |
| screenshots/02-entra-groups | Microsoft Entra group configuration evidence |
| screenshots/03-access-packages | Entitlement management and access package evidence |
| screenshots/04-ticket-workflows | Access request, approval, denial, and ticket workflow evidence |
| screenshots/05-access-verification | Access assignment and verification evidence |
| tickets | Fictional IAM ticket documentation for each access request scenario |

## Project status

In progress.

## Disclaimer

This is a fictional lab environment created for portfolio and learning purposes. It does not include confidential, employer, customer, or production information.
