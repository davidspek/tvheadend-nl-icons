# tvheadend-nl-icons
Channel icons from Ziggo for Tvheadend

This repository contains icons for ziggo television channels (and some radio stations) for use with [TVheadend](https://tvheadend.org).

These files were obtained directly from the ziggo website. The exception are a few of the regional channels for The Hague. The original SVG's and the converted PNG's are provided.


## Usage

Copy the files from the png folder to the icon folder used by tvheadend. I have mine in /config/tv-logos/. 
    
Configure TVheadend to look in the icons directoy by going to "Configuration -> General -> Base" and setting "Channel icon path" to `file:///config/tv-logos/%c.png`, and the channel icon name scheme to `All lower-case`

All files have been named so they are recognized for the channel names accuired from ziggo. No manual editing of the user icon path should be necassary. 

I do not own the rights to these icons and they might be subject to copyright.
