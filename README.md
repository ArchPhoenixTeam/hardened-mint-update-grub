# hardened-mint-update-grub
/etc/kernel/postinst.d/ script to properly update grub when updating kernel.

Require proper mount points for boot and efi partition (in /boot and /boot/efi)
Not tested on systems without UEFI.
