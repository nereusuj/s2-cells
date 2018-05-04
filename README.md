# s2-cells

This plugin will allow you to visualize s2 cells on top of IITC.  You can set two different configurable levels, one which is shown
on the map in a light color (should be higher cell number), and one which is marked in a darker color (should be lower). 

It's ok to set them both to the same.

If you set either of the numbers too high for your current zoom level (so it would cause your browser to freak out for drawing too many squares), we
will try and determine this and not display either of them.

This is just an initial attempt and could still use a lot of work, though I consider it functional and useful at this time.

You can learn more about [Cell Levels](https://github.com/nikolawannabe/s2-cells/blob/master/cell-guidelines.md) if you want.

[Install Current Version to Tampermonkey](https://github.com/nikolawannabe/s2-cells/raw/master/s2-cells.user.js)
