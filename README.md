Windows Native Guifications Themes
==================================

A set of native Windows notification styles to use with [Guifications](https://www.guifications.org/projects/gf2) for [Pidgin IM](http://pidgin.im/)

V1.2 By [BoffinbraiN](http://boffinbrain.deviantart.com)

![Screenshots](https://i.imgur.com/rMvDpqO.png)

Medium-sized notifications with avatar on left, statuses and protocol icons at bottom, with detailed two or three-line messages.  Supports all notification types, including new e-mail notifications. Source files and images included.

- Windows XP: Classic (Windows 2000), Blue, Silver, Olive, Royale Blue (Media Center), Royale Noir (Zune)
- Windows Vista + 7: Black, Blue, Green, Grey, Ice, Orange, Red, White
- Windows 8 + 10: Black, Blue, Green, Grey, Orange, Purple, Red, Teal, Yellow


Introduction
------------

Thanks for trying these themes.  I hope you find them beautiful and massively useful.

I have very high standards, and I'm very proud to use these themes on a daily basis.  I would certainly hope you don't find any faults in my work!  But, if you do, then I welcome your feedback either on the submission page on [DeviantArt](http://boffinbrain.deviantart.com/art/Windows-Native-Guifications-Themes-284407004), as a comment the [SourceForge tracker](http://sourceforge.net/p/guifications/themes/146/), or on [GitHub](https://github.com/BoffinbraiN/windows-guification-themes).


Installation
------------

Every Guifications theme is located in the Themes directory inside your Pidgin user directory.  To get there, browse to:

- Windows XP: `C:\Documents and Settings\your-username-here\Application Data\.purple\guifications\themes`
- Windows Vista and up: `C:\Users\your-username-here\AppData\Roaming\.purple\guifications\themes`

If you've just installed Pidgin or Guifications, make sure it is running and the plugin is enabled, otherwise the directory may not exist yet.

Extract the 'themes' directory from this archive and move all the contents there, so that all the theme names are visible under 'themes'.

Then, just go to the Guifications options window via the Plugins window, to see the list of available themes (refresh if the window is already open).  Unless you want to do advanced per-user theming, make sure only one theme is enabled - this will make sure the correct one is used.

One final note: these themes have only been tested on Windows. The Windows 10 themes reference the Segoe UI font, which probably won't exist on Linux distributions.


Customisation
-------------

Need to fine-tune your own colour scheme, or add other personal touches?  I've given you all the files you need to get started!  They're in the `source` directory.

Every theme file is derived from one of three theme XML files.  The layouts for all Windows XP and Windows 7 themes are the same; only the text colours change.  Select the most suitable one based upon the average brightness of the background image:

- Light: black headings, dark grey text
- Mid: white headings, black text
- Dark: white headings, light grey text
- Win10: same as dark, but with more padding

All images are made from pages and layers in the source.png file - an Adobe Fireworks CS3 file.  If you have Fireworks, you can modify layers and export to make a derivative theme. The Windows 10 images are not provided in the source because they are literally flat colours - you can alter an existing background in Paint or any other program.

Be careful with transparency - it looks like any alpha value that is less than 100% is rendered completely transparent by Windows, and for that reason, none of my themes use translucent backgrounds.  If you know why, or better still, have a workaround, let me know!


Version History
---------------

- V1.0 2012-02-11 - Initial release with 6 themes for Windows XP and 8 colours for Windows Vista and 7.
- V1.1 2015-08-25 - No changes to existing themes, but added 9 flat colour themes for Windows 8 and 10.
- V1.2 2017-02-08 - Updated Win10 themes to workaround the Guifications slide animation glitch.