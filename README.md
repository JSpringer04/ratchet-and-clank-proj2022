# ratchet-and-clank-proj2022

## Overview
A fully playable 3D shooter-platformer. Inspired by Ratchet &amp; Clank and built in a C++ based platform for the PlayStation, this project focuses on gameplay systems, smart enemy AI, stunning VFX, optimal level design, logic optimization, and player feedback loops. Commended by the official Insomniac Games.

## SHOWCASES
🎮 Official Gameplay  Video: [https://www.youtube.com/watch?v=y5cUio3Be_M&t=3s]
(DISCLAIMER: Usage of AI voices. Placeholder while awaiting human voice recordings.)

🎮 Boss Showcae: [https://www.youtube.com/watch?v=bNl2orp5FQc]


## Technical Focus
- State-based enemy AI
- Modular weapon wheel
- Engaging gameplay and creative weaponry
- Sleek UI that doesn't overwhelm the player
- Strong VFX
- Camera and movement tuning
- Performance optimization under engine memory limits

## Systems Breakdown
### Player Controller
* Idle
* Wrench Swinging
* Helipack movement (Glide mechanic)

### Combat System
* Weapon state machine
  * One-handed or Two-Handed?
  * IsPlayerIdle?
  * ShotsFired?
  
* 12 Creative weapons offering distinct and unique playstyles
  * OmniPistol (Pistol/Primary)
  * Shatterbomb (Grenade)
  * Enforcer (Shotgun)
  * BOOM!Box (Utility | Shockwave)
  * FlareMonger (Rocket Launcher)
  * MagmaHound (Utility | Lava)
  * A.I.M.Bot (Utility | Minion)
  * HornetRay (Target)
  * NovaTalons (Melee)
  * Plasmapeater (Shock)
  * SnapShot (Immobilizer)
  * RYNO (RYNO)

* Dodge mechanics that are present in R&C: Rift Apart. (Showcases animation skills and ability to recognize laws of animation and replicate AAA quality and fluidity)

* On-Field pgrade System
  * Usage of a weapon increases the weapon level. Level 1 to 4. 
  * Damage is increased by 5% for each level. 
 
* Vendor and Upgrade System
  * Purchase weapons from vendor.
  * Upgrade attributes of the weapon at the weapon vendor. 
  * Can go down 3 paths, which upgrade the weapons' key attributes (fire rate, radius, ammo)
  * When the attribute is maxed, the weapon gains a special perk.
  * Damage is increased by 5% for every level. 

### Level Design
- Engaging environments that tell stories and never stay static.

## Tools Used
- DreamsPS4 Engine
- C++

## Why This Project Matters
This project is what first sparked my interest in computer science. What began as a simple learning exercise using C++ concepts and the Dreams Engine evolved into a long-term passion project focused on building responsive, engaging gameplay systems.

As the project grew, I moved beyond basic scripting into designing and refining interconnected systems—player movement, combat logic, animation states, user feedback loops for refinement, and most importantly, performance optimization within strict engine constraints. 

The project has continued to evolve over time and remains a defining part of my technical journey. The official Insomniac Games team became aware of the project and commended my efforts, alongside positive feedback from members of the PlayStation community. While the recognition was rewarding, the most meaningful outcome was seeing technical problem-solving translate directly into a more polished and enjoyable player experience—an experience that ultimately motivated me to pursue computer science.

## Recognition
- Inspired by Insomniac Games' Ratchet & Clank series
- Non-commercial fan project
