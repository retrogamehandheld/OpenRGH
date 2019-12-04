# OpenRGH<br>
### An independent fork of the OpenDingux project, focused on improving the user experience. 

## Goals:
* exFAT support, auto-resize, constant sdcard mount point - 1.7.5 branch
* Replace Gmenu2x with GmenuNX, Suspend capability - 1.8.x branch
* Kernel update -2.x branch
* Modernize 3D APIs - 2.1.x
* HDMI support - 2.2.x
* Vulkan?? - Future

# Updated firmware 1.7.5 beta 5:<br>

## Changelog:<br>
### Beta5:<br>
1. exfAT support added - no more need to download a utility to format 64GB+ SD cards
2. Default SD card mount changed to /media/sdcard - No having to re-do paths when swapping SD cards
3. Auto swap file and partition resize - This takes a while, allow it to finish.  Progress will be shown on screen during first boot
4. Duplicate modules removed from modules.squashfs 
5. Fix the resize in old stock firmwares (bad ext4 partition)
6. Fixed power off and reboot error messages
7. Fixed slowdowns and stuttering during first 15 minutes after first boot

## Instructions:<br>
1. Place in /media/data/apps or /media/<your SD card>/apps
2. Run from gmenu2x (not currently working in gmenunx)
3. allow process to complete
4. Reboot
5. If system fails to boot, press Y to boot to last working kernel, or X to boot to last working rootfs. X+Y will load your previous OS version.
