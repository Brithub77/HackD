*** HackD v1.1 by Brithub77 ***
*** Everything you need in order to get your Series3 TiVo HackD ***

USE AT YOUR OWN RISK! I WILL NOT BE HELD RESPONSIBLE IF YOUR BREAK YOUR TIVO.
_____________________________________________________________________________

INSTRUCTIONS FOR USE:

1. Take the drive out of the TiVo and attach it to your computer.

2. Run "HackD". It will automate the hacking process so that you won't
have to do it yourself.

3. Run patch scripts if you'd like.

4. That's it! Put the drive back in the TiVo and see if it boots up.

_____________________________________________________________________________

CONTENTS:

HackD -- initial directory  
  -> oztivoapp_patches -- software-specific patches for AU/NZ tivoapps to 
     enable backdoors, disable encyrption, etc.   
  -> Saved_Apps -- where unmodified backups of tivoapp binary files are 
     located
  -> Saved_Kernels -- where unmodified backups of TiVo kernels are located
  -> source_video -- contains examples of videos extracted from hacked TiVos
  -> tivoapp_patches -- software-specific patches for US tivoapps to enable 
     backdoors, disable encyrption, etc.
  -> bootpage -- sets boot parameters to TiVo 
  -> busybox_AU.tar.gz -- busybox distro complete with all the necessary 
     hacks and utilities for AU/NZ TiVos
  -> busybox_US.tar.gz -- busybox distro complete with all the necessary 
     hacks and utilities for US TiVos
  -> get-password.sh -- the script in which you choose your own username and 
     password for logging in to the server
  -> hack_oztivoapp_PC -- patches AU/NZ tivoapps while the drive is attached 
     to the PC
  -> hack_oztivoapp_TiVo -- natively patches AU/NZ tivoapps 
  -> hack_tivoapp_PC -- patches US tivoapps while the drive is attached to 
     the PC
  -> hack_tivoapp_TiVo -- natively patches US tivoapps
  -> HackD -- main script
  -> null-linuxrc.img.gz -- backup of the initrd (ROM) from a TiVo kernel
  -> rc.sysinit.author -- startup script that allows all hacks to run once 
     MyWorld (TiVo's UI) is finished loading
  -> README -- this file
  -> replace_initrd_AU.x86 -- replaces the initrd in an AU/NZ TiVo kernel 
     and backs up the original initrd, as well as the kernel itself, to 
     allow the PROM to pass boot checks
  -> replace_initrd_US.x86 -- replaces the initrd in an US TiVo kernel and 
     backs up the original initrd, as well as the kernel itself, to allow 
     the PROM to pass boot checks
  -> tivopart -- can revalidate the TiVo drive for Linux to read, as well 
     as perform some other tasks that could corrupt it for the time being; 
     needed in order to mount drive partitions