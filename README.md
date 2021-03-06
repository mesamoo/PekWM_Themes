Config files and pekwm themes
----------

Goals:
-------------

Clean, consistant look

 - easily distinguish between overlapping windows
 - easily distinguish between active and inactive windows
 - window resizing without fighting to grab edge of window (just right border width)
 - reduce wasted space while retaining readability (designed for
   1920x1080 resolution)
 - 1024x768 pixel resolution versions also available
 - reasonably nice appearance with light or dark gui
 - look nice with or without compositing
 - try to reduce number of fonts required in system
	(fira, or arimo for theme), 
	(hack, and oxygen are used in some other configs)

Additional Goals:
-------------

Clean, well layed out (I hope) configuration files.
hopefully others can easily modify and learn from these files.

(Use a monospace font when editing for easily viewed layout)


AutoProperties:
-------------

PekWM Auto-properties have been used to force some applications to open on specific virtual desktops and to prevent some applications from accidentally being closed.
(Close button removed or replaced with minimize button, especially thunderbird and most web browsers)

Autoproperties are dependent on support in the theme.
If the auto-properties file does not reference a specific decor in the theme, the default decor will be used. 
(all apps will use same decor and open using default config)

> **Note:**
to get most from my pekwm themes your autoproperties file should be modified

AutopropertiesDH... is  my commented example, which will not be updated regularly, only for major changes (Such as adding new decor to theme)

If you choose to use my autoproperties you should review the modified properties first, specifically:

> - thunderbird mail, no close button, (minimize only)
> - email clients open on virt desktop 2
> - most web browsers open on own virt desktop
> - web browsers have no close button, (minimize only)
> - a few other misc tunings
> 
for me, autoproperties is a challenge, usually it works as expected occasionally it does not do what I expect.

----------


**Important**
-------------------

These themes were originally designed using a monitor resolution of 1920x1084. Some editting may be required for the lower resolution versions of the themes. 

(Adjust font sizes, modify title height, etc.

Lower Resolution versions (not fully tested) are in directories ending with 768
These "should" play nicely with 1027x768 screen resolutions

Thanks:
-------------

Ideas, learned from, and  some graphics taken from:

 - semitif
 - NeoMotif
 - Gulfstream
 - GreenBars
 - Magni
 - magic night
 - playbillblue
 - AxonKolors

**Special thanks to urukrama for showing PekWM's potential**
 
 .