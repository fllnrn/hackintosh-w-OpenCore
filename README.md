# hackintosh
stuff to install and run my first mac
Mobo: Gigabyte Z390 M (bios F3)
Audio: ALC892
CPU: i3-9100
GPU: Intel UHD 630 (0x3e92)
Disk: NVMEe SSD WD WDS500G1B0C

BIOS settings:
	Disable:
-Fast Boot
-VT-d
-CSM
-Intel SGX
-Intel Platform Trust
	Enable
+EHCI Hand-off
+XHCI Hand-off
+OS type: Windows 8.1/10

EFI folder - is my current boot stuff for Mojave.
didnt work:
* NVRAM
* CPU power management?
* Sometimes "Couldn't allocate runtime area" ? https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/extras/kalsr-fix