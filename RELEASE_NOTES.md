# Harmonious Us 0.6.8a — Gameplay Interaction Hotfix

Version 0.6.8-alpha.1 (build 69). A game update only: servers, worlds, characters and saves are unchanged, and
0.6.8 and 0.6.8a players play together.

## Fixed

- **Aiming in first person.** In 0.6.8, while a tool or the bow was in use in first person, the view dipped to follow the
  character's head but the game kept aiming where the view had been - up to 20 degrees apart. The crosshair now shows
  exactly where you aim again, as in 0.6.7.
- **Bow.** Arrows fly to the crosshair again, in first person and when aiming from third person (aiming the bow always
  looks over the arrow in first person).
- **Gathering tools.** The axe and the pickaxe work what is under the crosshair while you keep it on the work (the other
  tools aim the same way).
- **Hunting.** Arrows reach the animal you aim at, and the remains of an animal you have killed are harvested where you aim;
  the server's damage, deaths and harvests are as before.

## Known

- Spear strikes use the same corrected aim, but a live spear hit on an animal was not part of this update's automated
  checks (the animals near our test spot keep out of a spear's reach). Tell us if a spear still misses what you aim at.
- In first person the view no longer leans into a stroke with the head; that touch comes back in a later update, made so
  it cannot move your aim.
