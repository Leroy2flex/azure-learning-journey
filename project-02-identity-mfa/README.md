# Project 02 - Identity Protection / MFA

## Goal
Protect Stats SA census accounts so a stolen password alone cannot access data.
Enable remote self-service recovery for fieldworkers far from Head Office.

## What I Built
- Test User: fieldworker1@ngomaleroygmail.onmicrosoft.com
- Security Defaults: Enabled (MFA for all users)
- Method 1: Microsoft Authenticator App
- Method 2: Phone SMS (Self-service backup)

## How It Works
1. User logs in with password
2. Microsoft asks for Authenticator approval
3. Password alone = Access DENIED

## Remote Recovery / Self-Service
- Lost / new phone = User goes to mysignins.microsoft.com
- Verify with SMS code > Delete old phone > Add new phone
- No travel to Head Office required
- If no backup method, IT Helpdesk verifies identity and resets MFA

## Security Applied
- MFA enforced via Security Defaults
- Zero Trust - Never trust, always verify
- Blocks 99%+ of password attacks

## SC-900 Concept
Identity Protection + Authentication Methods

## Proof
Screenshot: Security info shows Authenticator + Phone
Screenshot: Login as fieldworker1 asks to set up Authenticator
