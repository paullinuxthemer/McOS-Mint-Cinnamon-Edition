# McOS-Mint-Cinnamon-Edition
A specially design version of McOS for the **Linux Mint Cinnamon 19.**

This is a totally re-engineered version of [McOS-MJV](https://www.opendesktop.org/p/1241688/) for the Linux Mint Cinnamon 19 desktop. 

Since it finally supports gtk 3.20+ (hello, we have been here for a few years already?) I thought I could give it a shot.

This has proven to be a much more difficult thing to do, because of the way Linux Mint uses Muffin as a window-manager, which has some drawbacks (like: Server-Side-Decoration, so no transparency in Nemo, ) and the 'multitude' of toolbars that take half the real-estate of the window... Reducing the size of them was my first priority.  

Next building a metacity-theme that blends with the rest of the UI.  I managed to create one that follows the theme.  So with applications like X-viewer, X-player, DarkTable, Mpv-videoplayer, Cheese or Totem-mediaplayer you **automatically get the dark theme with dark metacity titlebar. Or you can enable dark-mode on certain apps like the terminal.**

Next, for certain apps (like the calculator or Lollypop-music player) CSD is used for drawing the titlebar (and buttons). So here too, there is **support for dark-mode in CSD**. 

Nemo, the filemanager has been tweaked so it resembles (a bit) the MacOS-finder. In the screenshot Nemo's menubar is hidden. 

## How to:

Download and extract the file to your '.themes'-folder (make one if you have not done so already)

Open System Settings/Appearance/themes and choose the theme in the window-borders and Controls. 

## Issues:

Well there are small issues that needs to be addressed, but for a first draft it is stable. Next, the dark theme is provided but needs attention.  

## Note:  there is no Cinnamon-theme provided. 

Please rate, comment, make suggestions !

https://cn.pling.com/img/9/e/7/e/7184c88b809d94f3a0405d6b6a9baccd01bf.jpg

