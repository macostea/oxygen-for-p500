# Version 0.a - 30 oct 2011 #
  * 32 kernel

**_Known bugs:_**
  * Bluetooth does not always work
  * Weird green line on top side of youtube HQ videos (OMX problem)
  * Sometimes after you input pin number might ask for network unlock code. Just hit dismiss **fixed**
  * Crash in Settings->Status bar->Widget buttons order **fixed**
  * Screenshot feature does not yet work. No framework support **fixed**
  * Cpu and Status Bar icons are too big **fixed**
  * Blackscreen bug with other kernels **fixed**
  * No FM radio **fixed**
  * No video recording
  * Word suggestions don't work with stock keyboard - I replaced LatinIME with many versions... all seem to correct common mistakes like hell -> he'll well -> we'll but nothing else... so i don't think it's a bug **Update: found dictionary... fixed**
  * Spare parts crash on battery history **fixed**

# Version 0.a2 - 2 nov 2011 #

  * Tested gbs kernel but got big battery drain -> reverted to old kernel
  * Fixed contacts syncing with facebook (maybe the problem with vcards too)
  * Added GAPPS in zip -> no need to flash GAPPS from website or rom manager
  * Added APN list

**_Known bugs:_**
  * Bluetooth does not work so FM radio does not work either (use Spirit) **FINALLY FIXED! this one was really bugging me...**
  * Green line on top side of youtube hq videos
  * No video recording

# Version 0.b (from bluetooth i guess  ) - 9 nov 2011 #
  * Kept old kernel
  * Added Live Wallpapers (forgot to add it in build config)

**_Known bugs:_**
  * Green line on top side of youtube hq videos **fixed**
  * No video recording - wtf? **fixed**

# Version 1.0 - 13 nov 2011 #
  * Added tethering (forgot to add it in build config) -> needs testing

**_Known bugs:_**
  * Tethering does not work **fixed**
  * Location by Wifi or GSM does not work **fixed**
  * Poor quality radio buttons

# Version 1.1 - 14 nov 2011 #
  * Changed kernel to gbs v19 cfs
  * Added mod version

**_Known bugs:_**
  * Poor quality radio buttons
  * Bad sound quality on bluetooth headset needs testing
  * A2SD problems **probably fixed ->needs testing
  * GPS icon does not show on second toggle**

# Version 2.0 a - 22 nov 2011 #
  * Changed kernel to franco .v1.1 (.35)
  * Switched to oxygen 2.3.2
  * Very fast

**_Known bugs:_**
  * Poor quality radio buttons
  * Bad sound quality on bluetooth headset
  * GPS icon does not show on second toggle
  * Occasional blackscreen bug

# Version 2.0 b - 6 dec 2011 #
  * Tried to fix blackscreen bug -> no blackscreen with live wallpaper guaranteed (even with electronbeam)
  * Small performance tweaks
  * New bluetooth drivers
  * Added SIP calls
  * Manual network selection fix
  * Fixed battery drain

**_Known bugs:_**
  * Poor quality radio buttons **fixed**
  * Bad sound quality on bluetooth headset needs testing
  * GPS does not work on second toggle **fixed**
  * Blackscreen bug with static wallpaper... Use live wallpaper!

# Version 2.1 - 25 dec 2011 #
  * Even newer bluetooth drivers...
**_Known bugs:_**
  * Bad sound quality on bluetooth headset
  * Blackscreen bug with static wallpaper... Use live wallpaper! **fixed**

# Version 2.2 - 31 jan 2012 #
  * Build based on new cyanogenmod source
  * New baseband
  * CM kernel
**_Known bugs:_**
  * Well none so far...

# Version 2.3 - 6 feb 2012 #
  * Data fix from cyanogenmod
  * New kernel with no blackscreen and all other features working

# Version 2.4 - 8 feb 2012 #
  * 2G/3G data toggle issue fix
  * BT headset fix attempt
  * Swipe to clear notifications tweaked

# Version 2.5 - 19 feb 2012 #
  * BT headset fixed + bt sleep settings fixed
  * Now using wpa\_supplicant 6 and fixed ad-hoc networks

# Version 2.5.1 - 20 feb 2012 #
  * BT headset fixed for real

# Version 2.6 - 4 mar 2012 #
  * Fixed offline charging
  * Fixed 2G/3G toggle (needs testing)
  * Added On The Hunt notification sound
  * Added support for no-mic headset

# Version 2.7 - 5 apr 2012 #
  * Fixed video recording delay bug
  * Switched to higher quality alarm icon in status bar
  * Added opengles support in build.prop
  * Fixed notification sounds when using headphones
  * Added correct baseband support (now it's showing gibberish)

# Version 2.8 - 19 may 2012 #

  * Fixed camera (both camcorder and autofocus and all features work)
  * Fixed charger mode
  * Fixed audio routing
  * Switched to new ril (hopefully fixed data and APN issues)
  * Baseband shows correct string now
  * Fixed Digitel Venezuela APN


---

# Oxygen 3 (ICS) #

# Version 0.1.2 - 14 aug 2012 #

  * First ICS public release
  * No electronbeam
  * No tethering
  * No stock live wallpapers
  * No bluetooth pairing

# Version 0.2.0 - 17 aug 2012 #

  * Fixed APN list
  * 2G/3G selection fixed
  * Manual network search fixed
  * Stock live wallpapers fixed

# Version 0.3.3 - 19 aug 2012 #

  * Tethering fixed (needs testing);
  * Electronbeam animation now working;
  * Airplane mode reboot fixed;
  * Battery seems to drain less;
  * Added initlogo;
  * Wireless location works;
  * Bluetooth now works with no problems

# Version 0.3.4 - 19 aug 2012 #

  * Fix mobile data screwup

# Version 0.3.5 - 30 aug 2012 #

  * Fix power on phone (disable charger mode)

# Version 0.3.6 - 4 sep 2012 #

  * Updated OTAUpdater
  * Added OTAUpdater to Settings and remove it from the Launcher
  * Removed serial number from Settings
  * Downgraded Voice Search to version 2.1.4
  * Removed some unused files from GApps

# Version 0.4.0 - 8 sep 2012 #

  * Fixed panorama mode (very slow though)
  * Fixed ringtone issue

# Version 1.0.0 - 13 oct 2012 #

  * Fixed white screen in Webkit (Gmail, Facebook, Instagram, etc...)
  * Fixed audio routing of notifications
  * Fixed headset with no mic

# Version 1.1.0 - 6 nov 2012 #

  * Fixed Youtube HQ playback (video playback in gallery still does not work)
  * Fixed status bar not closing after long press on power widget
  * Fixed and updated OTA Updater