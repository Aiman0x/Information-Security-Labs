# Lab 01 — Command Reference

> Run these commands only in your own test directory or authorized lab VM. Some ownership operations require administrator privileges.

| Command | Purpose |
|---|---|
| `ls -l` | View permissions and ownership |
| `stat filename` | View detailed file metadata |
| `chmod 640 filename` | Set owner read/write, group read, others no access |
| `chmod u+x filename` | Add execute permission for the owner |
| `chown user filename` | Change file owner (usually requires sudo) |
| `chgrp group filename` | Change group ownership |
| `id` | Show current user and group IDs |
| `umask` | View the default permission mask |

## Safe Practice Example

```bash
mkdir -p ~/is-lab/lab01
cd ~/is-lab/lab01
touch sample.txt
ls -l sample.txt
chmod 640 sample.txt
stat sample.txt
```

## Observations
Record your own command output and explain what changed after each permission operation.
