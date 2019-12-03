# hackintosh
stuff to install and run my first mac
Mobo: Gigabyte Z390 M (bios F3)
Audio: ALC892
CPU: i3-9100
GPU: Intel UHD 630 (0x3e92)
?GPU: Gigabyte 650 Ti 2GB (onli 1 GB available) : tested VGA - sucessful
	Will replace to 5$ hdmi-vga adapter, when DVI-D was fixed
Disk: NVMEe SSD WD WDS500G1B0C

BIOS settings:
Disable:
	-Fast Boot
	-VT-d
	-CSM
	-Intel SGX
	-Intel Platform Trust
Enable:
	+EHCI Hand-off
	+XHCI Hand-off
	+OS type: Windows 8.1/10

EFI folder - is my current boot stuff for Mojave.

didnt work?:
* iMessage https://applelife.ru/threads/nastrojka-app-store-imessage-facetime-i-icloud.40790/page-219#post-727913
* FaceTime

* DVI-D https://www.tonymacx86.com/threads/guide-general-framebuffer-patching-guide-hdmi-black-screen-problem.269149/
* DisplayPort (NotTested)


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
