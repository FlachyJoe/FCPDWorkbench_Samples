# fcpd-animator Record and play animation in FreeCAD.

This utility run in Pure-Data throw the [FCPDWorkbench](https://github.com/FlachyJoe/FCPDWorkbench).

## Requirements
In addition to FCPD requirements, fcpd-animator needs *iemguts* and *zexy* by [IEM](https://git.iem.at/pd)

## Usage
### Launch
1. Start FreeCAD
2. Load the FCPDWorkbench
3. Click the `Launch PureData` button
4. Open fcpd-animator.pd

### Record
The recorder is based on a keyframe system :
1. Select the FreeCAD objects to animate
2. Click `Add Selection` in fcpd-animator
3. Click `First` to set the initial object's placements
4. Move objects where you want
5. Adjust animation duration if needed
6. Click `New`
7. Go to 4. until all object's waypoints are set

### Play
1. click `Play`
2. Enjoy !

## Feedback

Bugs, feature requests, and inquiries ? Please open tickets in the repo's issue queue.

## License

Copyright 2020 @flachyjoe and other contributors

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
