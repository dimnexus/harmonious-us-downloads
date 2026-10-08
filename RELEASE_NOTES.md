# Harmonious Us 0.6.2-alpha — Shape the world (select alpha testing)

Build 62, channel alpha, **protocol 3**. Servers of this build accept clients from 0.6.2-alpha: **a 0.6.1-alpha game must update** (the launcher does it; the game says so if you try to join).

This build is for the selected alpha testers it was handed to. It is not generally available yet.

## In short

- Everything you could do alone you can now do on a server: fish, dig, shovel snow, read the map, search ruins, follow objectives, and farm properly.
- The shovel was reworked. Left button digs, right button fills with the material you choose. Holes can be filled level again. Snow clears in a patch under the shovel, not across the landscape.
- You can pour water into a hollow you dug, and it stays there as water.
- Grass no longer grows through planters, crop plots, barrels or anything else you place.

## The shovel: dig, fill, shape

- **Left button digs.** A bite about a metre across and a hand deep. Several make a hole, a trench or a basement. You get what the ground is made of: dirt, clay, sand, stone, ore.
- **Right button fills** with the material shown on the prompt. In a hole the fill stops at the land's own level, so a few shovelfuls bring the ground back flat. On level ground it makes a low heap.
- **R changes the material**: Dirt, Clay, Sand, Stone, Snow, Water. What you put down is what is there afterwards: clay is clay, and stone needs a pickaxe to dig again.
- **Right button puts back what you dug.** If you carry none of the chosen material, the shovel takes the ground you do carry (the clay you just dug out, say).
- **Water**: with Water chosen, the right button pours what you carry into a hollow. It lies there as a still pond at one level, a little below the lowest edge of ground that holds it. Snow on the land around a hole has no part in it: the water sits in the ground, under the snow's top. A hollow holds only what it can; level ground holds none.
- **Snow**: the left button on snow lifts the patch under the shovel and throws it a step to the right of the way you are working, where it stands as a pile. Nothing around it is touched. With Snow chosen, the right button moves a scoop from beside you to where you aim.
- A shovelled path stays clear for a while under new snowfall and then slowly fills.
- Fill never goes into something that is built, and you cannot dig the ground out from under it.
- On a server all of this is the server's: everyone sees the same hole, the same fill, the same pond, the same path, and it is all still there after a restart.

## Now on a server too

- **Fishing.** Hold the Fishing Rod, right click fresh water to cast, right click the bobber when it dips. The fish are the server's own, and each one is caught once. The line now leaves the tip of the rod, in first and third person, and other players are seen holding their rod with their line on its tip.
- **The map (M).** Your own map of the planet you are on, uncovered as you travel. Right click to add a marker. Your map and markers are yours alone and are kept by the server.
- **Ruins and field notes.** Search a ruin's terminal with E: research points, salvage and sometimes a blueprint that halves a technology's cost. Each player can search each ruin once. The logs can be read again in the Journal.
- **Objectives.** A new character gets short objectives for the online game, one at a time, in the top left. They complete from what you actually do. Hide or show them from the Journal. Characters from before 0.6.2 start with them hidden.
- **Farming.** The Crop Plot is now a real crop: plant Seeds with E, water it, water it again half way, then harvest food and seeds. Fertilizer and fertile ground speed it up. A rain barrel or other water piece with water in it close by waters it for you. Other players can water your crop; the harvest is yours unless you let them in.

### If you played 0.6.1

Nothing you have is lost. Your pack, research, professions, buildings and the world's animals are as they were. Crop plots built before now need Agriculture to build new ones: if you already own plots you are given Agriculture once, on your first join. Anything that was stored in an old plot is collected from it with E.

## Building

- Anything you place on the ground owns its footprint. Grass, flowers, small stones and bushes do not stand or grow back inside it, and the vegetation around it is left alone.
- A free-standing piece can no longer be placed inside a tree or a rock.
- When you take a piece down, its patch of ground is free again and regrows the next time you come back to it.

## Known limits

- Planting wild species from collected seeds, spores and cuttings is still solo only.
- Poured water is still water. It does not flow, and it does not yet fill tunnels and caves, only open hollows.
- Placing building pieces down inside a dug pit is not supported yet. Digging and filling around buildings is.
- Field notes for merely sighting an animal are solo only. Catching and harvesting a species for the first time gives its notes online.
- The crouch is a pose laid over the walk, not its own animation.
- The Linux client's window fitting has not been run on a Linux desktop.

`Docs/SOLO_ONLINE_PARITY.md` in the source has the full solo-against-online table.

The dedicated server is not a public download.
