# macOS High Sierra Guide - Clover

*A Disclaimer: This Procedure Requires an Full Hard Drive Cleanup(if the usb is flashed with the Olarila Vanilla Image), since for some reason the Disk Utility Fails
at formating and screws up the partitions, so it's **recomended** that you have to backup your things before installing this operating system

*Note This Guide is Strictly Linux and macOS oriented.(although the initial steps are possible in windows, it needs a bit of fiddling)

-Pre Flashing-
  - You Need To Use an Tool called GenSMBIOS, since this efi don't include an smbios info(which is needed for any apple services)
  - Fetch The HornDiS kext from https://drive.google.com/file/d/1oBKn5JwKisGOaADY5dE85-coVNqXrkFx/view
  - And Copy it into the /CLOVER/Kexts/Others/ folder
 
 -Flashing-
  - This Step Is Dependent of What Type of macOS did you flash, this Guide Is Specifically Oriented Towards Olarila, but maybe the other distros can boot with this
  - Flash Via BalenaEtcher
  - and Reboot
 
 -Booting Process and the Installation Process-
  - Press F12 on bootup
  - and wait for the process
  - and open disk utility, and press CMD+H and delete the main disk
  - and set what type of the partition it is(although only apfs and hfs).
  - and wait for the installation process
 
 -Post Installation Steps-
  - Connect Your Phone and Tether your Wifi Connection via USB
  - Install an Kext Installer
  - Get The kext from https://www.insanelymac.com/forum/topic/328426-qualcomm-atheros-ar9565-wireless-for-os-x-108-1014/ this forum
  - and use the kext installer and drop the kext and reboot to macOS and voilà *full* macOS but just without bluetooth.

[Initially Edited on January 22 2022]
