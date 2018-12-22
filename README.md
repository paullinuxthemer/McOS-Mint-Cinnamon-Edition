# McOS-Mint-Cinnamon-Edition
A specially design version of McOS for the **Linux Mint Cinnamon 19.**

## new:

Version 2.0 has many improvements, such as a new metacity-theme and dark theme, blue accent in the comboboxes,...

This should also work in any distro with cinnamon-version. (This is developed in Manjaro Cinnamon)

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

This theme is also provided in [Gnome-look.org](https://www.opendesktop.org/p/1247470/)

![s](https://cn.opendesktop.org/img/4/6/2/c/c8d712b27bf7b95cc75544bf22295e15561b.jpg)
