# Thinkpad-x390-mac-tahoe
>[!Warning]
>This EFI may or may not have issues! Please be prepared to edit it and please have the knowhow to do so, I will push updates on my own accord. Unless I'm paid I won't do it for you (Mostly joking)
# About
This is my efi I made (with assistance from a [premade t490 efi](https://github.com/5T33Z0/Thinkpad-T490-Hackintosh-OpenCore) since the computers are similar)  and showed off my computer running on in [this reddit post](https://www.reddit.com/r/hackintosh/comments/1otyvob/thinkpad_x390_hackintosh_success/) however, obviously there have been some modifications and tweaks made since then. Mainly now the computer is now running the latest version of Tahoe since then, however there are some issues
>[!Warning]
>The touch screen is not enabled in macOS in this EFI. On macOS Tahoe VoodooI2C will cause the machine to not be able to shut down (sequoia and older don't suffer from this issue), the kexts are in there but are disabled to prevent confusion, re-enabling them will fix the touchscreen but the machine will need to be force shut down as needed
# Info
- Fixed intel wifi using stock oclp, not gonna share method, figure it out or google it!
- Used [YogaSMC](https://github.com/zhen-zen/YogaSMC) fork [ReYogaSMC](https://github.com/hoaug-tran/ReYogaSMC) to get fan control and other settings, kext version is 2.2.1 at this time, grab matching app version from their releases and update kexts accordingly
>[!Note]
>As per usual with premade EFI's I have scratched my serial number and you'll need to add your own to use apple services. My setup uses the MacBookpro15,2 SMBIOS. This is a basic knowledge thing that you should know how to do
# Credits
- me @klutzyt everywhere
- [the premade t490 efi](https://github.com/5T33Z0/Thinkpad-T490-Hackintosh-OpenCore)
- apple?
