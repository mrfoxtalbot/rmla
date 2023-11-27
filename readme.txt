=== Restrict Media Library Access ===
Contributors: mrfoxtalbot
Tags: media library, users, roles, visibility
Requires at least: 4.0
Tested up to: 6.3.2
Stable tag: trunk
License: GPLv2 or later

Restricts access for Authors and Contributors so they can only see their own Media Library uploads.

== Description ==
This plugin restricts access for Authors and Contributors so they can only see their own Media Library uploads. 

This has two main uses: Make it easier for Authors to locate their own uploads when Media Libraries grow very big and prevent Authors from using or downloading media that belongs to other users. 

Admins and Editors will still be able to see everyone's uploads. 

== Installation ==
1. Visit Plugins > Add New
2. Search for 'Restrict Media Library Access'
3. Activate Restrict Media Library Access from your Plugins page.
4. That's all!. After activating the plugin Authors and Contributors will only be able to see their own uploads.

== Changelog ==
= 1.0 =
First release
= 1.1 =
Add filter to also restrict access on the list view.
= 1.2 =
Fixes fatal error in frontend caused by get_current_screen being unavailable
= 1.3 = 
Fixes warnings due to the "screen" variable being undefined in some scenarios
= 1.4 = 
Fix error in readme.txt to allow localisation. Added header banner asset.