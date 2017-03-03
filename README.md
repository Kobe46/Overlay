# RetroArch Overlay injection

This is a hakchi/hakchi2 module which will add Overlays into the default folder location for overlays:
"~/.config/retroarch/overlay". This is to mitigate people from resyncing retroarch even though it is installed, so that overlays can be placed into the default folder without the need of resyncing RetroArch.

# What are Overlays?


RetroArch supports overlay images for use with hardware accelerated drivers. The purpose of this is to allow some kind of input interface that is mouse/touch oriented.
The overlay images are displayed with transparency over the regular game image, and the user is able to trigger input by pressing on certain parts of the overlay.
Since the overlay is a series of images, the user should be able to fully configure the look and functionality of this overlay. This allows skinners and themers to go wild.

In this aspect, these are borders or bezels that can be placed around the video image.

Example of these overlays in action.

Playlist:
https://www.youtube.com/watch?v=r4RoiChxsgQ&list=PL3KJBrqmANQ6GzgHDdn4B9ER6LFXTLHcy



# *This Module is to be used after installing RetroArch

# Installation:

1.	Copy Overlay.hmod folder into your user_mods folder in Hakchi.
		
2.	Inside Overlay.hmod folder is a overlay folder, please copy overlays into this folder. You should copy the .cfg and .png file
		For example: SNES.cfg and SNES.PNG should be both placed in the overlay folder
	
3.	Open Hakchi > Modules > Install extra modules. Now select overlay. Cick OK.
		
4.	Follow instructions to synchronize the module to NES Classic.
		
5.	Once completed you should now have injected all the overlay files that were placed in the overlay folder.


# Selecting Overlay in RetroArch:
		
1.  Turn on NES Classic.

2.  Select a game you wish to play using Retroarch

3.  Once the game has loaded, hit (Default) Start+Select to open Retro Arch GUI menu. *If not Start+Select, use which ever binding your configuration was setup for.

4.  Go to Settings > Onscreen Display > Onscreen Overlay > Overlay Preset. Once in here you should now see all of the .cfg and .png files that were placed in overlay folder.

5.  Make sure "Display Overlay" option is set to ON. It is your choice to have "Hide Overlay In Menu" turned ON/OFF. You can also change the Opacity to make sure it fills or covers the borders.

6.  Select one of the .cfg files corresponding to the overlay you wish to use. Example: SNES.cfg is selected, not the .png.

7.  Once you have selected the .cfg, hit B button on controller to go back. Then hit (Default) Start+Select to resume the game.

8.  You should now see the Overlay Border you selected.

9.  If the Video does not seem to fit in the right location, you will need to change the Video settings to fit what is needed.
For example: 

      Settings > Video

      Aspect Ratio Index - Custom

      Custom Viewport X - 281

      Custom Viewport Y - 27

      Custom Viewport Width - 1356

      Custom Viewport Height - 1012

      Window Scale - 5.0X

      Integer Scale - Off

Please let me know if there are any issues with this module.


# Thank Yous

Using the template model provided by PCM720

I would like to thank ClusterM, Madmonkey1907, PCM720 for their great work and additions to be able to even do this.

Thanks to nosh01 for the original overlays.

Thanks to the GBATemp and Reddit community for assisting those that needed help when needed.

-Kobe46
