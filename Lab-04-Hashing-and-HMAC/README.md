# Lab 04 — Cryptographic Hashing & HMAC

## Objective
Understand cryptographic hash functions and how HMAC provides message authentication using a shared secret key.

## Key Concepts
- One-way hashing and fixed-length digests
- SHA-256 and legacy MD5
- File integrity verification
- Password hashing versus general-purpose file hashing
- HMAC and message authenticity

## Practical Checklist
- [ ] Generate a SHA-256 digest for a test file.
- [ ] Change the file and compare its digest.
- [ ] Verify a file against a known checksum.
- [ ] Generate and verify an HMAC using a lab-only secret.
- [ ] Explain why a plain hash alone does not prove who created a file.

## Security Note
MD5 is included only for comparison/legacy awareness; do not use it for security-sensitive integrity or password storage. Never commit real HMAC keys.
