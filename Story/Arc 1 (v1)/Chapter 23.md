---
tags:
  - chapter
title:
  - Aku Sibuk! Semua Sibuk!
---
# Chapter 23 - Aku Sibuk! Semua Sibuk!

---

**Gema**
---
Pukul 14:05. 

Kepalaku berdenyut, bukan karena tidak enak badan. Tapi karena hari ini aku dapat 20 *carryover task* lagi dari minggu lalu. Dan betapa bodohnya aku, hampir semua *carryover task* dari minggu lalu dan minggu sebelumnya berhubungan dengan *encoding decoding* audio. Kupikir ini hanya *hidden complexity* biasa. Tapi bukan *programming* namanya kalau masalahnya sesederhana itu. 

Aku berdiri dan menghadap ke seisi ruangan. "Kakak-kakak, bisa kita *meeting* sebentar? Tiga puluh menit paling lama," pintaku.

Semenit kemudian, kami semua sudah ada di ruang meeting. Aku berdiri di depan layar besar dengan laptopku di atas meja samping. 

"Aku ingin bertanya. Siapa saja yang mengerjakan protokol terkait *encoding decoding audio*?" 

Hans dan Otis mengangkat tangan.

"Ada yang ingin dikeluhkan?" Tanyaku melanjutkan.

Hans dulu yang membuka mulut. "Sepertinya protokolnya terlalu rumit, Gema. Aku tidak pernah mengerjakan protokol se-*low level* ini. Aku pun tidak tahu harus berkonsultasi pada siapa. Kamu sudah terlalu sibuk mengerjakan banyak *task* ditambah menambal kekurangan kita semua."

"Kalau menurutku. Kita terlalu melebihkan kemampuan kita sekarang," kata Otis. "*Software* ini secara keseluruhan jauh melebihi tingkat kemampuan kita semua."

Sudah kuduga. 

"Dan kamu tidak bisa terus-terusan menambal kita semua, Gema." Luna menambahkan. Aku tahu, bisa-bisa aku masuk rumah sakit kalau harus mengerjakan begitu banyak. Makanya aku mengadakan *meeting* ini.

"Kamu ada solusi, Gema?" Tanya Surya. "Mungkin pakai *third-party*, atau merancang ulang protokolnya agar lebih sederhana."

Aku menggeleng. "Tidak sesederhana itu..." Kata-kataku menggantung.

Ada solusi yang mudah untuk ini semua. Opus. *Codec* standar untuk hampir semua keperluan audio. Masalahnya adalah, Opus tidak akan ada sebelum akhir 2012. Apa aku harus mengembangkannya? Sendiri? Aku ingat algoritmanya, tapi aku tidak pernah mengembangkan *codec* sebelumnya. Dan bukan itu juga masalah terbesarnya. 

"Gema, kamu melamun," panggil Luna. Aku tersentak. Lucu, aku tidak pernah melamun di depan forum.

"Hahaha. Maaf, aku sampai mana, ya, tadi?" 

"Tidak sesederhana itu. Memang protokolnya rumit," sahut Otis. Oh, dia memperhatikanku ternyata. Keren.

"Oke, maksudku tadi bukan soal algoritmanya," jawabku. Tanganku mengetikkan beberapa kata di *search engine*. Muncul laman berjudul SILK.

"Pada dasarnya. Kita sedang membuat kompetitor dari *Skype*. Layanan VoIP terbesar saat ini. Berita bagusnya adalah, *Skype* kelabakan menghadapi koneksi internet yang tidak jelas. Panggilannya tidak stabil. Kualitas suara jelek. Apalagi kualitas gambar. Aku yakin semuanya sudah paham soal ini."

Mereka serempak mengangguk-angguk.

"Berita buruknya adalah, *Skype* ternyata sudah membuat *codec* yang cukup bagus. SILK ini adalah buatan mereka. Fakta bahwa kita bisa melakukan panggilan internet dengan koneksi menyedihkan di Indonesia saja sudah jadi bukti bahwa kompresi audionya bagus. *Skype* hanya terhambat di *network layer*, *codec*-nya sendiri bekerja. Ditambah dia spesifik dibuat untuk menangani pembicaraan manusia. Masalahnya adalah-"

"Itu tidak cukup untuk kebutuhan kita," Hans menyahut. "Kita butuh kompresi yang bahkan lebih bagus lagi, dengan rentang *bitrate* yang dinamis. Kompresi tinggi ketika koneksi buruk, kompresi rendah ketika sinyal bagus. Ditambah *packet loss handling*. Semua itu harus dilakukan dengan *overhead* CPU yang mendekati 0."

"Seratus untuk Kak Hans," pujiku sambil mengacungkan jempol. Hans benar-benar belajar untuk mengerti ini semua. Setidaknya dia dapat ilmunya walaupun *carryover task*-nya dilemparkan padaku.

"Ya sudah kita buat saja sendiri," tantang Otis. "Kita punya kepalamu, kan, Gema? Ada empat pasang tangan juga yang bisa bekerja. Masa iya kita tidak bisa mereplikasinya?" Orang ini cukup percaya diri juga. Ada otakku saja dia bisa sombong, apalagi kalau otaknya sendiri terpakai.

"Memangnya kamu tahu isi *codec*-nya, Otis?" Sanggah Luna.

"Makanya itu, Luna. Tadi aku bilang kita punya kepala Gema." Otis mempertahankan pendapatnya.

"Kamu itu. Haduh," ujar Luna mengehela napas panjang. "Kalau mau menyampaikan ide, setidaknya pakai otakmu sendiri. Jangan pinjam otak orang."

"Tak apa, Kak Luna. Ide Kak Otis sebetulnya masuk akal. Aku juga ingin melakukan hal yang sama. SILK itu gratis kalau kita mau gunakan," sanggahku.

"Nah, iya, kan? Kamu dengar dia bilang apa, Luna?" Seru Otis semangat sambil menunjuk Luna di seberang meja.

"Tapi..." Tambahku.

"Eh? Tapi apa?" Tanya Otis kaget.

"Gratis untuk pembuat perangkat. Tujuannya untuk memperluas pengguna *Skype*. Dan isinya tidak boleh dimodifikasi. Sedangkan yang kita butuhkan jelas butuh optimisasi yang sangat banyak. Belum lagi dia dilindungi paten."

Semuanya tertunduk dan terdiam. Tentu saja kita semua diam. Kita *programmer*, ini masalah hukum. Tidak ada *output* yang bisa di-*debug*. Ada dokumentasi yang bisa dibaca, tapi dalam bahasa yang tidak kita mengerti. Bahasa manusia. 

"Tapi paten itu bukan di Indonesia, kan, Gema? Harusnya kita aman asalkan tidak menargetkan negara-negara tertentu," ujar Hans memecah keheningan. 

Aku tidak tahu harus menjawab apa. Sejauh yang aku tahu, kata-kata Hans itu benar. Tapi sangat-sangat tidak relevan denganku. Impiannya terlalu kecil. "A-" 

"Kamu tidak melihat mata, Gema?" Potong Luna. "Dari awal dia tidak merencanakan produk ini hanya untuk pasar Indonesia, Hans. Gema merancang *Roundtable* untuk cakupan internasional. Betul, kan, Gema?"

Ah, Luna. Sang pembaca hati dan pikiran. Ingin kupeluk dia dan kuajak makan malam, tapi aku masih ingin hidup. Dan aku juga tidak ingin Tika menggorok lehernya. Alhasil aku hanya mengangguk. Dan kami semua kembali ke titik nol, menunduk dan diam.

"Aku punya cara," ujarku memecah keheningan sekali lagi. "Tapi kalian harus percaya padaku."

---

"Mau pulang, Gema?" Tanya Hans. Aku sedang memasukkan laptop ke dalam tasku.

"Iya, kak. Tolong *review* lima belas *commit* yang tadi kubuat, ya, kak. Sudah jam lima sore."

"Cuma lima belas? Tumben sekali."

"Iya, cuma lima belas," lalu pandanganku berpindah ke Otis yang bersembunyi di balik empat monitornya. "Karena kali ini, Kak Otis sudah paham soal *saga* dan *deadlock*, jadi kerjaanku lebih enteng," ujarku dengan suara lebih keras agar Otis dengar. Dia tidak dengar. Luna yang tertawa.

---

Ponselku berdering. Oh, Tika.

K: *Sedang apa?*

G: *Bergelantung di dalam bis. Ada apa?*

K: *Aku bosan.*

Oh, ya? Dia bosan? Mungkin hidupnya kurang konflik. Memang orang-. *Ding!*

K: *Boleh main ke rumahmu?*

G: *What? Why?*

K: *Because I'm bored, dummy.*

G: *Memangnya tidak ada mall? Atau apalah. Kota ini besar. Pasti kamu bisa dapat hiburan di tempat lain selain rumahku yang sama membosankannya.*

K: *Mau apa aku di mall? Belanja sendiri? Nonton bioskop sendiri? Menurutmu aku psikopat? Masa bodoh, aku ke rumahmu sekarang.*

G: *Wait! Tika! I've never said yes!*

Pesanku tidak dibaca lagi. Kutelfon juga tidak diangkat. *Oh, please, no.* Kalau *Mercedes* hitam itu terparkir di depan rumah... Tetangga akan mulai menggosip yang aneh-aneh besok. Belum lagi ayah dan ibu. Baru kemarin mereka bilang ajak Tika ke rumah. Sekarang dia mau datang tanpa diundang? 

Semesta ini kejam.

---

"Aku pulang," ujarku lesu ketika memasuki rumah. 

"Tumben lemas, kamu kelelahan? Mandi dan makan sana," kata ayah.

"Iya. Lumayan sulit tadi di kantor. Ditambah..."

"Hmm? Ditambah apa?"

"Ah, sudahlah. Ibuu!! Lapaaar!!"

Aku ingin menjelaskan kalau akan ada putri dari khayangan datang dengan kereta kencana. Tapi aku terlalu lelah. Yang terjadi biarlah terjadi. Aku meletakkan tasku di kamar lalu bergegas mandi dan keramas. Kota Surabaya ini tidak mengijinkan pendudukan untuk mandi kurang dari dua kali sehari. 

---

**Kartika**
---
"Tolong parkir di minimarket depan gang saja, ya, pak."

"Siap, non."

Tak lama kemudian, mobilku sudah menepi ke depan minimarket itu. Aku turun membawa tas genggamku seperti biasa. Mendengar Gema protes soal pakaian 'kasual'-ku beberapa hari lalu, sekarang aku sengaja hanya menggunakan *dress* sopan dengan lengan pendek dan rok tepat di lutut. Kalau dia protes lagi, akan kusumpal mulutnya dengan bakso.

Mau kuputar badanku dan berjalan ke rumah Gema, tapi aku baru sadar. Apa aku perlu membawa oleh-oleh, ya? Aku pasti bertemu orang tuanya. Lagipula tidak sopan, kan, kalau bertamu dengan tangan kosong?

Menit kemudian mataku kosong melihat deretan *snack* di minimarket. Aku harus beli apa??? Orang tuanya suka apa? Gema suka apa? Aku tidak pernah melihatnya makan *snack*. Argh!! Harusnya tadi aku mampir resto saja.

---

*Ding dong.*

Kutekan bel di pagar hitam itu. Tangan kananku menenteng tas plastik berisi *snack random* dan minuman dingin. Aku merasa aneh sekali bertamu seperti ini. Ah, sudahlah. 

Rumah Gema terlihat... Aku tidak tahu deskripsinya. Biasa saja? 

Pagar hitam, garasi kecil dengan dua sepeda motor, rumah sederhana saja dengan cat warna putih dan pintu kayu. Ada taman kecil di terasnya dengan pot-pot tanaman rumahan. Oh, ada cabe juga. Menggemaskan.

"Siapa, ya?" 

Aku terkaget. Aku terlalu sibuk melihat cabe-cabe lucu itu sampai tidak memperhatikan seorang wanita paruh baya mungil berambut pendek mengenakan daster keluar dari pintu. Sepertinya ibu Gema.

"Selamat malam, tante. Saya Kartika, apa Ge-"

"Oooh! Cari Gema, ya? Sini, sini, masuk," potong ibu Gema sambil tergesa membukakan pagar. "Haduh, Gema ini bagaimana. Harusnya dia memberitahuku kalau kamu akan datang. Sini, ayo masuk." Tanganku digandeng dan ditarik masuk ke garasi. "Kamu naik apa? Sendirian?"

"Saya diantar naik mobil, tante. Itu parkir di minimarket seberang," jawabku gugup sembari tertarik masuk ke rumahnya.

"Duduk, duduk situ. Diantar siapa? Ayahmu? Kenapa tidak diajak kemari? Kasihan menunggu di pinggir jalan." Sepertinya ibu Gema orang yang sangat sibuk. Sebagaimana layaknya ibu-ibu biasa. Bicaranya cepat sekali, gerakannya lincah dan gesit. Kontras sekali dengan anaknya.

"Diantar sopir saya, tante. Tidak apa-apa, biasanya memang menunggu di dekat mobil, kok."

Lalu ibu Gema diam. Ah, kusebut tante saja, ribet sekali menyebut 'ibu Gema'. Lalu tante diam, seperti menyadari sesuatu. Aduh, aku menyebut sopir. Aku menampar dahiku dalam hati. Bodoh. Bodoh.

"Aduh, tetap saja, jangan disuruh menunggu di sana," omelnya. Kok, mengomel? "Gema! Ada Tika! Cepat kemari!" Loh? Kok Tika? Gema cerita tentangku? "Sebentar, tante antarkan kopi dan gorengan untuk sopir kamu, ya."

"Eh, tante. Tidak usah repot-repot..." Dan tante sudah pergi.