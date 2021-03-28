# Future Updates: MYTV Broadcasting channels / Astro Channels
XMLTV ID will be changed to channel numbers (for example, if you want the guide to TV1, you have to change tvg-id="TV1" to tvg-id="101").

# epg
Pre-built XMLTV EPG for channels, updated every 7 days. Generated manually.
**This project didn't contain any IPTV links.** Here are some free IPTV projects:

https://t.me/s/helpfreeviewinfo (Official links to Malaysia / Singapore / Brunei channels and some other channels)

You can also view XMLTV files using [Ian Bishop's EPG Viewer](http://xmltvview.birtles.org.uk/epgviewer.html) (Open Source) by downloading it and opening it on this application.

# Upcoming

Nothing

**Use the Compressed option to save data and time on importing XMLTV.**

![](https://img.shields.io/github/issues/weareblahs/epg "that one issue counter")
# New Channels on the provider?

I only monitor Astro channels (because I actually own an Astro STB). Special Channels are added at the period (such as Stay Home Concert is added on the guide from April 14 to June 9).

If theres new channels added to the other providers, [Submit an issue here and tag it "New Channel"](https://github.com/weareblahs/epg/issues/new). I'll check it weekly (or daily if I can).

# How to use
1. Get your M3U file ready

2. Find the line which looks like this (the line below is an example):

`#EXTINF:-1 tvg-logo="https://astrocontent.s3.amazonaws.com/Images/ChannelLogo/Pos/101_300.png" ,TV1`

3. Add the channel ID like the format below after #EXTINF: -1:

`tvg-id="[XMLTV ID HERE]" `

Here's an example:

`#EXTINF:-1 tvg-id="TV1" tvg-logo="https://astrocontent.s3.amazonaws.com/Images/ChannelLogo/Pos/101_300.png" ,TV1`

4. Add more like this as you want on the channels.

5. Save it.

### How to import XMLTV with Guide

Here are some instructions for some IPTV clients:

Kodi (PVR IPTV Simple Client)

1. Open the settings of PVR IPTV Simple Client (Settings > Add-ons > My Add-ons > PVR Clients > PVR IPTV Simple Client > Settings).

2. Go to "EPG Settings".

3. Enter the URL at the table below.

4. Select "OK".

5. Restart Kodi.




# Available channels and links

[See Channel list and XMLTV IDs here](https://github.com/weareblahs/epg/blob/master/misc/channel_list.md)

Malaysia Freeview XMLTV (also known as myFreeview, available channels were free-to-air channels only / Radio included)
||  |
|--|--|
|Link|https://weareblahs.github.io/epg/MY-Freeview.xml (XMLTV) / https://weareblahs.github.io/epg/MY-Freeview.xml.gz (Compressed)|


Guide for Astro channels
||  |
|--|--|
|Link |https://weareblahs.github.io/epg/MY_Astro.xml (XMLTV) / https://weareblahs.github.io/epg/MY_Astro.xml.gz (Compressed) | 
