---
title: Dungeon Generator
draft: true
---
# PILIH BOSS ROOM
Ambil 1 kartu Boss (K&A). terdapat 4 Alignment dan 2 variant Boss per Alignment

| Kartu | Boss           | Kartu | Boss           |
| ----- | -------------- | ----- | -------------- |
| ♥K    | Chaos Moderate | ♠K    | Time Moderate  |
| ♥A    | Chaos Hard     | ♠A    | Time Hard      |
| ♦K    | Order Moderate | ♣K    | Space Moderate |
| ♦A    | Order Hard     | ♣A    | Space Hard     |
 ^boss-alignment-table
 
Ambil 1 kartu terrain. Terdapat 4 terrain berdasarkan jenis suit kartu.

| Suit | Jenis Terrain           | Naratif                                                                                                           | Efek                                                                                                                                                                                                           |
| ---- | ----------------------- | ----------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ♥    | Chaos (Chaos Rift)      | Ruangan gelap, hanya diterangi oleh lava yang berkilau emas dan meletup-letup kecil.                              | setiap 3 turn, akan muncul Glitch hound (HP 5 Bite 1d4 Piercing). posisi random                                                                                                                                |
| ♦    | Order (Order Nexus)     | Ruangan dengan tile metal, dan terdapat 4 laser yang hidup secara periodik. Laser tidak dapat dihancurkan.        | setiap 3 turn, laser akan hidup memberikan 1d6 radiant damage pada semua creature yang berda di jalurnya. PC harus melakukan DEX save DC 10 untuk menghindarinya.                                              |
| ♠    | Time (Temporal Archive) | Ruangan berdindingkan cermin, dan tampak seperti lorong tanpa akhir.                                              | Setiap 3 turn player melakukan WIS save DC 10, jika gagal maka akan mendapatkan DIS pada roll selanjutnya. Player bisa bergerak menembus dinding, dan akan ter teleportasi pada dinding yang berlawanan arah.  |
| ♣    | Space (Void Abyss)      | Ruangan gelap, tanpa akhir, yang ditengahnya terdapat black hole yang akan menghisap segala sesuatu disekitarnya. | Setiap 3 turn, player melakukan STR save DC 10, jika gagal akan tertarik 5 ft ke arah black hole. player terkena 1d10 force damage jika masuk ke dalam black hole. dan memerlukan STR save DC 15 untuk keluar. |
^terrain-table

Ambil 1 kartu efek. akan memberikan BUFF/DEBUFF pada PC sesuai dengan suit dan nilai kartu. 

| Suit | Nilai | Efek             | Suit | Nilai | Efek          |
| ---- | ----- | ---------------- | ---- | ----- | ------------- |
| ♥    | 2-6   | temp HP + 2 x lv | ♠    | 2-6   | -1 AP 1 round |
| ♥    | 7-10  | temp HP + 3 x lv | ♠    | 7-10  | -1 AP 2 round |
| ♥    | JQKA  | temp HP + 4 x lv | ♠    | JQKA  | -1 AP 3 round |
| ♦    | 2-6   | +1 AP 1 round    | ♣    | 2-6   | 1 DIS 1 round |
| ♦    | 7-10  | +1 AP 2 round    | ♣    | 7-10  | 1 DIS 2 round |
| ♦    | JQKA  | +1 AP 3 round    | ♣    | JQKA  | 1 DIS 3 round |
^pc-encounter-buff-debuff-effect-table

# TENTUKAN DEPTH DUNGEON
Depth = total room sebelum memasuki Boss room. Depth 3 berarti ada 3 room yang harus dilewati player sebelum memasuki Boss Room.

# TENTUKAN TERRAIN DUNGEON
Ambil 1 kartu terrain. Terdapat 4 terrain berdasarkan jenis suit kartu.

![[#^terrain-table]]

# TENTUKAN KONTEN DUNGEON
Ambil 1 kartu Content. Tipe konten dungeon ditentukan berdasarkan Value kartu, jumlah pintu untuk menuju ruang selanjutnya ditentukan oleh suit kartu.

| Nilai | Kategori          | Konten                                                                                                                                                                              |
| ----- | ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2&3   | Loot Minor        | Ruang kosong dengan Chest ditengahnya. Berisikan minor loot, mungkin ada item quest                                                                                                 |
| 4-10  | Monster Encounter | Monster Encounter difficulty : easy(4-6)-moderate(7-10). Pintu tidak terkunci. player bisa escape tapi tidak bisa mendapatkan loot.                                                 |
| J     | Puzzle Room       | Pintu selanjutnya terkunci. Time sensitive, jika melewati batas waktu, akan muncul monster, clue/item quest hilang/rusak.                                                           |
| Q     | Trap Room         | Pintu selanjutnya tidak terkunci, tetapi diselimuti trap. Trap bisa memunculkan monster, hazard, perubahan terrain.                                                                 |
| K     | Riddle Room       | Ruang/lorong kosong, dengan pintu yang terkunci. bisa encounter dengan NPC atau CLARA, drop lore atau Efek Naratif.                                                                 |
| A     | Safe Zone         | PC bisa menghubungi CLARA, Crafting, dan Short Rest. Jika Item quest sudah lengkap bisa submit lebih awal, dan otomatis melawan Boss di room selanjutnya untuk keluar dari Dungeon. |
| Joker | Wild Glitch       | Ruang dengan 2 efek suit sekaligus. (Monster Encounter  + Puzzle/Trap/Riddle)                                                                                                       |
^content-dungeon-table

# TENTUKAN ROOM EFFECT
Ambil 1 kartu efek. akan memberikan BUFF/DEBUFF pada PC sesuai dengan suit dan nilai kartu. 

![[#^pc-encounter-buff-debuff-effect-table]]

Jika tipe room bukan jenis encounter monster, makan efeknya sebagai berikut:

| Suit | Nilai | Efek                            | Durasi |
| ---- | ----- | ------------------------------- | ------ |
| ♥♦   | 2-6   | 1 ADV on checks & saving throws | 1 x    |
| ♥♦   | 7-10  | 1 ADV on checks & saving throws | 2 x    |
| ♥♦   | JQKA  | 1 ADV on checks & saving throws | 3 x    |
| ♠♣   | 2-6   | 1 DIS on checks & saving throws | 1 x    |
| ♠♣   | 7-10  | 1 DIS on checks & saving throws | 2 x    |
| ♠♣   | JQKA  | 1 DIS on checks & saving throws | 3 x    |
^pc-puzzle-trap-riddle-effect-table

Jika mendapatkan Joker, maka PC mendapatkan full heal HP, dan mendapatkan mengembalikan 2 spell slot/prepared spell yang sudah terpakai.

# TENTUKAN ROOM ANOMALI
Dari kombinasi 3 kartu di Dungeon Room dan Boss Room, jika membentuk kombinasi tertentu, akan memberikan room anomali.

| Kombinasi   | Contoh   | Anomali         | Efek                                                                                                                                                |
| ----------- | -------- | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pair        | ♠6,♣6,♣4 | Directed Attack | Player hanya bisa menyerang lurus. tidak bisa menyerang diagonal                                                                                    |
| 3 of a Kind | ♠5♥5♦5   | Unstable Floor  | Setiap player bergerak, harus melakukan DEX save DC 10. Jika gagal maka terkena [[Conditions & Diseases#Prone\|prone]]                              |
| Flush       | ♥6♥7♥J   | Low Gravity     | PC mendapatkan free action untuk bergerak vertikal, dan bisa berjalan di langit langit. PC bisa bergerak melayang namun half speed.                 |
| Straight    | ♥8♥9♦10  | Time Dilation   | Waktu berjalan lambat bagi player, player hanya bisa melakukan reaction setiap 2 turn, Rushed attack memiliki tambahan 1 DIS, Speed berkurang 10ft. |
| Royal Flush | ♦9♦10♦J  | Double effect   | Kombinasi 2 dari 4 anomali dalam 1 ruang, namun tiap efek tidak sekuat anomali normal.                                                              |
^anomali-effect-table

 
