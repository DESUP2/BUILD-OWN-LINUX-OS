# BUILD-OWN-LINUX-OS
BUILD your OWN LINUX OS
Yocto for your embedded Linux project
So let us assume you have chosen Linux for your embedded project. You will likely consider Yocto as a potential candidate in that it is among the most well-known solutions. The Yocto Project is a popular open-source collaboration initiative that helps developers create a custom Linux distribution for their embedded applications. 

Yocto benefits from industry-wide support and is fully configurable.
Among the go-to platforms in the industry and benefiting from broad silicon vendors’ support, Yocto outputs a root filesystem image, a kernel, a bootloader, and a compatible toolchain for the target device.

To get the developers up and running, Yocto provides blueprint root filesystem images for typical Linux OS stacks, as per the screen capture below. For instance, core-image-minimal-initramfs.bb is the most basic configuration allowing a device to boot with a Linux kernel comprising a RAM-based filesystem, whereas core-image-full-cmdline.bb adds CLI tools (e.g. bash, acl, attr, grep, sed and tar) to the initial root filesystem.

Example Linux distribution blueprints available in Yocto.
Developers can then create their custom distro by extending the provided images
