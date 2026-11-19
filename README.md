# Fossil Fury

An original top-down stone age roguelike. You play a caveman kid throwing rocks at dinosaurs through procedurally generated cave floors.

Everything is made in code: the pixel art is drawn from text sprite maps, and the music and sound effects are synthesized live with the Web Audio API. There are no external assets or dependencies.

## Play

Open `index.html` in a browser. To put it on a website, host the file and embed it:

```html
<iframe src="/games/fossil-fury/index.html" width="960" height="672" style="border:0" allow="gamepad; autoplay"></iframe>
```

The canvas scales to fit whatever size its container is.

## Controls

| Action | Keyboard | Gamepad | Touch |
| --- | --- | --- | --- |
| Move | WASD | Left stick or D-pad | Left half of screen |
| Throw rocks | Arrow keys, or hold the mouse button | Right stick or face buttons | Right half of screen |
| Pause | P or Esc | Start | Tap the minimap |
| Mute | M | | |

## What's in this slice

- 3 floors (Fern Hollow, Tar Pits, Magma Deeps), each a random map of 9 to 15 rooms with a treasure room and a boss room
- Rooms lock until every dino is cleared, with random obstacle layouts: boulders, bone piles, breakable ferns and slowing tar
- 5 enemy types: compies (chasers), pteros (fliers), spitters (ranged), ankylos (charge when lined up) and eggs (hatch into compies)
- A tyrant lizard boss with charge, ground-pound, roar and fire-spit attacks, recolored and stronger on each floor
- 11 items: Mammoth Tusk, Bone Sling, Raptor Feather, Turtle Shell, Fire Stick, Handful of Pebbles, Big Rock, Amber Eye, Lucky Claw, Dino Heart, Flint Spear
- Meat and berry heals, minimap, pause screen with stats, best-floor record saved in the browser
