---
title: Nimble Combat
draft: false
tags:
  - homebrew
  - playtesting
---
# Rule dasar
Diambil dari core rule Nimble TTRPG dengan modifikasi.
## Hit Points & Dying
- Ketika Hit points (HP) mencapai 0, mendapatkan 1 [[Wound]], dan mendapat status [[Dying]]. Player dengan status [[Dying]] hanya dapat melakukan melakukan 1 aksi, yaitu:
	- Attack/Casting Spell : mengakibatkan 1 [[Wound]], kecuali berhasil melakukan DC 10 STR save
	- Terkena serangan akan mendapatkan 2 [[Wound]], CRIT mengakibatkan 3 wound.
	- Dying akan menghilangkan aggro musuh, kecuali saat melakukan Attack/Casting Spell
	Ketika player mendapatkan 4 wound, mereka mati ([[Death|teleport kembali ke Arkhe]])
## Advantage/Disadvantage
- Advantage (ADV) mendapatkan tambahan roll 1 dadu, eliminasi  dadu terendah
- Disadvantage (DIS) mendapatkan tambahan roll 1 dadu, eliminasi dadu tertinggi
- ADV & DIS dapat ditumpuk.

> [!info] Penjelasan
> Jika attack mendapatkan 2 ADV, dan 1 DIS, total attack akan mendapatkan 1 ADV

## Resting
### Field Rest 
#### Catch Breath 
- Membutuhkan waktu minimal 10 menit / 5 ronde, jika dilakukan saat combat, player harus diam, tidak bergerak, dan tidak terlihat musuh.
- Efek : Memulihkan HP dengan memakai 1 [[Hit Dice]]. Menghilangkan status [[Dying]], dan mengurangi 1 [[Wound]].
- Gagal memberikan efek jika terkena serangan, berpindah tempat, atau terlihat musuh.
		
		$$
				HP= Roll Hit Dice + CON modifiier
		$$
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

> [!example] Exploding Critical HIts
> player menyerang dengan senjata berkekuatan 2d8. Roll Damage!
> - dadu menunjukkan  8(primary dice), 5. CRIT!
> - player melempar 1d8 primary dice, menunjukkan angka 8. CRIT!
> - player melempar 1d8 primary dice lagi, menunjukkan angka 1. 
> - total damage : 8+5+8+1 = 22 damage!
> Note : roll MISS hanya diberlakukan pada roll pertama.

#### Rushed Attacks
Player dapat menyerang lebih dari 1 kali, namun serangan selanjutnya mendapatkan disadvantage. 
Efek ability yang memberikan bonus action, atau multi attack akan mengunakan 1 AP untuk semua rangkaian serangan tambahan, dengan disadvantage yang bertumpuk.

> [!example] Multi Attack
> [[Fighter]] lv. 20 mendapatkan [[Extra Attack]] hingga total 4. Urutan kalkulasi action/damage sebagai berikut:
> **Action 1 (1AP)**: melakukan Attack dasar dengan weapon. Mengaktifkan feat [[Extra Attack]]
> **Action 2 (1AP)**: melakukan attack dari feat Extra Attack dengan disadvantage bertumpuk
> extra attack 1 : 1 DIS
> extra attack 2 : 2 DIS
> extra attack 3 : 3 DIS
> extra attack 4 : 4 DIS
> **Action 3 (1AP)**: melakukan Attack dasar kembali dengan weapon. Tidak dapat mengaktifkan feat Extra Attack karena AP slot sudah habis di ronde ini. Attack memliki 2 DIS karena merupakan aksi ke 3 dalam 1 turn ini.

### Move
Pergerakan seperti Dash, 
### Assess
### Use Item
### Ready Action

## Heroic Reactions
### Defence
- Armor Class berfungsi sebagai Damage Reduction.  AC 12 light armor full modifier, 14-17 medium no modifier, 17+ heavy no modifier + half damage.
- unarmored d4, light d6, medium d8, heavy d10, shield +1DR, DEX >=+3 +1DR, magic shield +x DR