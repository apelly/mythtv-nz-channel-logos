#NZ DVB-T TV Logos
Lyngsat channel logos are hit and miss at best. Usually miss. And the aspect ratio is all over the place. Googling failed to locate a good set of MythTV channel logos for New Zealand. So I looked around and collected and enhanced some.

I have tweaked the ones that were of any interest that were also too shit to tolerate (most of them). The process was pretty simple. Open in Gimp, add alpha, tweak/enhance if necessary, export to png, resize with ImageMagick.

I originally resized these for Myth using the documented aspect ratio of 132w x 99h or 4:3. It turns out that some themes expect a square logo, so the build script creates these too. The icons are resized with a maximum width of 528 as a compromise to preserve detail in the larger ones, in case they are being scaled up from the documented resolution anywhere. (and they are!) Finally, there is a small transparent border added, because some themes add their own border and it looks unnatural when the theme border touches the logo edge.

#Wanted:
The Edge logo is a bit small and crap.<br>
Better (bigger) TV One + 1 logo. The current one has been enhanced from the website, but still not perfect.<br>
Better TV 3 logos. But the current ones are OK.<br>
<b>Other contributions welcome!</b>

#How-To
checkout and place desired images in /home/mythtv/.mythtv/channels on the backend (for versions >=.27)

Manually link using the channel editor in mythbackend

#Sources
I think this is everything I used. You should be able to find what I started with from here anyway.<br>
###First port of call
http://www.team-mediaportal.com/extensions/tv-channels/new-zealand-dvb-t-tv-channels-logos<br>
Thanks very much, whoever put those together.
###Other icons found and used as replacements
http://www.cuetv.co.nz/files/cuetv-logo.png<br>
http://www.radionz.co.nz/x/logos/national-07d5afadad66d1df81f7013430fbbb33.png<br>
http://www.basefm.co.nz/base09/templates/yougrids_dl/images/metal/logo.png<br>
http://www.parliament.nz/en-nz/features/00NZPHomeNews201305091/recent-changes-to-parliament-tv-access<br>
http://www.four.co.nz/TV/Shows/C4.aspx<br>
http://www.georgefm.co.nz/Portals/0/skins/2014/images/george-logo.png<br>
http://tvnz.co.nz/planit-toolbox/tvnz-logos-3083642<br>
http://images.tvnz.co.nz/tvnz_images/planit/opportunities/week_34/Solid%20Red_ONE.jpg<br>
http://www.lyngsat-logo.com/hires/cc/choice_tv_nz.png<br>
http://www.chineseyearbook.co.nz/product.asp?id=1059<br>
http://images.tvnz.co.nz/tvnz_images/ondemand_shows/CTV8/<br>
http://dannews.co.nz/2012/06/01/new-christian-channel-to-launch-on-freeview/<br>
http://dannews.co.nz/wp-content/uploads/2014/05/fourplusone.jpg
http://www.theedge.co.nz/Portals/0/Skins/2013/images/edge_logo-tv.png?v=3
