Hello, I am DistroHopper39B. I have had an interest in running Linux on NewWorld (>=1998) PowerPC and early Intel Macs (<2012) for a while now, and I've found Debian based Linux distributions to be the most reliable. If I'm bored enough, I will be making a custom distribution designed for these machines (based on Debian sid on PowerPC; or a choice between Debian sid and stable on Intel) with some extra features, including but not limited to:
- Support for G3-G5 machines (with a 64-bit kernel on the G5 machines)
- Custom boot loader allowing a choice between Mac OS X and Linux on boot (on Intel Macs, similar to rEFInd and on PowerPC Macs, similar to first-stage yaboot) along with a graphical and easy to use configurator for said boot loader (available for Mac OS X, Linux, Windows (Intel) and MorphOS (PowerPC))
- Custom Openbox-based desktop similar to LXQt or LXDE
- Custom xorg driver for nvidia on powerpc (based on the old "nv" driver from Ubuntu >= 11.10, since nouveau is unstable, buggy, and doesn't always work on big-endian)
- Custom xorg driver for old ati gpus (<2003) since these don't work in modern linux (corrupted image on screen or xorg refusing to start)
- easy xorg.conf editor and configurator for CRT iMacs/monitors
- Custom sleep/wake kernel module for PowerBooks and iBooks
- Custom battery kernel module for all machines (current battery modules are unreliable on all machines)
- Functional sound on every PowerMac
- Installation from within Mac OS X (no additional media required)
- Traditional \*\.iso installation for CDs and USB media
- Graphical driver managers
- 1-click dual-boot with Mac OS X, MorphOS, and Windows (bootcamp)
- Legacy (Macbian) and EFI (Mac OS X) dual-boot (using Hybrid MBR) for MacBooks with nvidia GPUs (which are unsupported in EFI mode due to unknowns in Apple's old EFI implimentation)
- 1-click WiFi driver installation (b43, b43legacy, bcmwl)

Look, I get it, this is ambitious (especially since I know basically nothing about programming lol), and probably won't turn into anything. However, if anyone is interested, send me a DM on Twitter @DistroHopper39B. 
