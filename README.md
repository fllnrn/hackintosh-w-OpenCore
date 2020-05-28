# hackintosh
stuff to install and run my first mac
Mobo: Gigabyte Z390 M (bios F5)
Audio: ALC892
CPU: i3-9100
GPU: Intel UHD 630 (0x3e91)
Disk: NVMEe SSD WD WDS500G1B0C

BIOS settings:
Disable:
	-Fast Boot
	-VT-d
	-CSM
	-Intel SGX
	-Intel Platform Trust
Enable: 
+igpu memory limit: max
+  4g encoding enable
+EHCI Hand-off
	+XHCI Hand-off
	+OS type: Windows 8.1/10

EFI folder - is my current boot stuff for Mojave.

didnt work?:
* iMessage https://applelife.ru/threads/nastrojka-app-store-imessage-facetime-i-icloud.40790/page-219#post-727913
* FaceTime

? DisplayPort (NotTested)
? try to remove 
    framebuffer-patch-enable 
    framebuffer-stolenmem 
    ig-platform-id
? try to add
    igfxfw | Data | <02 00 00 00>


TOOLS:
MaciASL
macinfo
MountEFI
OpenCorePkg
ProperTree
USBMap
Clean Cache Apple Services.command
IORegistryExplorer
Hackingtool 
