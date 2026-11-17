# Lab 02 — Command Reference

> Account creation and privilege changes affect the operating system. Perform them only in a disposable or authorized Linux VM.

| Command | Purpose |
|---|---|
| `whoami` | Show current username |
| `id` | Show UID, GID, and group memberships |
| `getent passwd` | Query user account records |
| `getent group` | Query group records |
| `sudo groupadd labgroup` | Create a group |
| `sudo useradd -m labuser` | Create a user with a home directory |
| `sudo usermod -aG labgroup labuser` | Add user to supplementary group |
| `groups labuser` | Display a user's groups |
| `sudo visudo` | Safely edit sudoers policy |

## Verification Example

```bash
whoami
id
getent group labgroup
groups labuser
```

Do not grant broad administrator access merely to make a practical command work. Record the minimum privilege required.
