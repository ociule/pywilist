# PyWiList

PyWiList is a Python wrapper for the iwlist utility. If you want to implement a Kismet or Wifi-Radar clone in Python, it will interface with iwlist, read and parse the data for you.

## Status

Beta, in development. If anyone is interested in dev/maintaining it, contact me.

## Needs

    * testing.
    * more testing - with unittests.
    * a bit of refactoring to return results properly as objects.
    * could be extended into a Python wrapper for all iw tools. This would provide a complete back-end for a Wifi-Manager type of tool. 

## Rationale

Why not reuse Wifi-Radar's back-end ? It is written in Python after all. Because it is not object oriented (as of Nov 2007) or separated from Wifi-Radar, so it is a bit hard to reuse. Plus, my wifi net connection was down and I had nothing to do. 
