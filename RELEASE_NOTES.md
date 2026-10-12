# Harmonious Us 0.6.4-alpha — Pick up a controller (select alpha testing)

Build 64, channel alpha, **protocol 3** (unchanged). A 0.6.4 server accepts games from 0.6.2-alpha and 0.6.3-alpha, and a 0.6.4 game plays on a 0.6.3 server: nobody is locked out by this update. A controller needed nothing new from the server.

This build is for the selected alpha testers it was handed to. It is not generally available yet.

## In short

- Play with a controller: moving, looking, tools, building, and every menu.
- Xbox-compatible, PlayStation-compatible, Nintendo-compatible and generic controllers are recognised by themselves.
- Prompts show the buttons of whatever you are holding, and change the moment you change hands.
- Everything 0.6.3 fixed about staying connected is unchanged.
- The launcher is unchanged: this update is the game only.

## Controllers

- **One game, any device.** A controller, the keyboard and the mouse all ask for the same actions - walk, jump, gather, build - so there is one game underneath, not a second one for controllers. Use any of them at any moment; nothing needs restarting and there is no "controller type" to choose.
- **It knows what you are holding.** The last device you deliberately used decides the prompts: move the mouse and they are keys, press a button and they are that controller's own - A / B / X / Y and LB / RB / LT / RT, Cross / Circle / Square / Triangle and L1 / R1 / L2 / R2, or a Nintendo-style controller's letters in their own places. A controller the game does not recognise still works, with its buttons shown by position. A stick that rests a little off centre does not count as "used".
- **On a Nintendo-style controller, A confirms and B goes back**, as players of those controllers expect; everywhere else it is the bottom button that confirms.
- **Every menu without a mouse.** The title screen, a new game, the character, multiplayer, the pack and all its pages, crafting, research, professions, the map, settings, pausing and quitting: a button is always selected and framed, the D-pad or left stick moves the selection, lists scroll to keep it in view, sliders move left and right, and the bumpers change tabs. Going back returns you to the button you came from.
- **A bar along the bottom says what the buttons do** on the screen you are looking at, in large pictures. While building, the build bar shows the builder's controls the same way.
- **Building works as it is**, with a controller: choose a piece, turn it, snap on or off, place it, undo, change material and storey, demolish.
- **Settings > Controller**: on or off, look speed, invert look up / down, stick dead zone. The mouse's own sensitivity is untouched.
- **Unplugged in the middle of something?** Nothing stays held, the keyboard and mouse simply carry on, and the controller is found again when it comes back.

The pictures of keys and buttons are Kenney's Input Prompts (www.kenney.nl, Creative Commons Zero), shown on the game's own plates.

## The server

- The server's log now sums up each connection when it ends: which build the player ran, how long joining took, and how close the connection came to the silence limit. A dropped connection can be explained from one line.
- Protocol 3, unchanged. Worlds, characters and everything built are carried over as they are.

## Known limits

- Typing still needs a keyboard: your character's name, a custom map marker's name and chat. (The character has a name already, and the map marker has ready-made names to choose from.)
- Keys can be rebound; a controller's buttons are a fixed layout in this version.
- No vibration.
- A controller must be one the system presents as a gamepad. Unusual controllers that appear only as a generic joystick are not read.
- Windows still shows "unknown publisher" for the game and the launcher. Signing them, and a launcher that checks the signature, are planned for a later update and are not part of this one.
- Unchanged from 0.6.3-alpha: planting wild species is still solo only; poured water does not flow; building pieces cannot be placed down inside a dug pit; field notes for merely sighting an animal are solo only.

The dedicated server is not a public download.
