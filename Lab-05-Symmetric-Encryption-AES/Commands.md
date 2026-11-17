# Lab 05 — Command Reference

> OpenSSL options differ by version. Use the syntax required by your lab manual and note the installed version.

| Command | Purpose |
|---|---|
| `openssl version` | Show OpenSSL version |
| `openssl enc -list` | List supported encryption algorithms |
| `openssl rand -hex 16` | Generate 16 random bytes as hex |
| `sha256sum filename` | Check file digest before/after a workflow |

## Example Inspection

```bash
openssl version
openssl enc -list
```

Add the exact encryption/decryption commands taught in your manual here, along with the cipher mode, KDF, salt, and IV/nonce handling. Do not publish passwords or keys.
