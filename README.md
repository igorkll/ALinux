# ALinux
minimal linux build for my projects  
Architecture: x86  
Target firmware: BIOS / UEFI in legacy mode  
There is no UEFI support to avoid taking up space for an EFI partition  
Build system: https://github.com/igorkll/syslbuild  
although this distribution contains full-fledged GNU utilities (NOT busybox) and several useful tools,  
it is still minimal and highly specialized. for example, it does not contain a login and user system, but only a root  

## supported tools
* lua / luac
* bash
* nano
