# Lab 06 — Command Reference

> The commands below can destroy data if used on the wrong device. Use only the disposable device explicitly assigned by your instructor.

| Command | Purpose |
|---|---|
| `lsblk -f` | Inspect block devices and filesystems |
| `sudo cryptsetup luksDump /dev/DEVICE` | Inspect LUKS metadata |
| `sudo cryptsetup luksOpen /dev/DEVICE lab_crypt` | Open an encrypted device |
| `sudo cryptsetup status lab_crypt` | Inspect an active mapping |
| `sudo cryptsetup luksClose lab_crypt` | Close an encrypted mapping |

Replace `/dev/DEVICE` only after verifying the exact disposable lab device. Do not run `luksFormat`, `mkfs`, or partitioning commands on an unverified device.

## Observations
Record the device type, LUKS version, successful verification steps, and any errors. Never upload passphrases or key material.
