---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1
- monster/environment/feywild
- monster/environment/forest
- monster/environment/grassland
- monster/environment/planar
- monster/environment/underdark
- monster/size/medium
- monster/type/fey/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bugbear Warrior
---
# [Bugbear Warrior](3-Mechanics\CLI\bestiary\fey/bugbear-warrior-xmm.md)
*Source: Monster Manual (2024) p. 62. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Bugbear warriors serve those who offer them treasure, food, or the chance to hunt challenging prey.

## Bugbears

*Lurking Goblinoid Brutes*

- **Habitat.** Forest, Grassland, Planar (Feywild), Underdark  
- **Treasure.** Armaments, Individual  

Bugbears embody fear of the wilds and the menace of natural places. They're notoriously stealthy, and foes that venture into their territories often vanish without a trace.

```statblock
"name": "Bugbear Warrior (XMM)"
"size": "Medium"
"type": "fey"
"subtype": "goblinoid"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "13"
  - !!int "8"
  - !!int "11"
  - !!int "9"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Goblin"
"cr": "1"
"traits":
  - "desc": "The bugbear needn't spend extra movement to move a creature it is grappling."
    "name": "Abduct"
"actions":
  - "desc": "Melee Attack Roll: +4, reach 10 ft. Hit: 9 (2d6 + 2) Bludgeoning\
      \ damage. If the target is a Medium or smaller creature, it has the [Grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ condition (escape DC 12)."
    "name": "Grab"
  - "desc": "Melee  or Ranged Attack Roll: +4 (with [Advantage](/3-Mechanics/CLI/variant-rules/advantage-xphb.md)\
      \ if the target is [Grappled](/3-Mechanics/CLI/conditions.md#Grappled) by the\
      \ bugbear), reach 10 ft. or range 20/60 ft. Hit: 9 (3d4 + 2) Bludgeoning damage."
    "name": "Light Hammer"
"source":
  - "XMM"
"image": "/3-Mechanics/CLI/bestiary/fey/token/bugbear-warrior-xmm.webp"
```
^statblock

## Environment

forest, grassland, planar, feywild, underdark