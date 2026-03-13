# MacVirt — Modified QEMU

[Camouflage](https://camouflage.network) uses **camouflage-vmkit** (Apple Virtualization.framework) for Linux virtual machines and **QEMU** for Windows virtual machines. Both are packaged inside the **MacVirt.app** bundle.

This is a fork of [QEMU](https://www.qemu.org/) modified by Camouflage Networks, Inc. for use in the MacVirt virtual machine manager.

## Modifications

- `ui/cocoa.m`: Replaced "QEMU" branding with "MacVirt" in the macOS menu bar, window title, and About dialog.

No functional changes were made to the emulator.

## License

QEMU is licensed under the GNU General Public License v2 (GPLv2).
The modified file `ui/cocoa.m` is licensed under the MIT License (Copyright Mike Kronenberg).

"QEMU" is a trademark of Fabrice Bellard.

## Source Code

The complete source code for this modified version is available at:
https://github.com/CamouflageNetworks/qemu
