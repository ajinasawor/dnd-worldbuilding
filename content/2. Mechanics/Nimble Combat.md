---
title: Nimble Combat
draft: true
tags:
  - homebrew
  - playtesting
  - rule
---
Saat combat didalam [[Fragmented Dungeon|Dungeon]], player akan menggunakan mekanik Nimble Combat yang berbeda dengan Core mechanic dari Combat D&D 5e. 
# Rule dasar
Diambil dari core rule Nimble TTRPG dengan modifikasi.
## Hit Points & Dying
Ketika Hit Point Mencapai 0 (nol), Player mendapatkan 1 level Wound dan mendapatkan status Dying. Ketika Level Wound mencapai maksimal, Player mendapatkan status Fragmented.
![[Conditions & Diseases#Dying]]
![[Conditions & Diseases#Wounded]]
![[Conditions & Diseases#Fragmented]]
![[Conditions & Diseases#Shattered]]
## Attack Roll Modification & Damage Bonus
Semua serangan tidak memerlukan [[#Attack|Attack roll]], sehinga semua Spell, Feat, dan Trait yang memberikan efek pada attack roll akan dikonversi menjadi damage bonus.
- Spell, Feat, dan Trait yang memberikan bonus pada Attack Roll, seperti spell Bless dan feat Archery, akan memberikan bonus damage pada primary dice roll (maksimal sebesar nilai tertinggi dice), dan dikalkukasi sebelum penentuan MISS/HIT/CRIT (dapat mengubah roll MIS menjadi HIT, atau menyebabkan roll HIT menjadi CRIT).
- Spell, Feat, dan Trait yang memberikan efek reroll, akan memberikan reroll pada primary dice jika roll pertama MISS, atau bisa reroll semua dice untuk mendapatkan kesempatan total damage yang lebih besar (player yang melakukan reroll harus menggunakan hasil roll yang baru).
- Spell, Feat, dan Trait yang memberikan ADV, atau menghilangkan DIS, bekerja seperti normal dengan mekanisme [[#Advantage/Disadvantage]].
- Spell, Feat, dan Trait yang memberikan extra damage, ditambahkan diakhir kalkulasi total damage jika serangan tidak MISS.

> [!example] Contoh
> 1.  Seorang Ranger dengan feat Archery mendapatkan +2 bonus pada Attack roll menyerang dengan Crossbow (1d8 piercing), roll 6. +2 bonus Attack roll ditambahkan pada roll primary dice, menjadi total 8. CRIT! roll kedua 6. Total damage 8 + 6 = 14 Piercing damage.
> 2. Seorang Barbarian dengan feat Great Weapon Master, memberikan extra damage sebesar proficiency bonus (PB +2) saat menggunakan heavy weapon menyerang dengan great axe (1d12 Slashing), roll 1. MISS. extra damage dari Great Weapon Master tidak tertrigger karena serangan berakhir MISS.


## Advantage/Disadvantage
- Advantage (ADV) mendapatkan tambahan roll 1 dadu, eliminasi  dadu terendah
- Disadvantage (DIS) mendapatkan tambahan roll 1 dadu, eliminasi dadu tertinggi
- ADV & DIS dapat ditumpuk.

> [!info] Penjelasan
> Jika attack mendapatkan 2 ADV, dan 1 DIS, total attack akan mendapatkan 1 ADV

## Resting
### Field Rest 
#### Catch a Breath 
- Membutuhkan waktu minimal 10 menit / 3 ronde. Jika dilakukan saat combat, player harus diam, tidak bergerak, dan tidak terlihat musuh.
- Efek : Memulihkan sejumlah Hit Points dengan memakai 1 [[Hit Dice]] dan menghilangkan status [[Dying]]
- Gagal memberikan efek jika terkena serangan, berpindah tempat, atau terlihat musuh.

> [!success] Rumus
> HP= Roll Hit Dice + CON modifiier

#### Short Rest 
- Membutuhkan waktu minimal 1 jam, tidak bisa dilakukan saat combat.
- Efek : Memulihkan HP dengan memakai sejumlah Hit Dice. Menghilangkan status [[Dying]] dan menghilangkan 2 [[Wound]]
- Mengembalikan semua Spell, Ability, Item slot, dan efek yang memiliki syarat short rest
### Safe Rest / Long Rest
- Membutuhkan waktu minimal 8 jam, dan dilakukan di tempat yang aman yang dipilih [[Dungeon Master|DM]]. 
- Sama dengan mekanisme [[Long Rest]] normal D&D 5e
## Starting Combat
- Combat encounter dimulai saat [[Dungeon Master|DM]] mengatakan "Roll initiative!". Setiap player melempar 1d20 + Initiative Modifier untuk menetukan jumlah Action Point yang didapatkan pada ronde pertama. Player selalu menyerang pertama.
- Urutan serangan player dimulai dari player yang lebih dulu siap menyerang, giliran player selanjutnya sesuai arah jarum jam.

|  Roll Initiative  | AP pada Ronde 1 |
| ---------------   | --------------- |
| 1 digit           | 1 AP            |
| 2 digit (under 20)| 2 AP            |
| 20+               | 3 AP            |

- Combat line up ada 2 jenis. Zipline dan Basic, dan yang menentukan adalah [[Dungeon Master|DM]]

| Zipline | lineup | Basic   | lineup |
|:-------:|:------:|:-------:|:------:|
| Player1 |        | Player1 |        |
|         | Enemy1 | Player2 |        |
| Player2 |        |         | Enemy1 |
|         | Enemy2 |         | Enemy2 |

## Heroic Actions
### Attack
Damage [[#Attack Roll Modification & Damage Bonus|selalu hit]], kecuali pada roll damage player roll 1, maka attack MISS dan attack tidak memberikan efek. (attack yang membutuhkan lebih dari satu dice, dice paling kiri disebut sebagai [[Primary dice]] yang digunakan untuk menentukan MISS/HIT/CRIT). Attack/Spell yang membutuhkan Ability/DC Saving Throw, bekerja seperti normal. 
#### Spellcasting
Casting Leveled Spell membutuhkan 2 AP. Casting Cantrip membutuhkan 1 AP. [[#Rushed Attacks]] rule tetap berlaku.
#### Exploding Critical Hits
Rolling angka tertinggi dice pada [[Primary dice]] memberikan CRIT. Roll [[Primary dice]] lagi dan tambahkan kedalam total damage. CRIT dapat bertumpuk.

> [!example] Exploding Critical Hits
> Player menyerang dengan senjata berkekuatan 2d8. Roll Damage!
> - dadu menunjukkan  8(primary dice), 5. CRIT!
> - player melempar 1d8 primary dice, menunjukkan angka 8. CRIT!
> - player melempar 1d8 primary dice lagi, menunjukkan angka 1. 
> - total damage : 8+5+8+1 = 22 damage!
> - Note : roll MISS hanya diberlakukan pada roll pertama primary dice.

#### Rushed Attacks
Player dapat menyerang lebih dari 1 kali, namun serangan selanjutnya mendapatkan disadvantage. 
Efek ability yang memberikan bonus action, atau multi attack akan mengunakan 1 AP untuk semua rangkaian serangan tambahan, dengan disadvantage yang bertumpuk.

> [!example] Multi Attack
> - [[Fighter]] lv. 20 mendapatkan [[Extra Attack]] hingga total 4. Urutan kalkulasi action/damage sebagai berikut:
> - **Action 1 (1AP)**: melakukan Attack dasar dengan weapon. Mengaktifkan feat [[Extra Attack]]
> - **Action 2 (1AP)**: melakukan attack dari feat Extra Attack dengan disadvantage bertumpuk
> - extra attack 1 : 1 DIS
> - extra attack 2 : 2 DIS
> - extra attack 3 : 3 DIS
> - extra attack 4 : 4 DIS
> - **Action 3 (1AP)**: melakukan Attack dasar kembali dengan weapon. Tidak dapat mengaktifkan feat Extra Attack karena AP slot sudah habis di ronde ini. Attack memliki 2 DIS karena merupakan aksi ke 3 dalam 1 turn ini.

### Move
Player bisa bergerak hingga Speed. Karakter yang memiliki fitur dash sebagai bonus action, otomatis dianggap sebagai bagian dari aksi Move. 1 aksi Move dapat dibagi menjadi pergerakan diantara beberapa aksi Attack / Rushed attack.

> [!example] Contoh
> Player (speed 30ft) menggunakan Move (1 AP) untuk bergerak 15 ft mendekati musuh, lalu menggunakan aksi Attack (1 AP) untuk menyerang musuh tersebut, lalu bergerak 15 ft lagi ke musuh kedua, dan melakukan aksi Rush attack (1 AP) pada musuh tersebut.

### Assess
Dengan melakukan [[Ability Check]], player bisa melakukan salah satu dari aksi berikut:
- **Memberikan pertanyaan**. Berkaitan dengan weakness, ability, strategi musuh, kondisi lingkungan, dll.
- **Membuat celah serangan pada musuh**. +1 roll primary dice terhadap musuh pada ronde ini.
- **Mengantisipasi bahaya**. -1 roll primary dice terhadap player pada ronde ini.
### Use Item/Interact with object
Player dapat menggunakan consumable, berinteraksi dengan objek, atau memasang jebakan dalam combat dengan menggunakan 1 AP. Maksimal 1 aksi/ronde. Tergantung kompleksitas jebakan, mungkin player perlu menghabiskan hingga 3 AP, atau perlu bantuan player lain untuk menyelesaikan jebakan yang dibuat.
### Ready Action
Ready action adalah aksi yang dipersiapkan player di akhir giliran sebagai reaksi saat giliran musuh. Ready action menggunakan 1 AP pada giliran player, dan menyebabkan player tidak dapat melakukan Heroic Reactions hingga giliran selanjutnya.

> [!example] Contoh
> - Player bersiap untuk menarik pemicu (1 AP) apabila musuh berjalan melewati Bear Trap yang sudah dipersiapkan sebelumnya. Hingga giliran player berikutnya, player tidak bisa menggunakan Heroic Reactions. 
> - Jika Ready action melibatkan penggunaan Spell Slot, spell slot tidak akan terpakai jika Ready Action tidak teresolusi hingga giliran player berikutnya.


## Heroic Reactions
Dengan mengurangi 1 AP pada giliran selanjutnya, player dapat menggunakan Heroic Reactions pada giliran player lain atau musuh, maksimal 1 Heroic Reactions tiap player tiap ronde.
### Defend
[[Armor Class]] (AC) akan dikoversikan sebagai Armor yang bertindak sebagai defensif aktif untuk mengurangi total damage yang diterima ([[Damage Reduction]]) saat player menggunakan reaksi Defend. Jumlah pengurangan damage sebesar total AC player (pengurangan damage tidak bisa dibawah nol, kecuali akibat efek khusus)
### Interpose
Dalam radius 10ft, player dapat mengcover player lain saat diserang musuh. Player yang melakukan reaksi Interpose akan terkena serangan dan memindahkan karakter target di 1 area kosong radius 5 ft sekitar player.
### Opportunity Attack
Player dapat melakukan opprotunity attack dengan DIS jika musuh bergerak menjauh atau menyerah player lain saat dalam jangkauan melee attack.
### Help
Player dapat memberikan ADV pada roll karakter lain (maksimal 1 help per roll) jika mampu menjelaskan secara rasional kepada DM. DM dapat meminta player melakukan skill check atau memberikan ADV secara otomatis tergantung seberapa kreatif ide dari player.
## Free Action
Player dapat melakukan aksi sederhana (membuka pintu yang tidak terkunci, menjatuhkan item, memberikan item ke karakter lain, menyelesaikan konsentrasi) satu kali tiap giliran.

