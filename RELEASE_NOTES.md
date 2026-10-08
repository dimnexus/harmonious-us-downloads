# Harmonious Us 0.6.3-alpha — Staying connected (select alpha testing)

Build 63, channel alpha, **protocol 3** (unchanged). A 0.6.3 server accepts games from 0.6.2-alpha, and a 0.6.3 game plays on a 0.6.2 server: nobody is locked out by this update, but everyone should take it.

This build is for the selected alpha testers it was handed to. It is not generally available yet.

## In short

- Fixed: being disconnected a few seconds after joining a server.
- An online game keeps running when you switch to another window, so alt-tabbing no longer drops you.
- The server waits longer before giving up on a player who has gone quiet.

## What was wrong

When you join a server the game builds the world around you in one go, and while it did that it said nothing to the server. A server gave up on any player it had not heard from for ten seconds. On a computer where building the world took longer than that, the player was let in and then dropped ("timed out") before the world had appeared, every time they tried. The same thing happened to anyone who switched to another window for more than ten seconds, because the game stopped running while it was not in front.

Nothing was wrong with anyone's character, pack or the world. No data was lost.

## What changed

- **The game stays in touch while it builds the world.** The connection is serviced many times a second all through it, however long your computer takes.
- **An online game runs in the background.** Switching to another window no longer silences it. (A solo game still pauses when it is not in front, as before.)
- **The server is patient.** It now holds a quiet player for 45 seconds instead of 10. This alone lets a 0.6.2 game join again; the game-side fixes above make it no longer depend on that.
- The game's log now says how long the world took to build and how long the connection went unserviced, in one line, so a slow join can be seen for what it is.
- The multiplayer screen's "What's new" was brought up to date.

## Known limits

Unchanged from 0.6.2-alpha: planting wild species is still solo only; poured water does not flow; building pieces cannot be placed down inside a dug pit; field notes for merely sighting an animal are solo only.

The dedicated server is not a public download.
