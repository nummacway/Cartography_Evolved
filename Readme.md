*Cartography Evolved* is a Texmod for the game Guild Wars, aiming to make the cartographer titles easier.

Created by Redeemer (numma_cway) from GuildWiki.de.

See the [wiki page](https://wiki.guildwars.com/wiki/User:Numma_cway/Carto) for more info and download packages.


# License

The map textures (the _Map_ layer in the Affinity files and all exported PNGs) are Copyright © ArenaNet and NCsoft. GuildWiki.de joined ArenaNet's Community Fansite Program, which is believed to cover the use of the map textures in this project. If you redistribute ArenaNet property, please make sure that you are allowed to do so.

My work on this mod (all layers in the Affinity files, except for the _Map_ layer) is licensed under GNU-AGPLv3. Among other things, this means that if you release a Texmod or web viewer derived from this one, you *must* make the source files (Affinity files) available.


# Build Process

To work on this mod, you'll need Affinity. As of the original release, the files in this repo are Affinity Designer v1 files, so you can use whatever Affinity version you like, but Affinity only became freeware in v3.

To export a map after updating it:

1. Set Affinity to _Export Persona_
2. Go to _Slices_ panel (by default, this panel shares its space with the _Layers_ panel)
3. Click _Export Slices_ to export the slices for the "2x" version with grid and navmesh
4. Save (try to not save after the following steps)
5. Go back to _Vector Persona_ and hide the layers called _Navmeshes_ and _Grid_
6. Select all slices and set the _Export Preset_ to _Single PNG_, and set _Recalculation_ to _Bilinear_
7. Click _Export Slices_ to export the slices for the "clean" version for use with Texmod
8. Optional: Run a lossless PNG optimizer of your choice. I use `pingo` with `-s0` to `-s9` arguments.

You can then build the mod from the supplied `.log` file using Texmod. It should say that 285 files were added. From my experience, the first build after starting Texmod always fails – Texmod claims that the build had succeeded, but produces an invalid `.tpf` file.


# Notes

The navmesh images are not part of this project and PSDs will be provided on request. Note that the navmesh project uses German names.
