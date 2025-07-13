---
title: Session Notes
draft: true
tags:
  - notes
  - session
---
# Hook
Kalian mendapatkan e-mail iklan sayembara sebagai play tester game dari suatu perusahaan VR baru, Void-walk Entertainment, yang memberikan hadiah sejumlah uang dan bonus 1 set VR headset terbaru, [[Void Render Helmet|Void Render Helmet v.2 (DRG-0V4)]] collector edition! bagi tim yang beruntung. 
Tugas Anda:
1. Temukan password debugger #-REDACTED- 
2. Uji batas realitas Draggonova, semakin banyak bug yang kamu temukan semakin baik!

# Lokasi
![[Arkhe]]
![[Fragmented Dungeon]]

# NPC
1. [[C.L.A.R.A]]
2. [[GM Asmodey]]

# Plot Encounter  
## Encounter 1
Player login kedalam game, player dihadapkan pada login screen game D.E.D. Pada log in screen terdapat judul game "Dragon Essence Dungeons alpha v.25.07.1" , dengan 4 ekor naga, tombol START GAME, GM HELP.

Jika player mencoba menanyakan salah satu dari 4 naga, naga akan menjawab. 
> "Selamat datang di Kontinen Draconia. Bantu para naga menyelesaikan permainan mereka!"

Jika player mencoba menyentuh judul game, 
> Normal screen title akan fade away, lalu muncul screen baru, berwarna merah eror dan muncul "D.E.D ahead. you have been warned." dan player otomatis masuk ke dalam game.

Jika player menekan tombol GM HELP. akan ada respon auto reply dari bot bernama CLARA,
> "Mohon maaf, semua GM sedang tidak bisa diganggu, silakan tekan START GAME untuk masuk."

Setelah player log in, player disambut oleh NPC [[C.L.A.R.A]]
> "Selamat datang para player! Selamat datang di Draconia! Kalian sekarang berada di Arkhe Dragon stone, salah satu kota terbesar di Draconia. Apakah kalian siap menjalani quest?" 

Di kejauhan, kalian mendengar suara sekelompok orang berteriak, menjerit kesakitan, dan sepeti meminta tolong. Namun suaranya terdengar sangat samar, kalian tidak mampu memahami apa yang mereka katakan.

> Jika player bertanya: [[C.L.A.R.A]] menjawab, "Oh, suara itu berasal dari sector Void-07. Itu hanyalah..... bug! Ya, itu hanya bug. Coba aku matikan audionya supaya kalian lebih tenang." Lalu CLARA membuka interface command prompt, dan suara itu hilang. "Selesai! Apakah kalian siap untuk menjalani quest?"

## Encounter 2
Player masuk ke dalam dungeon. terdapat 3 level randomly generated dungeon.
Jika berhasil disarm trap / menyelesaikan puzzle / menyelesaikan riddle / membunuh semua monster, di tiap ruangan akan ada treasure chest berisikan fragment card password debugger. Player juga bisa mencatat semua fenomena yang dianggap sebagai bug. jika berhasil mendapatkan 5 bug, party akan mendapatkan bonus 1 AP pada Boss room, yang bisa dipakai kapan pun selama combat. Action bonus ini tidak akan bisa terkena DIS, dan Attack akan otomatis CRIT.
## Encounter 3
Boss Room. Setelah selesai melawan bos, player bisa input password debugger untuk masuk ke debug console dan bertemu CLARA. 
Jika fragment card lengkap:
>CLARA, "Selamat para player! Kalian berhasil mengumpulkan ketiga fragment dari Password card. Kalian bisa mengakses Debug console ini." lalu debug console muncul dari tembok di ujung ruangan. 

Jika fragment card tidak lengkap:
>CLARA, "Selamat! kalian sudah mencapai ujung dungeon. apakah kalian berhasil mengumpulkan semuja fragmen Password card? Hmmm? Sayang sekali, kalian tidak dapat mengakses Debug Console secara penuh. Tapi tidak apa-apa, sini aku tunjukkan isi dari debug console ini, walaupun aksesnya terbatas." CLARA menunjukkan fungsi debug console. ditengah-tengah demonstrasi, CLARA mengaktifkan efek Zero Gravity, dan juga memunculkan Black hole di tengah ruangan. CLARA, "Seru kan? Seru kan? Seru kan? ...". suara CLARA berulang ulang, hingga mengalami bug, suara terdengar ganda dan pitch menurun, Visual CLARA bugged, menjadi texture merah dan tertutupi tulisan SYSTEM OVERLOAD. Semua player terhisap kedalam black hole, blackhole memberikan damage DoT 1 HP/detik hingga mencapai player tinggal 1 HP, lalu party glitch out keluar dari Dungeon.
# Notes

# Loot
3 Fragment card Password debugger: 
1. DR4G
2. 0NOV
3. 4_DEB

Game Bugs:
1. Bug Visual
2. Bug Audio
3. Bug Game play
4. Bug Performance
5. Bug Crash
6. Bug Interaksi
7. Bug logika

# Cliffhanger
Setelah keluar dari Dungeon, player akan kembali ke [[Arkhe]] dan bertemu dengan [[GM Asmodey]].
> GM Asmodey, "Oh! halo halo! Akhirnya aku bertemu dengan kalian. Kalian kemana saja? aku cari kemana-mana dari tadi! Tapi salahku juga sih, tadi aku terlambat karena ada critical bug yang harus aku perbaiki sebelum menemui kalian. Ehem. Oke. Uhhhh, dimana dialog cardku tadi. Oh ini! Selamat datang di play testing Dragon Essence Dungeons! apakah kalian siap menerima quest?"

Jika player kebingungan dan menanyakan CLARA:
> GM Asmodey, "CLARA? tapi CLARA masih dalam tahap pengembangan dan belum bisa diakses. Apakah kalian yakin?"

Jika player menunjukkan Password card / Fragmentnya dan GM Asmodey mencoba menggunakannya untuk mengakses debugging console, tiba-tiba langit warna merah dan muncul warning dialog di seluruh permukaan.
> WARNING! SYSTEM OVERLOAD! WARNING! SYSTEM OVERLOAD!
> GM Asmodey, "Sial! Apakah ini ulah kalian?! Sial! Apa yang kalian laku-"

Player disconnect dari game, kembali ke dunia nyata. Tapi, apakah itu benar dunia nyata mereka?
End.