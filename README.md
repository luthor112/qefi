# qefi
Quick POSIX-UEFI environment and test script

Based on:
- [POSIX-UEFI on GitLab](https://gitlab.com/bztsrc/posix-uefi)
- [UEFI on OSDev](https://wiki.osdev.org/UEFI)
- [POSIX-UEFI on OSDev](https://wiki.osdev.org/POSIX-UEFI)

Commands:
- `qefi setup` installs needed dependencies
- `qefi new NAME` creates a new environment in the NAME directory
- `qefi build` runs `make`...
- `qefi image` builds a disk image containing the built binary
- `qefi run` runs QEMU and drops you into the EFI Shell