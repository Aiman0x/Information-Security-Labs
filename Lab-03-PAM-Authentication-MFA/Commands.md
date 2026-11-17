# Lab 03 — Command Reference

> PAM configuration is security-critical. Do not copy configuration lines blindly; follow the exact lab manual and distribution-specific instructions.

| Command | Purpose |
|---|---|
| `man pam` | Read PAM overview (where available) |
| `ls /etc/pam.d/` | List PAM service configuration files |
| `grep -R "pam_" /etc/pam.d/` | Inspect PAM module references |
| `sudo apt install libpam-pwquality` | Install password-quality module on Debian/Ubuntu-based systems |
| `pwscore` | Check password strength where installed |
| `timedatectl` | Inspect system time settings |

## Notes
- TOTP depends on correct time synchronization.
- Do not publish QR codes, shared secrets, backup codes, or private authentication material.
- Record the module name, purpose, test case, and observed result without exposing secrets.
