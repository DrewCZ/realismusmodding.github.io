---
title: Seasons Mask
tags: [modding, maps]
keywords: guide, modding, maps
last_updated: 2017-06-07 22:16:15 +0100
summary: ""
ref: maps_seasons_mask
permalink: /mods/seasons/manual/modding/maps/seasons-mask
---

 # Seasons Mask
The snow mask will keep snow from falling inside sheds, houses, rivers and on model roads. The snow mask is also used to determine if an object is ‘inside’ our ‘outside’, for example with bales and vehicles. It is important that you supply a snow mask so that Seasons can use snow up to 0.5 meter (It will otherwise default to 0.06m. See the F.A.Q.) The mask is a new foliage layer named ssSnowMask. Everywhere you paint it, snow will not stay on ground. There are also some other layers that we use for other purposes or for the future.
Map mod to work with Season correctly, must be prepared for using Snow mask, then create Snow mask in Giants Editor, and reconfigure it for using in game. This steps are middle dificulty and you need basic experiences how to edit i3d file and work with Giants editor. How to do it is described here:
1. Preparing map mod
1.1 Download following files: 
1.2 Put downloaded files into your map01 folder (path example: \yourMapModeName\maps\map01\herePutFiles)
1.3 Open i3d file of your map (example: \yourMapModeName\maps\map01\map01.i3d) in text editor (Notepad, better is Notepad++)
1.3.1 Find <Files> and insert under it two lines:

