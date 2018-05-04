# s2-cells

This plugin will allow you to visualize [s2 cells](https://pokemongohub.net/post/article/comprehensive-guide-s2-cells-pokemon-go/) on top of [IITC](iitc.me).  You can set two different configurable levels, one which is shown
on the map in a light color (should be higher cell number), and one which is marked in a darker color (should be lower). 

It's ok to set them both to the same.

If you set either of the numbers too high for your current zoom level (so it would cause your browser to freak out for drawing too many squares), we will try and determine this and not display either of them.

This is just an initial attempt and could still use a lot of work, though I consider it functional and useful enough at this time.  It's probably not going to crash/freeze your browser/tab, unless you have a huge screen.

You can learn more about [Cell Levels](https://github.com/nikolawannabe/s2-cells/blob/master/cell-guidelines.md) if you want.

This info is based largely on info from Reddit's [TheSilphRoad](https://www.reddit.com/r/TheSilphRoad), [OpenStreetMaps](openstreetmap.org), [overpass turbo](http://overpass-turbo.eu/), and simply testing by creating new portals to find out what happens.

With thanks and credit to all who have come before, including original l17 plugin submitter [vibrunazo](https://github.com/vibrunazo) and quality PR by [Dragonsangel](https://github.com/Dragonsangel).

![Configuration](https://github.com/nikolawannabe/s2-cells/blob/master/config.png?raw=true)

![Visualization](https://github.com/nikolawannabe/s2-cells/blob/master/s2-cells.png?raw=true)

[Install Current Version to IITC](https://github.com/nikolawannabe/s2-cells/raw/master/s2-cells.user.js)
