# Lab 03 — PAM Authentication & Multi-Factor Authentication

## Objective
Understand Linux Pluggable Authentication Modules (PAM), password policy enforcement, and time-based one-time passwords (TOTP).

## Key Concepts
- PAM authentication stack and module configuration
- Password quality and account policy
- Authentication factors: knowledge, possession, and inherence
- TOTP and time-based verification
- Secure backup and recovery considerations

## Practical Checklist
- [ ] Identify PAM configuration files relevant to the lab distribution.
- [ ] Review the authentication flow and module order.
- [ ] Examine password-quality policy.
- [ ] Configure MFA only by following the lab manual.
- [ ] Test successful and unsuccessful authentication.
- [ ] Confirm a recovery path before enabling MFA.

## Important
A mistake in PAM configuration can lock users out. Keep an active administrator session and a VM snapshot/recovery method while testing. Never upload real recovery codes or authenticator secrets.
