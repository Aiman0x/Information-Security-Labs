# Lab 04 — Command Reference

| Command | Purpose |
|---|---|
| `sha256sum filename` | Calculate SHA-256 digest |
| `md5sum filename` | Calculate legacy MD5 digest for comparison only |
| `sha256sum -c checksums.txt` | Verify checksums from a file |
| `openssl dgst -sha256 filename` | Calculate a digest with OpenSSL |
| `openssl dgst -sha256 -hmac 'LAB_KEY' filename` | Calculate HMAC-SHA256 with a lab-only key |

## Safe Practice Example

```bash
printf 'Information Security Lab\n' > sample.txt
sha256sum sample.txt
printf 'changed\n' >> sample.txt
sha256sum sample.txt
```

Use a dummy key for demonstrations. Do not store production secrets in this repository.
