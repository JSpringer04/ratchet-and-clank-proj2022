# ratchet-and-clank-proj2022

## Overview
A fully playable 3D shooter-platformer. Inspired by Ratchet &amp; Clank and built in a C++ based platform for the PlayStation, this project focuses on gameplay systems, smart enemy AI, stunning VFX, optimal level design, logic optimization, and player feedback loops. Commended by the official Insomniac Games.

## Demo
🎮 Gameplay Video: [https://www.youtube.com/watch?v=bNl2orp5FQc]
📸 Screenshots: See /media folder

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
-Idle
-Wrench Swinging
-Helipack movement (Glide mechanic)

### Combat System
- Weapon state machine
  *One-handed or Two-Handed?
  *IsPlayerIdle?
  *ShotsFired?
  
-12 Creative weapons offering distinct and unique playstyles
  *OmniPistol (Pistol/Primary)
  *Shatterbomb (Grenade)
  *Enforcer (Shotgun)
  *BOOM!Box (Utility | Shockwave)
  *FlareMonger (Rocket Launcher)
  *MagmaHound (Utility | Lava)
  *A.I.M.Bot (Utility | Minion)
  *HornetRay (Target)
  *NovaTalons (Melee)
  *Plasmapeater (Shock)
  *SnapShot (Immobilizer)
  *RYNO (RYNO)

-Dodge mechanics that are present in R&C: Rift Apart. (Showcases animation skills and ability to recognize laws of animation and replicate AAA quality and fluidity)

-On-Field pgrade System
  *Usage of a weapon increases the weapon level. Level 1 to 4. 
  *Damage is increased by 5% for each level. 
 
-Vendor and Upgrade System
  *Purchase weapons from vendor.
  *Upgrade attributes of the weapon at the weapon vendor. 
  *Can go down 3 paths, which upgrade the weapons' key attributes (fire rate, radius, ammo)
  *When the attribute is maxed, the weapon gains a special perk.
  *Damage is increased by 5% for every level. 

### Level Design
- Engaging environments that tell stories and never stay static.
- 

## Tools Used
- DreamsPS4 Logic System
- C++
- 

## Why This Project Matters
This project demonstrates 

## Recognition
- Inspired by Insomniac Games' Ratchet & Clank series
- Non-commercial fan project
