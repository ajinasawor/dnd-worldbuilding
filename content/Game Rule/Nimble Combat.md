---
title: Nimble Combat
draft: false
tags:
  - homebrew
  - playtesting
  - rule
---
Saat combat didalam [[Black Shard|Dungeon]], player akan menggunakan mekanik Nimble Combat yang berbeda dengan Core mechanic dari Combat D&D 5e. 
# Rule dasar
Diambil dari core rule Nimble TTRPG dengan modifikasi.
## Hit Points & Dying
- Ketika Hit points (HP) mencapai 0, karakter mendapatkan 1 [[Wound]], dan mendapat status [[Dying]]. Player  yang memiliki [[Wound]] akan medapatkan disadvantage saat melakukan [[#Heroic Actions]]. Player dengan status [[Dying]] tidak bisa berpindah tempat tanpa bantuan player lain, dan hanya dapat melakukan melakukan 1 aksi, yaitu:
	- Attack/Casting Spell : mengakibatkan 1 [[Wound]], kecuali berhasil melakukan DC 10 STR save
	- Terkena serangan akan mendapatkan 2 [[Wound]], CRIT mengakibatkan 3 [[Wound]].
	- [[Dying]] akan menghilangkan aggro musuh, kecuali saat melakukan Attack/Casting Spell
	Ketika player mendapatkan 6 [[Wound]], mereka mati ([[Death|teleport kembali ke Arkhe]])
	Note: spell/item yang terlibat dalam mekanik Healing, Death Saving Throw & Revive akan mendapatkan [[Heal & Revive|penyesuaian efek]].
## Advantage/Disadvantage
- Advantage (ADV) mendapatkan tambahan roll 1 dadu, eliminasi  dadu terendah
- Disadvantage (DIS) mendapatkan tambahan roll 1 dadu, eliminasi dadu tertinggi
- ADV & DIS dapat ditumpuk.

> [!info] Penjelasan
> Jika attack mendapatkan 2 ADV, dan 1 DIS, total attack akan mendapatkan 1 ADV

## Resting
### Field Rest 
#### Catch Breath 
- Membutuhkan waktu minimal 10 menit / 3 ronde, jika dilakukan saat combat, player harus diam, tidak bergerak, dan tidak terlihat musuh.
- Efek : Memulihkan HP dengan memakai 1 [[Hit Dice]]. Menghilangkan status [[Dying]], dan mengurangi 1 [[Wound]].
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
- Combat line up ada 2 jenis. Zipline dan Basic, dan yang menentukan adalah [[Dungeon Master|DM]]

| Zipline | lineup | Basic   | lineup |
| ------- | ------ | ------- | ------ |
| Player1 |        | Player1 |        |
|         | Enemy1 | Player2 |        |
| Player2 |        |         | Enemy1 |
|         | Enemy2 |         | Enemy2 |

## Heroic Actions
### Attack
Damage [[Attack Hit Roll|selalu hit]], player langsung roll damage, jika player roll 1, maka attack MISS dan attack tidak memberikan efek. (attack yang membutuhkan lebih dari satu dice, dice paling kiri disebut sebagai [[primary dice]] yang digunakan untuk menentukan MISS/CRIT). Attack/Spell yang membutuhkan Musuh melakukan Ability/DC Saving Throw, bekerja seperti normal. 
#### Exploding Critical Hits
Rolling angka tertinggi dice pada [[primary dice]] memberikan CRIT. Roll [[primary dice]] lagi dan tambahkan kedalam total damage. CRIT dapat bertumpuk.

> [!example] Exploding Critical Hits
> Player menyerang dengan senjata berkekuatan 2d8. Roll Damage!
> - dadu menunjukkan  8(primary dice), 5. CRIT!
> - player melempar 1d8 primary dice, menunjukkan angka 8. CRIT!
> - player melempar 1d8 primary dice lagi, menunjukkan angka 1. 
> - total damage : 8+5+8+1 = 22 damage!
> - Note : roll MISS hanya diberlakukan pada roll damage awal.

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
Player bisa bergerak hingga Speed. Dash dianggap melakukan Move 2 kali (2 AP), jika karakter memiliki bonus speed akibat dash, maka efek bonus speed akan diberlakukan pada Move action kedua. 1 aksi Move dapat dibagi diantara aksi Attack/Rush attack.

> [!example] Contoh
> Player (speed 30ft) menggunakan Move (1 AP) untuk bergerak 15 ft mendekati musuh, lalu menggunakan aksi Attack (1 AP) untuk menyerang musuh tersebut, lalu bergerak 15 ft lagi ke musuh kedua, dan melakukan aksi Rush attack (1 AP) pada musuh tersebut.

### Assess
Dengan melakukan DC 12 skill check, player bisa melakukan salah satu dari aksi berikut:
- **Memberikan pertanyaan**. Berkaitan dengan weakness, ability, strategi musuh, kondisi lingkungan, dll.
- **Membuat celah serangan pada musuh**. +1 roll primary dice terhadap musuh pada ronde ini.
- **Mengantisipasi bahaya**. -1 roll primary dice terhadap player pada ronde ini.
### Use Item/Interact with object
Player dapat menggunakan consumable, berinteraksi dengan objek,, atau memasang jebakan dalam combat dengan menggunakan 1 AP. maksimal 1 aksi/ronde. Tergantung kompleksitas jebakan, mungkin player perlu menghabiskan hingga 3 AP, atau perlu bantuan player lain untuk menyelesaikan jebakan yang dibuat.
### Ready Action
Ready action adalah aksi yang dipersiapkan player di akhir giliran sebagai reaksi saat giliran musuh. Ready action menggunakan 1 AP pada giliran player, dan menyebabkan player tidak dapat melakukan Heroic Reactions hingga giliran selanjutnya.

> [!example] Contoh
> - Player bersiap untuk menarik pemicu (1 AP) apabila musuh berjalan melewati Bear Trap yang sudah dipersiapkan sebelumnya. Hingga giliran player berikutnya, player tidak bisa menggunakan Heroic Reactions. 
> - Jika Ready action melibatkan penggunaan Spell Slot, spell slot tidak akan terpakai jika Ready Action tidak teresolusi hingga giliran player berikutnya.


## Heroic Reactions
Dengan mengurangi 1 AP pada giliran selanjutnya, player dapat menggunakan Heroic Reactions pada giliran player lain atau musuh, maksimal 1 Heroic Reactions tiap player tiap ronde.
### Defend
[[Armor Class]] (AC) akan dikoversikan sebagai Armor yang bertindak sebagai defensif aktif untuk mengurangi total damage yang diterima ([[Damage Reduction]]) saat player menggunakan reaksi Defend.

| Jenis Armor              | Defence Dice | Armor Class (AC)    |
| ------------------------ | ------------ | ------------------- |
| Unarmored                | 1d4          | 11 or lower         |
| Light armor              | 1d6          | 12-14               |
| Medium armor             | 1d8          | 15-17               |
| Heavy armor              | 1d10         | 18-20               |
| DEX modifier +3 or above | +1 DR        | every 3 AC above 20 |
| Shield                   | +1 DR        |                     |
| Magic Shield (+1/+2/+3)  | +x DR        |                     |
- Class Feature, Racial Traits, atau Spell yang mengubah teknis perhitungan AC (seperti unarmored defense, mage armor, dan barkskin), tetap berlaku, dengan mereferensikan total akhir AC pada tabel.
- Class Feature, Racial Traits, Spell, Equipment selain armor, dan Consumables yang memiliki efek memberikan bonus AC akan dikonversikan menjadi flat DR sejumlah Bonus AC/2 (pembulatan kebawah, minimal +1 DR)
> [!important] Perhitungan Damage Reduction (DR)
> DR = Jenis armor /total AC (pilih salah satu yang tertinggi) + flat DR
### Interpose
Dalam radius 10ft, player dapat mengcover player lain saat diserang musuh. Player yang melakukan reaksi Interpose akan terkena serangan dan memindahkan karakter target di 1 area kosong radius 5 ft sekitar player.
### Opportunity Attack
Player dapat melakukan opprotunity attack dengan DIS jika musuh bergerak menjauh atau menyerah player lain saat dalam jangkauan melee attack.
### Help
Player dapat memberikan ADV pada roll karakter lain (maksimal 1 help per roll) jika mampu menjelaskan secara rasional kepada DM. DM dapat meminta player melakukan skill check atau memberikan ADV secara otomatis tergantung seberapa kreatif ide dari player.
## Free Action
Player dapat melakukan aksi sederhana (membuka pintu yang tidak terkunci, menjatuhkan item, memberikan item ke karakter lain, menyelesaikan konsentrasi) satu kali tiap giliran.