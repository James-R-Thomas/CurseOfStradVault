---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
  - compendium/src/5e/cos
  - monster/cr/15
  - monster/size/medium
  - monster/type/undead/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Strahd von Zarovich
NamedMonster: true
Place:
---
# [Strahd von Zarovich](3-Mechanics\CLI\bestiary\npc/strahd-von-zarovich-cos.md)
*Source: Curse of Strahd p. 240*  

With his mind sharp and his heart dark, Strahd von Zarovich is a formidable foe. Courage and lives beyond measure have been lost to him. Reread chapter 1, "Into the Mists," to understand his personality and goals.

Although Strahd can be encountered almost anywhere in his domain, the vampire is always encountered in the place indicated by the card reading in chapter 1, unless he has been forced into his tomb in the catacombs of Castle Ravenloft.

## Strahd's Tactics

Because the entire adventure revolves around Strahd, you must play him intelligently and do everything you can to make him a terrifying and cunning adversary for the player characters.

When you run an encounter with Strahd, keep the following facts in mind:

- Strahd attacks at the most advantageous moment and from the most advantageous position.  
- Strahd knows when he's in over his head. If he begins taking more damage than he can regenerate, he moves beyond the reach of melee combatants and spellcasters, or he flies away (using summoned wolves or swarms of bats or rats to guard his retreat).  
- Strahd observes the characters to see who among them are most easily swayed, then tries to charm characters who have low Wisdom scores and use them as thralls. At the very least, he can order a [charmed](conditions.md#Charmed) character to guard him against other members of the adventuring party.  

## The Vampire's Minions

Whenever Strahd appears in a location other than his tomb or the place indicated by the card reading, roll a `dice:d20|noform|noparens|avg` (`d20`) and consult the Strahd's Minions table to determine what creatures he brings with him, if any.

## Strahd's Minions

`dice: [](strahd-von-zarovich-cos.md#^creatures)`

| dice: d20 | Creatures |
|-----------|-----------|
| 1–3 | `dice:1d4+2\|noform\|noparens\|avg` (`1d4 + 2`) [dire wolves](/3-Mechanics/CLI/bestiary/beast/dire-wolf-xmm.md) |
| 4–6 | `dice:1d6+3\|noform\|noparens\|avg` (`1d6 + 3`) [ghouls](/3-Mechanics/CLI/bestiary/undead/ghoul-xmm.md) |
| 7–9 | `dice:1d4+2\|noform\|noparens\|avg` (`1d4 + 2`) [Strahd zombies](/3-Mechanics/CLI/bestiary/undead/strahd-zombie-cos.md) (in this appendix) |
| 10–12 | `dice:2d4\|noform\|noparens\|avg` (`2d4`) [swarms of bats](/3-Mechanics/CLI/bestiary/beast/swarm-of-bats-xmm.md) |
| 13–15 | `dice:1d4+1\|noform\|noparens\|avg` (`1d4 + 1`) [vampire spawn](/3-Mechanics/CLI/bestiary/undead/vampire-spawn-xmm.md) |
| 16–18 | `dice:3d6\|noform\|noparens\|avg` (`3d6`) [wolves](/3-Mechanics/CLI/bestiary/beast/wolf-xmm.md) |
| 19–20 | None |
^creatures

If the characters are in a residence, Strahd's creatures break through doors and windows to reach them, or crawl up through the earth, or swoop down the chimney. The vampire spawn (all that's left of a party of adventurers that Strahd defeated long ago) can't enter the characters' location unless invited.

## Heart of Sorrow

Strahd can afford to be bold in his tactics, for he has additional protection in the form of a giant crystal heart hidden inside Castle Ravenloft.

Any damage that Strahd takes is transferred to the Heart of Sorrow (see chapter 4, area K20). If the heart absorbs damage that reduces it to 0 hit points, it is destroyed, and Strahd takes any leftover damage. The Heart of Sorrow has 50 hit points and is restored to that number of hit points each dawn, provided it has at least 1 hit point remaining. Strahd can, as a bonus action on his turn, break his link to the Heart of Sorrow so that it no longer absorbs damage dealt to him. Strahd can reestablish his link to the Heart of Sorrow as a bonus action on his turn, but only while in Castle Ravenloft.

The effect of the protection afforded by the Heart of Sorrow can be chilling to behold, as damage to Strahd is quickly undone. For example, a critical hit might dislocate Strahd's jaw, but only for a moment; then the vampire's jaw quickly resets itself.

The ability of the Heart of Sorrow to absorb damage is suppressed if it or Strahd is fully within an [antimagic field](/3-Mechanics/CLI/spells/antimagic-field-xphb.md).

```statblock
"name": "Strahd von Zarovich (CoS)"
"size": "Medium"
"type": "undead"
"subtype": "shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "18"
  - !!int "20"
  - !!int "15"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+15"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+10"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+14"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 120 ft., passive Perception 22"
"languages": "Abyssal, Common, Draconic, Elvish, Giant, Infernal"
"cr": "15"
"traits":
  - "desc": "Strahd is a 9th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 18, +10 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\nCantrips (at will): [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md), [ray\
      \ of frost](/3-Mechanics/CLI/spells/ray-of-frost-xphb.md)\n\n1st level (4\
      \ slots): [comprehend languages](/3-Mechanics/CLI/spells/comprehend-languages-xphb.md),\
      \ [fog cloud](/3-Mechanics/CLI/spells/fog-cloud-xphb.md), [sleep](/3-Mechanics/CLI/spells/sleep-xphb.md)\n\
      \n2nd level (3 slots): [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [gust of wind](/3-Mechanics/CLI/spells/gust-of-wind-xphb.md), [mirror image](/3-Mechanics/CLI/spells/mirror-image-xphb.md)\n\
      \n3rd level (3 slots): [animate dead](/3-Mechanics/CLI/spells/animate-dead-xphb.md),\
      \ [fireball](/3-Mechanics/CLI/spells/fireball-xphb.md), [nondetection](/3-Mechanics/CLI/spells/nondetection-xphb.md)\n\
      \n4th level (3 slots): [blight](/3-Mechanics/CLI/spells/blight-xphb.md),\
      \ [greater invisibility](/3-Mechanics/CLI/spells/greater-invisibility-xphb.md),\
      \ [polymorph](/3-Mechanics/CLI/spells/polymorph-xphb.md)\n\n5th level (1 slots):\
      \ [animate objects](/3-Mechanics/CLI/spells/animate-objects-xphb.md), [scrying](/3-Mechanics/CLI/spells/scrying-xphb.md)"
    "name": "Spellcasting"
  - "desc": "If Strahd isn't in running water or sunlight, he can use his action to\
      \ polymorph into a Tiny bat, a Medium wolf, or a Medium cloud of mist, or back\
      \ into his true form.\n\nWhile in bat or wolf form, Strahd can't speak. In bat\
      \ form, his walking speed is 5 feet, and he has a flying speed of 30 feet. In\
      \ wolf form, his walking speed is 40 feet. His statistics, other than his size\
      \ and speed, are unchanged. Anything he is wearing transforms with him, but\
      \ nothing he is carrying does. He reverts to his true form if he dies.\n\nWhile\
      \ in mist form, Strahd can't take any actions, speak, or manipulate objects.\
      \ He is weightless, has a flying speed of 20 feet, can hover, and can enter\
      \ a hostile creature's space and stop there. In addition, if air can pass through\
      \ a space, the mist can do so without squeezing, and he can't pass through water.\
      \ He has advantage on Strength, Dexterity, and Constitution saving throws, and\
      \ he is immune to all nonmagical damage, except the damage he takes from sunlight."
    "name": "Shapechanger"
  - "desc": "If Strahd fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "When Strahd drops to 0 hit points outside his coffin, he transforms into\
      \ a cloud of mist (as in the Shapechanger trait) instead of falling [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious),\
      \ provided that he isn't in running water or sunlight. If he can't transform,\
      \ he is destroyed.\n\nWhile he has 0 hit points in mist form, he can't revert\
      \ to his vampire form, and he must reach his coffin within 2 hours or be destroyed.\
      \ Once in his coffin, he reverts to his vampire form. He is then [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)\
      \ until he regains at least 1 hit point. After 1 hour in his coffin with 0 hit\
      \ points, he regains 1 hit point."
    "name": "Misty Escape"
  - "desc": "Strahd regains 20 hit points at the start of his turn if he has at least\
      \ 1 hit point and isn't in running water or sunlight. If he takes radiant damage\
      \ or damage from holy water, this trait doesn't function at the start of his\
      \ next turn."
    "name": "Regeneration"
  - "desc": "Strahd can climb difficult surfaces, including upside down on ceilings,\
      \ without having to make an ability check."
    "name": "Spider Climb"
  - "desc": "Strahd has the following flaws:\n\n- Forbiddance. He can't enter\
      \ a residence without an invitation from one of the occupants.  \n- Harmed\
      \ by Running Water. He takes 20 acid damage if he ends his turn in running\
      \ water.  \n- Stake to the Heart. If a piercing weapon made of wood is driven\
      \ into his heart while he is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ in his coffin, he is [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)\
      \ until the stake is removed.  \n- Sunlight Hypersensitivity. While in sunlight,\
      \ Strahd takes 20 radiant damage at the start of his turn, and he has disadvantage\
      \ on attack rolls and ability checks  "
    "name": "Vampire Weaknesses"
"actions":
  - "desc": "Strahd makes two attacks, only one of which can be a bite attack."
    "name": "Multiattack (Vampire Form Only)"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 8 (1d8\
      \ + 4) slashing damage, plus 14 (4d6) necrotic damage. If the target is a creature,\
      \ Strahd can grapple it (escape DC 18) instead of dealing the slashing damage."
    "name": "Unarmed Strike (Vampire or Wolf Form Only)"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one willing creature,\
      \ or a creature that is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by Strahd, [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ or [restrained](/3-Mechanics/CLI/conditions.md#Restrained). Hit: 7 (1d6\
      \ + 4) piercing damage plus 10 (3d6) necrotic damage. The target's hit point\
      \ maximum is reduced by an amount equal to the necrotic damage taken, and Strahd\
      \ regains hit points equal to that amount. The reduction lasts until the target\
      \ finishes a long rest. The target dies if its hit point maximum is reduced\
      \ to 0. A humanoid slain in this way and then buried in the ground rises the\
      \ following night as a [vampire spawn](/3-Mechanics/CLI/bestiary/undead/vampire-spawn-xmm.md)\
      \ under Strahd's control."
    "name": "Bite"
  - "desc": "Strahd targets one humanoid he can see within 30 feet of him. If the\
      \ target can see Strahd, the target must succeed on a DC 17 Wisdom saving throw\
      \ against this magic or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed).\
      \ The [charmed](/3-Mechanics/CLI/conditions.md#Charmed) target regards Strahd\
      \ as a trusted friend to be heeded and protected. The target isn't under Strahd's\
      \ control, but it takes Strahd's requests and actions in the most favorable\
      \ way and lets Strahd bite it.\n\nEach time Strahd or his companions do anything\
      \ harmful to the target, it can repeat the saving throw, ending the effect on\
      \ itself on a success. Otherwise, the effect lasts 24 hours or until Strahd\
      \ is destroyed, is on a different plane of existence than the target, or takes\
      \ a bonus action to end the effect."
    "name": "Charm"
  - "desc": "Strahd magically calls 2d4 [swarms of bats](/3-Mechanics/CLI/bestiary/beast/swarm-of-bats-xmm.md)\
      \ or [swarms of rats](/3-Mechanics/CLI/bestiary/beast/swarm-of-rats-xmm.md),\
      \ provided that the sun isn't up. While outdoors, Strahd can call 3d6 [wolves](/3-Mechanics/CLI/bestiary/beast/wolf-xmm.md)\
      \ instead. The called creatures arrive in d4 rounds, acting as allies of Strahd\
      \ and obeying his spoken commands. The beasts remain for 1 hour, until Strahd\
      \ dies, or until he dismisses them as a bonus action."
    "name": "Children of the Night (1/Day)"
"legendary_actions":
  - "desc": "Strahd moves up to his speed without provoking opportunity attacks."
    "name": "Move"
  - "desc": "Strahd makes one unarmed strike."
    "name": "Unarmed Strike"
  - "desc": "Strahd makes one bite attack."
    "name": "Bite (Costs 2 Actions)"
"lair_actions":
  - "desc": "While Strahd is in Castle Ravenloft, he can take lair actions as long\
      \ as he isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": ""
  - "desc": "On initiative count 20 (losing initiative ties), Strahd can take one\
      \ of the following lair action options, or forgo using any of them in that round:"
    "name": ""
  - "desc": "- Until initiative count 20 of the next round, Strahd can pass through\
      \ solid walls, doors, ceilings, and floors as if they weren't there.  \n- Strahd\
      \ targets any number of doors and windows that he can see, causing each one\
      \ to either open or close as he wishes. Closed doors can be magically locked\
      \ (needing a successful DC 20 Strength check to force open) until Strahd chooses\
      \ to end the effect, or until Strahd uses this lair action again.  \n- Strahd\
      \ summons the angry spirit of one who has died in the castle. The apparition\
      \ appears next to a hostile creature that Strahd can see, makes an attack against\
      \ that creature, and then disappears. The apparition has the statistics of a\
      \ [specter](/3-Mechanics/CLI/bestiary/undead/specter-xmm.md).  \n- Strahd targets\
      \ one Medium or smaller creature that casts a shadow. The target's shadow must\
      \ be visible to Strahd and within 30 feet of him. If the target fails a DC 17\
      \ Charisma saving throw, its shadow detaches from it and becomes a [shadow](/3-Mechanics/CLI/bestiary/undead/shadow-xmm.md)\
      \ that obeys Strahd's commands, acting on initiative count 20. A [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell or a [remove curse](/3-Mechanics/CLI/spells/remove-curse-xphb.md) spell\
      \ cast on the target restores its natural shadow, but only if its undead shadow\
      \ has been destroyed.  "
    "name": ""
"source":
  - "CoS"
"image": "/3-Mechanics/CLI/bestiary/npc/token/strahd-von-zarovich-cos.webp"
```
^statblock