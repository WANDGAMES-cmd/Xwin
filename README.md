# Xwin

Xwin is a free operating system written in Rust, with no ads or telemetry.

## Status

Xwin is currently an early development build.

It has only been tested in QEMU. Running Xwin on real hardware is not currently recommended.

## Current features

* Rust-based x86_64 kernel
* GNU GRUB 2 bootloader
* Multiboot2 framebuffer
* Graphical interface
* Shell
* Basic filesystem support
* Experimental storage support

## Testing

For now, use a virtual machine such as QEMU.

Do not install Xwin on a real computer yet. The system is still under development and has not been tested on real hardware.

## Bootloader

Xwin uses GNU GRUB 2 as its bootloader.

GNU GRUB 2 is licensed under the GNU General Public License v3.0 (GPLv3).
