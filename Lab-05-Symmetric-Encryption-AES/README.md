# Lab 05 — Symmetric Encryption & AES

## Objective
Explore symmetric encryption and use AES through OpenSSL to understand confidentiality, keys, initialization vectors, and password-based key derivation.

## Key Concepts
- Symmetric encryption and shared secret keys
- AES block cipher
- Cipher modes and IV/nonce requirements
- Password-based key derivation (PBKDF2)
- Encryption versus integrity/authentication
- Why unauthenticated encryption can be unsafe

## Practical Checklist
- [ ] Create a harmless sample plaintext file.
- [ ] Encrypt and decrypt it using the method specified in the manual.
- [ ] Compare plaintext and ciphertext.
- [ ] Verify that decryption restores the original file.
- [ ] Explain the role of the key, IV, and KDF.
- [ ] Record the exact OpenSSL version and command options.

## Security Note
Use lab-only data and secrets. Prefer authenticated encryption (such as AES-GCM) when supported by the exercise. Do not reuse IVs/nonces with the same key.
