# Project 01 - Secure Census Storage

## Goal
Create a secure storage foundation for Stats SA census data in South Africa, following POPIA.

## What I Built
- Resource Group: rg-securecensus (South Africa North)
- Entra ID Groups: Fieldworkers, Supervisors
- Storage Account: stsecurecensusleroy

## Security Applied
- Location: South Africa North (data residency for POPIA)
- Public network access: Disabled
- Identity: Least privilege via groups, not individual users

## SC-900 Concept
Defense in Depth + Identity and Access - Block network access first, then control who can access data.

## Proof
Screenshot: Public network access = Disabled
