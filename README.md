# MacOSWiki

## Clover configurator
https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/


## Drivers

### Networking (e.g intel IV219)
https://github.com/Mieze/IntelMausiEthernet

### AMD Gpu driver
https://github.com/acidanthera/whatevergreen/releases
https://github.com/acidanthera/Lilu/releases

### Audio driver
https://github.com/acidanthera/AppleALC/releases

### Preferred method to deal with MacOS 20 USB limit port
https://www.tonymacx86.com/threads/guide-creating-a-custom-ssdt-for-usbinjectall-kext.211311/

## Common issues
### Kernel panic from AppleALC on wake when using external GPU
1. Make sure to inject No-HDA-Gfx property from here:
https://github.com/acidanthera/bugtracker/issues/513
