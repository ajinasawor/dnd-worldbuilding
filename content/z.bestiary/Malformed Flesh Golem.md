---
title: Malformed Flesh Golem
draft: true
tags:
- homebrew
- CR2
- ref-DMLAIR
---
```statblock
layout: Basic 5e Layout
image: 
name: Malformed Flesh Golem
size: medium
type: construct
alignment: ualigned
ac: 9
hp: 60 (11d8 + 11)
hit_dice: 11d8 + 11
speed: 30 ft.
stats: [15,9,12,1,10,5]
damage_immunities: lightning, poison; bludgeoning, piercing, slashing from nonmagical attacks that aren’t adamantine
condition_immunities: charmed, exhaustion, frightened, paralyzed, petrified, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: 
cr: 2
traits:
  - name: Berserk
    desc: Whenever the golem starts its turn with 30 hit points or fewer, roll a d6. On a 6, the golem goes berserk. On each of its turns while berserk, the golem attacks the nearest creature it can see. If no creature is near enough to move to and attack, the golem attacks an object, with preference for an object smaller than itself. Once the golem goes berserk, it continues to do so until it is destroyed or regains all its hit points.
  - name: Aversion of Fire
    desc: If the golem takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.
  - name: Lightnig Absorption
    desc: Whenever the golem is subjected to lightning damage, it takes no damage and instead regains a number of hit points equal to the lightning damage dealt.
  - name: Malformed Monstrosity
    desc: When the golem takes 15 or more damage in a single attack, one of its arms is destroyed and it can no longer use its multiattack. If it is hit by a second attack that deals 15 or more damage, it loses its second arm and can only use its bite attack.
  - name: Loot
    desc: 2 Rotten Flesh (1d6 ration with poison effect each), 1 Golem Core
actions:
  - name: Multiattack
    desc: The golem makes two Slam attacks each turn.
  - name: Slam
    desc: _Melee Weapon Attack:_ +4 to hit, reach 5 ft., one target. _Hit:_ 11 (2d8 + 2) bludgeoning damage.
  - name: Bite
    desc: _Melee Weapon Attack:_ +4 to hit, reach 5 ft., one target. _Hit:_ 7 (2d4 + 2) piercing damage.
```
