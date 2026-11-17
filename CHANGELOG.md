# Changelog

## 1.0.5

Works with KSA build version 2026.11.16.5901 and needs it. KSA 2026.11.16.5901 moved the minimum throttle and the minimum pulse time of an engine from the combustion chamber to the rocket, so with Facet 1.0.4 the Alcor Kick Engine and the Facet RCS Pod did not load. These values are now in the new place and are the same as before. The game also corrected the density of MMH: the Facet Voyager Tank now holds about 414 kg instead of 300 kg and each RCS Pod about 11 kg instead of 8 kg, so Facet Voyager has about 3,500 m/s instead of about 2,900 m/s. Part Ids, shapes, colliders, masses and saved vehicles are the same as in 1.0.4. This version does not load on older KSA builds; use 1.0.4 there.

## 1.0.4

Fixes flickering faces on some parts, validated against KSA build version 2026.11.10.5801. The mounting faces of the Camera Pod, the Horn Antenna, the Patch Antenna, the Star Tracker and the root plate of Wing 2 and Wing 3 had no texture area, so the game could not shade them and they showed changing noise when a part was turned on its mount point. These faces now have their own small texture area with the plain back of the plate. Two corner faces and the radiator plate of the Eye Imager and the narrow rings in the bolt seats of the Cube Adapter had texture coordinates on a line; they now have a real texture area too. Only the meshes and the textures of these faces changed: part Ids, shapes, colliders, masses and saved vehicles are the same as in 1.0.3.

## 1.0.3

The foil and cloth variants of the Facet Bus, the Battery Pack and the Eye Imager now look like different parts, validated against KSA build version 2026.11.10.5801. Before, these variants changed only one small sheet on one face. Now a gold foil (B) or white beta cloth (C) blanket covers most of each side face of the Bus and the Battery Pack, with cut-outs for the radiator, the sensor window, the connectors and the wing fittings. Imager B has foil on its tube and on three faces of its mount. The blankets lie flat enough that wings and small parts still fit on the faces. Part Ids, shapes of the bare parts, colliders, masses and saved vehicles are the same as in 1.0.2. The Rack, the Adapter, the Voyager Tank and the cube satellites are unchanged.

## 1.0.2

New gold foil and silver tank blanket, validated against KSA build version 2026.11.10.5801. The foil was a dark sheet with one highlight. It now lies over rails, ribs and straps as a real blanket does, so it has many folds that catch the sun and reads as foil from every side. Part Ids, shapes of the bare parts, masses and saved vehicles are the same as in 1.0.1.

## 1.0.1

New materials for all hardware parts, validated against KSA build version 2026.11.10.5801. The parts were dark in orbit, because bare metal showed only one highlight. Bare aluminium is now a lighter satin metal, large black anodised faces are clear anodised or dark grey metal, and the dish, the patch antenna and the backs of the solar wings are white. The Bus, the Battery Pack, the Rack and the antennas have more surface relief. The solar cells of the wings and the cube satellites are glossy cover glass with a tone per cell. Only textures changed: part Ids, shapes, masses and saved vehicles are the same as in 1.0.0. The foil and cloth finishes are unchanged.

## 1.0.0

First release, validated against KSA build version 2026.11.10.5801: rideshare rack and adapter, cube satellites 3U, 6U and 12U, Bus, Battery Pack, solar wings, RCS Pod, instruments, antennas, dish, science boom, Voyager Tank and the Alcor kick engine. Rack, Adapter, Bus and Battery in bare, gold foil and white cloth finishes; Imager and Voyager Tank also with foil.
