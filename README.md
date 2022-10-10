# qefi
Quick UEFI application development environment and test script

Based on:
- [POSIX-UEFI on GitLab](https://gitlab.com/bztsrc/posix-uefi)
- [GNU-EFI on SourceForge](https://git.code.sf.net/p/gnu-efi/code)
- [UEFI on OSDev](https://wiki.osdev.org/UEFI)
- [POSIX-UEFI on OSDev](https://wiki.osdev.org/POSIX-UEFI)
- [GNU-EFI on OSDev](https://wiki.osdev.org/GNU-EFI)

Commands:
- `qefi setup-posix` installs needed dependencies for development with POSIX-UEFI
- `qefi setup-gnu` installs needed dependencies for development with GNU-EFI
- `qefi new-posix NAME` creates a new POSIX-UEFI environment in the NAME directory
- `qefi new-gnu NAME` creates a new GNU-EFI environment in the NAME directory
- `qefi build-posix` runs `make`
- `qefi build-gnu` builds the one-file application
- `qefi image` builds a disk image containing the built binary
- `qefi run` runs QEMU and drops you into the EFI Shell