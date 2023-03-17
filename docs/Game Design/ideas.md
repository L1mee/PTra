# Ideas

## Fundamentals

  - The player is weak and not made for surving the alien planet.
  - Rather than weapons the player prefers tools.

---

## Story

Throughout the missions the player finds story elements and clues towards something special to the alien race. This is, so to say, their One Piece.

A spie contacts you to uplift the organisation.

You start to unite the workers which ultimately leads to a rebellion.

---

## Player abilities, tools and weapons

  - ### Stungun

    Very limited amount of ammunition, to make stun-locking enemies not a viable strategy.

  - ### Shockwire

    Inspired by Horizon: Zero Dawn a trap layed down beforehand to accomplish different kinds of effects on passing creatures.

  - ### Barrier

    Something that creatures don't want to enter/pass through.

  - ### Distraction

    Something to distract creatures to lead them in a certain direction.

  - ### TP-Bridges

    The player places down two anchors. Interacting with one of them teleports the player to the other anchor. Intended use is to prepare the bridge and then use it afterwards, not place it in a rush. That is also why an anchor requires some time to be deployed.

  - ### Flash

    Used to confuse chasing creatures that are using eyesight.

  - ### Smoke grenade

    A hiding place, unless chasing creatures saw the player enter.

  - ### Scout drone

    Inspired by R6 Siege, a way for the player to get some information on the area ahead without risking their own discovery.

  - ### Movement

    Some tools that allow the player to move in more ways than just walk. Could include diegetic bars, roles, sprints and more.

---

## Alien abilities

Alien specific abilities, though not every creatures can use all of these abilities.

  - ### Charge-AOE

    Charges an area of effect ability that hits the player. Animation that displays charge to allow player to get out of reach.

  - ### Scan

    Allows the creature to check for enemies, mainly used to find the player after they escaped.

  - ### Silence

    Prevents player to use certain abilities for a set amount of time.

  - ### Slimeshot

    Stuns player on hit at their current location.

  - ### Stealth

    Hides itself to surprise player and reduce predictability. Can't hide just about everywhere.

  - ### Change environment

    For example places cobwebs at their current location that makes it harder for the player to pass that area.

---

## Environment

  - ### Terrain

    - Normal
    - Tough
    - Slippery

  - ### Cover
    
    - Natural cover (bushes)
    - Line of sight (hide behind)

---

## Base

  - ### Scanner

    Displays information about the current planet.

  - ### Equipment Upgrades

  - ### Equipment Crafting

  - ### Unlocks

  - ### Skilltree

    Skills can be earned/unlocked by in-game money to limit immersion breaking as much as possible. Therefore the player won't have a level.

    - Reduce visibility
    - Increase movement speed

---

## Miscellaneous

  - ### Performance based difficulty

    AI might get better during the game and adapt to the player.

  - ### More options/brains instead of muscle

    Instead of becoming overpowered the player gets more options. The environment and obstacles still get harder though, but the main focus should be the player getting better at the game. This means no weapons that simply deal more damage.

---

## Alien technology

On multiple occasions the player may find ancient alien ruins. Portable power sources and other technological equipment can be used to get deeper in those ruins. Those ruins are either required as passage way to an objective or contain additional ressources, upgrades or story elements. Difficulty scales based on the usable puzzle elements. It is important, that there are multiple options to prevent a linear puzzle experience where the solution is straightforward.

Visual feedback is shown by animations and particles that show the player what certain actions do. Interactables are also equiped with a slight effect, like tiny sparkles.

### Lore & description

The alien technology is based on an impulse system. Power cells emit a steady pulse that runs through the linked systems. Levers then convert the impuls to an action, when linked to a door this can be either open or close, the state of the door itself does not require any power. This changes per linked object, some objects need constant power to maintain their state. Since this system is running on impulse the conservation of momentum (Impulserhaltung) dictates that only the last-linked system is powered. This only applies to "work" being done, so a turned-on lever linked to an open door is not considered to "use up" that impulse.

(They can be separated into two categories: Impulse and constant power. More categories might be added in the future)

Since this impulse system is different from electricity no circuit is required. Instead of parallel connections the signal is simply split up, with both ends being considered for "last-linked". However different machines/actions might require stronger impulses, a split only provides each side with exactly half impulse power. Some machines simply won't run properly under these cirumstances. This can easily be achieved by adding an additional impulse cell to the entire circuit. Whenever there are two impulse cells on the same line the last two systems are powered. A split always splits in two lines, so there are only ever power states of 1, 1/2, 1/4, 1/8 and less. Power states above 1 are always rounded down visually and only internally processed as a higher number. Lower power states are shown with a weaker impulse.

The first obstacle: A nice introduction to alien technology is a very basic door with a powercell and a lever. The player needs to put back the powercell and flip the lever to get through the door. Levers stay in their last position no matter the power, so the sequence is not important here.

(This might open potential mechanics for overloading the system that then forcefully flicks the lever by overloading)

More advanced obstacle: Multiple power cells are required in a two-stage puzzle. The first challenge is getting through to the first additional impulse cell that then opens a pathway to the second stage that makes use of both impulse cells.

**Attributes**

  - Impulse cell: Generates impulses
  - Series connection
  - Parallel connection
  - Door (Impulse power): Opens pathway
  - Restoration device (Constant power): Creates new pathways
  - Dropper (IP): Drops an item/device
  - Bridge (CP): Transfers impulse to a different location
  - Lights (CP): Lights up a previously unlit area, highlighting a code or something useful previously invisible
  - Moving elements (CP): Moving pathways
  - Distraction (IP/CP): A noise or something used to distract enemies
  - Custom effects (IP/CP): Whatever else might work in the area
  - Piston (IP/CP): Push forward once per impulse, might clear a previously blocked lever
  - Motor (CP): Powers something that requires a motor to run
  - Overload: Forces a system running on IP to switch states
  - Lever: Switches state of the attached machine

### More ideas

Contributing the impulse could be part of the puzzle too.

## Other puzzle ideas

Underlying mechanic: Sudoku based puzzle where different symbols/objects need to be aligned.

However this is outside of the usual 9x9 grid and instead only focusses on finding a few specific pieces for one tiny scenario.