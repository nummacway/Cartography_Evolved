## 0xd4850245
This is the map fog. The default one makes it hard to know what has been explored due to massive smoothing.
- Left: Unexplored
- Right: Explored
- Opaque: Show hi-res-map
- Transparent: Show low-res map
(Color does not matter.)

## 0x67ce6d98
This is the map frame. The default one impacts usability of the map in Pre-Searing, especially the Northern edge of The Northlands.
- Top: Used in any location with no actual map
- Bottom: Like 64px into the map
- White: Show black
- Black: Transparent
(It shouldn't be fully black because viewing a small map like Pre-Searing would retain the last 3D-rendered image around the actual map.)
Software has issues with this file's format (content is shifted by 4 pixels), so the file was modified using a hex editor.