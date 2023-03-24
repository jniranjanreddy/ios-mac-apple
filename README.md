## MAC OS Versions
## https://www.youtube.com/watch?v=qxYq8R8rOTA
```
macOS	Latest version
macOS Ventura	13.2.1
macOS Monterey	12.6.3
macOS Big Sur	11.7.4
macOS Catalina
10.15.7
macOS Mojave	10.14.6
macOS High Sierra	10.13.6
macOS Sierra	10.12.6
OS X El Capitan	10.11.6
OS X Yosemite	10.10.5
OS X Mavericks	10.9.5
OS X Mountain Lion	10.8.5
OS X Lion	10.7.5
Mac OS X Snow Leopard	10.6.8
Mac OS X Leopard	10.5.8
Mac OS X Tiger	10.4.11
Mac OS X Panther	10.3.9
Mac OS X Jaguar	10.2.8
Mac OS X Puma	10.1.5
Mac OS X Cheetah	10.0.4
```
## How to install MACOS in Virtual Box.
```
Execute inline commands in the windows command prompt.
NOTE:  Replace hostname with Machine Name
cd "C:\Program Files\Oracle\VirtualBox\"
VBoxManage.exe modifyvm "Virtual Machine Name" --cpuidset 00000001 000106e5 00100800 0098e3fd bfebfbff
VBoxManage setextradata "Virtual Machine Name" "VBoxInternal/Devices/efi/0/Config/DmiSystemProduct" "iMac11,3"
VBoxManage setextradata "Virtual Machine Name" "VBoxInternal/Devices/efi/0/Config/DmiSystemVersion" "1.0"
VBoxManage setextradata "Virtual Machine Name" "VBoxInternal/Devices/efi/0/Config/DmiBoardProduct" "Iloveapple"
VBoxManage setextradata "Virtual Machine Name" "VBoxInternal/Devices/smc/0/Config/DeviceKey" "ourhardworkbythesewordsguardedpleasedontsteal(c)AppleComputerInc"
VBoxManage setextradata "Virtual Machine Name" "VBoxInternal/Devices/smc/0/Config/GetKeyFromRealSMC" 1
```
