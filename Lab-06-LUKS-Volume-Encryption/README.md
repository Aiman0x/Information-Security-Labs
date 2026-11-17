# Lab 06 — LUKS Volume Encryption

## Objective
Understand Linux Unified Key Setup (LUKS) and how it protects data at rest using encrypted block devices.

## Key Concepts
- Full-disk and volume encryption
- LUKS metadata/header
- Passphrases and key slots
- Mapping an encrypted device
- Opening, closing, and safely backing up encrypted volumes

## Practical Checklist
- [ ] Identify the disposable virtual disk or loopback device assigned for the lab.
- [ ] Inspect device layout before making changes.
- [ ] Initialize LUKS only on the intended test device.
- [ ] Open the encrypted mapping and create a test filesystem if required.
- [ ] Mount, test, unmount, and close the mapping.
- [ ] Review LUKS header backup and recovery precautions.

## Critical Warning
Formatting or initializing the wrong block device can permanently destroy data. Never run destructive commands against your system disk or a disk containing personal files. Follow the lab manual and verify the device identity at every step.
