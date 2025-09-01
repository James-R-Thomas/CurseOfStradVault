---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
  - compendium/src/5e/cos
  - monster/cr/10
  - monster/size/medium
  - monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
  - The Abbot
NamedMonster: true
Place:
---
# [The Abbot](3-Mechanics\CLI\bestiary\npc/the-abbot-cos.md)
*Source: Curse of Strahd p. 151*  

```statblock
"name": "The Abbot (CoS)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "18"
  - !!int "17"
  - !!int "20"
  - !!int "20"
"speed": "30 ft., fly 90 ft."
"saves":
  - "wisdom": !!int "9"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 19"
"languages": "all, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "The Abbot's spellcasting ability is Charisma (spell save DC 17). The\
      \ Abbot can innately cast the following spells, requiring only verbal components:\n\
      \nAt will: [detect evil and good](/3-Mechanics/CLI/spells/detect-evil-and-good-xphb.md)\n\
      \n1/day each: [commune](/3-Mechanics/CLI/spells/commune-xphb.md), [raise\
      \ dead](/3-Mechanics/CLI/spells/raise-dead-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "The Abbot's weapon attacks are magical. When The Abbot hits with any\
      \ weapon, the weapon deals an extra 4d8 radiant damage (included in the attack)."
    "name": "Angelic Weapons"
  - "desc": "The Abbot has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The Abbot makes two melee attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 7 (1d6\
      \ + 4) bludgeoning damage plus 18 (4d8) radiant damage."
    "name": "Mace"
  - "desc": "The Abbot touches another creature. The target magically regains 20 (4d8\
      \ + 2) hit points and is freed from any curse, disease, poison, blindness, or\
      \ deafness."
    "name": "Healing Touch (3/Day)"
  - "desc": "The Abbot magically polymorphs into a humanoid or beast that has a challenge\
      \ rating equal to or less than its own, or back into its true form. It reverts\
      \ to its true form if it dies. Any equipment it is wearing or carrying is absorbed\
      \ or borne by the new form (The Abbot's choice).\n\nIn a new form, The Abbot\
      \ retains its game statistics and ability to speak, but its AC, movement modes,\
      \ Strength, Dexterity, and special senses are replaced by those of the new form,\
      \ and it gains any statistics and capabilities (except class features, legendary\
      \ actions, and lair actions) that the new form has but that it lacks."
    "name": "Change Shape"
"source":
  - "CoS"
"image": "/3-Mechanics/CLI/bestiary/npc/token/the-abbot-cos.webp"
```
^statblock