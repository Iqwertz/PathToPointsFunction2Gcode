# PathToPoints
SVG Paths to array of points - https://shinao.github.io/PathToPoints/
Fork by Iqwertz to easier export paths for functions to gcode.
Extract points from SVG paths or generate them from a text.

Text svg can be generated here: https://jvolker.github.io/single-line-font-renderer/ 

### Capacities
You can either get each path array of points seperately each differentiated by a color or all of them at the end of the tabs.
<p align="center">
<img src="/docs/preview_get_all_points.png">
</p>
The paths are then scaled and reposition as most as possible to the center of the screen.<br>
Each line correpond to a point, the x and y axis are separated by a comma. Each paths are separated by a #.

### Notes
It is possible that the paths drawn are weird looking or cannot be seen. This app only takes paths into account, any rotation, transform and other attributes are ignored. Nevertheless the array of points given should be accurate.
