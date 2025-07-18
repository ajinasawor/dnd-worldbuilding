---
title: Chrono Slime
draft: true
tags:
  - CR2
  - Time-AL
  - nimble
  - homebrew
---
```statblock
layout: Basic 5e Layout
name: Chrono Slime
size: medium
type: monstrosity
alignment: neutral evil
ac: 12
hp: 45 (6d8 +18)
hit_dice: 6d8 +18
speed: 20 ft., burrow 10 ft.
stats: [16,6,16,1,16,1]
damage_vulnerabilities: Thunder
damage_resistances: Cold, Radiant
condition_immunities: Blinded, Deafened, Exhaustion
senses: Blindsight 60 ft.
languages: 
cr: 2
traits:
  - name: Temporal Ooze
    desc: saat mati, creature meledak radius 10 ft., creature di area harus melakukan DC 12 DEX save. jika gagal akan kehilangan 1 AP di ronde selanjutnya.
  - name: Time-Slip (1 AP)
    desc: reaksi saat terkena serangan. Teleport 5 ft ke lokasi yang tidak terjangkau
  - name: Move pattern
    desc: Time Slip if attacked-Move-Psudopod. Rewind Slime on 30% HP
  - name: Loot
    desc: 10% Chronal Goo (Material)
actions:
  - name: Psudopod (1 AP)
    desc: reach 10 ft., +4 to hit, 5 (1d6 + 2) Bludeoning + 2 (1d4) cold damage. Korban harus melakukan DC 12 CON save atau kecepatan berkurang 10 ft. hingga akhir ronde berikutnya.
  - name: Rewind Slime (2 AP)
    desc: pulihkan 10 (1d10 + 5) HP
```
