# MIPS Open IDE Releases

[MIPS OPEN IDE v1.0.20190323 Download](http://dev-mips-new.pantheonsite.io/resources/download/)

## v1.0.20190323 RELEASE NOTES - 

### NEW FEATURES:
* Managed build and debug of embedded and embedded Linux applications.
* Code generation for specific releases of MIPS ISA with IDE/toolchain.
* "One-click" debug of application by pressing on "Debug As" button on menu toolbar.
* Support for *-mti-* versions of MIPS toolchain from
	https://codescape.mips.com/components/toolchain/2018.09-03/downloads.html
* Added Windows desktop shorcut after installation.
* Verify Qemu, RootFS and Kernel checksum before running Debug - this feature may be disabled in future releases do the slow down in debug perfoformance.
* Check availability of MIPS toolchain on startup.

### KNOWN BUGS:
* Managed build of C++ application not yet supported.
* Can't set Product Provider.
* Linux version: No menu icons when dropdown from menu toolbar.
* Window version: A black frame appears at icon when creating new C project.
* An error image in the bottom left of Welcome Page.
* Currently support to build only mips32r2 Big Endian (with MIPS Embedded Linux toolchain) and mips32r2 Little Endian (with MIPS Embedded toolchain).

### ANTICIPATED NEXT RELEASE FEATURES:
* Support for managed build of C++ application.
* Update the Welcome Page.
* Support to managed build of multiple MIPS architecture: Mips32r2-r6 BL, EL.
* Upgrade to the latest Eclipse version.
