# Harmonious Us 0.6.6-alpha — Building + Terrain Interaction

Build 66, channel alpha, **protocol 3** (unchanged). A 0.6.6 server accepts games from 0.6.2-alpha onwards, and a 0.6.6 game plays on an older server: nobody is locked out by this update. Nothing in the save format changed.

This update is about building and digging on a server, and when you **Play alone** from the multiplayer screen - which is the same game with the server on your own computer. A game started with NEW GAME on the title screen still uses its older builder, which is as it was.

## In short

- The turn key turns a roof, and roofs line up.
- The build panel tells you where the piece will go before you click.
- The "next snap point" key no longer sticks.
- Undo reaches back through your last placements, not only the last one.
- The remove key takes the piece you are looking at, and tells you which first.
- Back is one step back.
- A foundation stands on the floor of what you have dug - a hollow, or a room dug deep under the land - and walls, doors, stairs and ceilings go on it.
- Nothing is built into ground that has not been dug away.
- A world with a lot of digging in it reaches everyone who joins.

## Roofs

- **[R] turns a roof.** A quarter turn at a time, back with Shift. Before, the turn key did nothing to a roof: the only way to turn one was "next snap point" ([K]), which said nothing about turning.
- **Roofs line up.** The next roof you place lies the way you turned the last one, whichever way its own floor happens to face. Two rooms side by side get one ridge line without touching a key. Before, each roof took the heading of the floor under it, and a floor's heading depended on which edge it had been extended from - neighbours could come out a quarter turn apart.
- The key strip says "Turn roof" while a roof is selected.

## Knowing what will happen

- **The build panel says where the preview is.** "Ready: on the north edge of the Foundation", "Ready: over the Foundation, turned to face east", "Ready: in the Doorway Wall", "Ready: on the dug ground". Before, it said only "Ready to place".
- **[K] is for where you press it.** It steps past the nearest snap point at the place you are aiming; aim somewhere else and the nearest point is offered again, as it is after placing a piece or choosing another. Before, one press stayed in force until build mode was closed, and every later preview went to the second-nearest place - a wall on the wrong edge, a roof on the wrong room.

## Putting a mistake right

- **Undo reaches back.** [U] takes back your placements of the last fifteen seconds, newest first, each for all it cost; the key strip shows how many it can still take ("Undo (3)"). Before, it remembered one.
- **[X] takes what you are looking at.** Look at a door and it is the door that goes, not the wall it hangs in. Before, it took whichever of your pieces had its origin nearest your aim; a door, its doorway wall and the edge of the floor under them share one origin, and which went was chance.
- **The key strip names it.** "Remove: Door", "Remove: Wall" - before you press the key.
- **Back is one step back.** [Esc] (B on a controller) leaves a thing you were moving where it was, or puts demolish mode away, or takes the pointer back to aiming - and only then closes build mode. Before, it closed build mode from wherever you were. In link mode it used to open the game menu as well; now it closes link mode and nothing else.

## Building and dug ground

- **A foundation stands on the ground as it is now.** In a hollow you have dug, it goes on the dug floor, below the land. Standing in a room you have dug deep under the land, it goes on that room's floor. Walls, a doorway, a door, stairs and a ceiling go on it as anywhere else. Before, building measured from the land as it was made: in a hollow the foundation was put up where the ground used to be, and drawn as a block rising out of the hole.
- **Nothing is built inside solid ground.** A floor or foundation that would lie in ground that has not been dug away - run from a sunken room into the side of its hollow, on from an underground room into rock, or along a hillside into the rise - is refused, in the preview and by the server, with the reason: "The ground is in the way - dig it out first, or build higher". A wall is refused where the room has not been dug to the wall's height.
- **Digging and filling are as they were,** and worth knowing: the shovel digs soft ground and, with its second use, puts ground back; the pickaxe goes through rock; a shaft goes as deep as you like to dig it, and from its foot you can dig sideways - the ground above stays where it is. Filling is paid for in the ground you carry, so what you dug by mistake goes back. The ground a building stands on cannot be dug out from under it.

## On a server

- **A world with a lot of digging reaches everyone.** When a player joined, the server could say more at once than the connection would take, and what did not fit was lost without a word - with enough dug ground in a world, a joining player could be left with none of it. Now nothing is lost: what cannot go at once waits its turn and goes in order.
- Every placement, removal, door and dig is still the server's decision; the preview is only a preview.
- What is built and what is dug survives the server being stopped and started, and is the same for every player. A door opened by one player is open for the other.

## Playing alone

- **Play alone** on the multiplayer screen is this same builder and this same ground: the game runs the server on your own computer, saves when you leave, and has your world as you left it when you come back. Everything above applies to it.

## Known limits

- **NEW GAME's builder is unchanged.** A game started from NEW GAME on the title screen uses a different, older builder (drawn walls, rectangle floors and roofs, Quick Roof). None of this update's fixes apply to it, and it still refuses to build over a hollow or a tunnel. To build with everything in these notes on your own, use Play alone.
- A roof can still be placed over a floor that has no walls.
- A wall on a floor's edge always faces outward from that floor; it cannot be flipped.
- A group of the build menu shows ten pieces to the number keys; the rest are reached with the wheel or the pointer.
- There is no ladder or stair that follows a shaft down: a deep room is reached by the way you dug to it.
- Ceilings do not fall and need no supports.
- A game older than 0.6.6 on a 0.6.6 server previews with the old rules: its preview can show a foundation in a hollow at the old height, and the server then places it on the dug floor.
- Unchanged from 0.6.5-alpha: small ponds can hold no fish; typing needs a keyboard; Windows still shows "unknown publisher" for the game and the launcher.

The dedicated server is not a public download.
