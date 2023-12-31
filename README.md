# debian-live
Builds a Debian Live x86-64 ISO monthly using GitHub Actions. Used for live usb Linux on USB Stick ....


## Default Password
The default username and password is root / toor.


## Installation Options
1. Burn / mount the ISO
2. Copy the files to a FAT32 formatted USB drive
    * Only works on modern UEFI based systems
3. Use `dd` to flash the ISO to a USB drive
    * Would only recommend for older BIOS based systems
4. Use https://www.ventoy.net/en/index.html


## Tools

cifs-utils - Mount `Samba` and `Windows` file shares

ddrescue - Backup and restore failing drives

gdisk - `gpt` compatible `fdisk` toolset

nfs-common - mount `nfs` file shares

ntfs-3g - Manage `NTFS` formatted drives

wimtools - Create, restore, and manage `WIM` files for Windows based systems.

nmap - check network connections

iperf3 - check network performance

For a full list of installed packages, see `packages.txt` in the release.




## References
This image was built based from the instructions found at https://willhaley.com/blog/custom-debian-live-environment/
