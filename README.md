# Trick or Treat Street 🎃🍬

A 3D Halloween trick-or-treating game in a single HTML file, built with [Three.js](https://threejs.org). Pick a costume, walk around the neighborhood, knock on doors, and get home by midnight with the biggest haul you can.

## Play

Open `index.html` in any modern browser. There's no build step and nothing to install. Three.js and the title font load from CDNs, so you need an internet connection.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Walk | ↑ ↓ ← → or WASD | Drag anywhere |
| Look around | Drag with the mouse; scroll to zoom | Drag with a second finger |
| Reset view | Double-click or R | — |
| Pick a costume | Click it, or ← → on the title screen | Tap it |
| Music on / off | M, or the 🎵 button | Tap the 🎵 button |
| Start / restart | Space, Enter, or click | Tap |
| Exit to title | Esc, or 🏠 Exit (press twice) | Tap 🏠 Exit twice |

## How it works

- **Costumes:** Choose one on the title or game-over screen. Your pick is remembered. Each costume has a perk and its own special effects:
  - 🧛 **Vampire, Night Charm:** doors trick you half as often. Bats with red eyes circle overhead and red mist trails behind you. When the charm turns a trick into a treat, a swarm bursts out with "Night Charm! No trick!".
  - 🧙 **Witch, Candy Magnet:** loose candy flies to you from far away. Your hat tip glows and sheds green and purple sparkles, green streaks show candy being pulled in, and a spell circle flashes on the ground when you get a treat.
  - 💀 **Skeleton, Swift Bones:** you walk 25% faster. Your eye sockets glow blue, every step kicks up bone dust with a little rattle, and your bones go flying when a ghost gets you.
  - 🎃 **Pumpkin, Thick Rind:** you start with 4 hearts instead of 3. Your suit glows with flickering candlelight and gives off rising embers, and pumpkin seeds splatter when a ghost gets you.
  - Each costume also plays its own little tune when you get a treat.
- The night runs from 9:00 PM to midnight (2½ minutes).
- **Knock on doors:** Walk up the front path of a house with its porch light on. You knock, the door swings open, and someone answers.
- **Every door is a gamble:**
  - 🟠 **Orange porch light:** 2–4 candies, with a 25% chance of a trick.
  - ❓ **Green porch light:** 8 candies, with a 50% chance of a trick.
  - ⭐ **Gold porch light:** always a king-size bar, worth 10 candies.
- **Tricks:** A monster jumps out instead. It knocks you back, takes 4 candies, and pulls a prank: you get slimed, a spider drops down, or your screen gets toilet-papered.
- **The neighborhood:** Every street is different, with cottages, gable houses, Victorians with turrets, big haunted manors and crooked boarded-up shacks.
- **Dark houses:** Nobody's home. Once you've visited a house, its porch light goes out.
- **Loose candy** in the street is worth 1 each.
- **Ghosts** float down the street after you, and more come out as midnight gets closer. Each touch costs a heart and some candy. Lose all your hearts and you run home early.
- **Sugar Rush 🍭:** Get 5 treats in a row and for 8 seconds you walk faster, ghosts flee from you, and no door can trick you.
- **Music:** A spooky little tune plays the whole time. It speeds up as midnight gets closer and goes up an octave during a Sugar Rush.
- Your best haul is saved in the browser.
