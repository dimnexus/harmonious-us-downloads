# Harmonious Us 0.6.1-alpha — The server's world (select alpha testing)

Build 61, channel alpha, **protocol 2**. Servers of this build accept clients from 0.6.1-alpha: **a 0.6.0-alpha game must update** (the launcher does it; the game says so if you try to join).

This build is for the selected alpha testers it was handed to. It is not generally available yet.

## In short

- On a server the Tab panel now has all seven pages of a solo game: Pack, Craft, Research, Professions, Settlement, Planet, Journal.
- Research and professions are real on a server: they belong to your character there, and they decide what you can make and how well.
- The animals of a server are the server's: everyone sees the same animals, and a hunt or a fight is settled by the server.
- Crouch (Ctrl or C) to stalk: animals let you come much closer. Other players see you crouch. The bow works on a server.
- Escape on a server opens the full menu with Settings; the official server is already in the list; windowed is a real window.

## Your character on a server

- **Seven pages** in the Tab panel, as in a solo game: Pack, Craft, Research, Professions, Settlement, Planet, Journal.
- **Research** is the solo game's own tree, with the same costs and requirements. Research points come from Research Stations you build on the server (three a minute each), from profession levels, and you start with four. The server checks every requirement, takes the points and materials once and grants the technology once.
- **Research decides what you can make.** A craft or a piece that the technology tree ties to a technology needs that technology, researched by your character on that server, as well as the progression tier it always needed. For example: Lumber needs Lumber Processing; the Furnace, iron and copper ingots, glass and iron tools need Smelting; the Kiln needs Basic Construction; wire, mechanical parts and the Wind Turbine need Electricity; leather and leather armour need Leatherworking; fertilizer and the Grain Silo need Agriculture; the power saw and drill need Automated Production. The Craft page says what is missing.
- **Professions** grow from what you do on the server: gathering, crafting, building, hunting, researching. Their perks act on the server's own sums: one more from a gather (Clean Cuts for trees, Prospector for stone and ore, Forager for plants), a quicker next swing (Deep Strike, Quick Hands), cheaper building (Efficient Builder, Master Builder), everything back when you take a piece down (Salvage), faster research (Method, Insight, Genius).
- **Settlement** shows the settlement as a server has it: the players who are on, who has built on the planet, what stands there, the civilization's pillars, its stage, and your own progression. On a server the players are the civilization: there are no housed survivors and no workforce, and the page says so.
- **Journal** is the record of your character on that server: technologies, professions, everything you have gathered.
- **Separate from solo.** Your online character starts fresh whatever your solo games hold, and nothing you do online changes a solo save. Each player on a server has their own progress.
- The **Research Station** can be built on a server (Wood 12, Stone 8, Fiber 4).

### If you played 0.6.0

Your character keeps what it could already do. The first time it joins a 0.6.1 server it is given, once, the technologies behind everything its progression tier already allowed it to make, and behind anything it already holds or has built. Nothing you could make is locked by research afterwards. You get no research points or experience for those technologies; what lies beyond your tier you research like everyone else. Nothing you built or carry is changed.

## Animals, hunting and fighting on a server

- There is one set of animals on each planet of a server, run by the server. Two players standing together see the same animals doing the same things.
- The server decides who an animal notices - by where you are and whether you are walking, sprinting, standing still or crouching - and when it runs or attacks. An animal that attacks bites the player it went for, and that player's health is the server's to take.
- A strike with a hand weapon, a shot and a harvest are requests: the server knows your weapon and where you stand, takes the arrow from its own count, flies it, decides what it hit, and applies the damage once. A kill is seen by everyone as that animal dying. A carcass yields once, to the player standing at it.
- Which animals were killed, and the carcasses lying, are saved with the world.
- **Crouch / sneak**: Ctrl (or C) to crouch, again to stand; a jump or deep water stands you up. About half pace, no sprinting; the view sits lower and the HUD says SNEAKING. Animals notice a crouched player from about half as far while creeping and a third as far while still - come too close and they still run. Other players see you crouched. The key can be rebound.
- **The bow on a server**: right mouse button aims and draws, left click shoots - standing or crouched.

## The menu, the display, joining

- **Escape on a server** opens the menu: Resume, Settings (Audio, Video, Graphics), Controls, Leave Server, Quit Game. Nothing is paused and you stay connected; Escape steps back a page; Leave and Quit ask first.
- **Windowed** is a real window that fits on the screen beside the taskbar, at the size you choose. **Borderless** fills the monitor you choose. **Fullscreen** is exclusive fullscreen. The 15-second "Keep these display settings?" protection also goes back if you leave the page.
- **Official Server** is always the first entry on the multiplayer screen; its address is never shown and never needs typing. Direct Connect is still there for private, LAN and development servers.
- The first time on a server, CREATE YOUR CHARACTER opens by itself and says why; a refused name shows the reason; after CREATE you are told "Character created." and the same join carries on into the world.

## Coming in 0.6.2 (not on a server yet)

These work in a solo game and are the next parity work for servers:

- Fishing
- Digging and excavation
- The map
- Ruins and field notes
- The tutorial
- Farming beyond the first crop and plot

## Known limits

- Perks of systems a server does not have yet do nothing there: those of the solo settlement's machines, of ecology and of the orbital programme.
- The crouch is a pose laid over the walk, not its own animation.
- The Linux client's window fitting has not been run on a Linux desktop.
- Everything listed as a limit in the 0.6.0-alpha notes still applies.

`Docs/SOLO_ONLINE_PARITY.md` in the source has the full solo-against-online table.

The dedicated server is not a public download.
