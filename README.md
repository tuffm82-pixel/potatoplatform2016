# potatoplatform2016

## [CLICK ME TO PLAY OFFICIAL](https://potato-man-paper-quest.hassan766767676.chatgpt.site)

Sign in with ChatGPT to play the hosted game.

A portrait, three-lane arcade runner with original modeled 3D Potato Man characters, animated limbs, live lighting, shadows, and a colorful 3D world.

## Play
Open index.html in a browser. No installation or build is needed.

Left / Right or A / D change lanes. Space / Up / W jumps. Down / S slides. E activates your hero power. Escape / P pauses. Touch supports swipes and on-screen controls.

## Unlock your crew
Potato Man is free. Earn gold coins by collecting them on the track, then preview a locked character and choose Unlock when you have enough:
- Super Spud: 200 coins
- Greg: 350 coins
- Barry: 500 coins
- Chef: 750 coins

These are in-game coins earned through play. No payment or account is required. Coins save at pickup, so returning to the menu keeps them. Buying a hero deducts the price once, permanently unlocks them in this browser and equips them. Previously saved runner stars migrate into the wallet. Locked previews do not change the equipped hero.

Progress is local to this browser and origin; clearing browser data removes it. The 3D edition needs WebGL. It uses locally bundled Three.js r160 under the MIT license; see THREE-LICENSE.txt. Original art remains in assets as reference, while the playable characters are mesh models built in renderer3d.js.

## Verify
Run node --test *.test.cjs. Tests cover runner controls and collisions, purchases and migration, persistence, and all five volumetric character rigs.
