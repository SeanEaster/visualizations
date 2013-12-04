# The Measles-pleth

Dots or placemarkers can quickly crowd a map that's meant to show many discrete events, especially if circular markers are scaled by area. Chloropleths show concentration across a geographic zone, but lose the detail of where events are distributed within them.

The measles-pleth groups overlapping dots into larger circles, and represents each event as a single, small dot. Large circles' area are scaled to the total quantities associated with their underlying dots. This maintains the discrete representation of events, while showing the rough distribution of total quantity. To reduce clutter, this implementation allots the circles three percent of the total area of the map.

Map adapted from Mike Bostock's [tutorial](http://bost.ocks.org/mike/map/); Data via the [Guardian](http://www.theguardian.com/world/datablog/2010/jul/25/wikileaks-afghanistan-data#data) show civilian wounded and killed during 2009.