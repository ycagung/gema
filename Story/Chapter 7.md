---
tags:
  - chapter
title: Sumbu
---
# Chapter 7 - Sumbu

---

**Gema**
---
"Kak, ini *race condition*," ujarku pada Johan. Kami berdua sedang mengevaluasi *bug* di salah satu sistem manufaktur. Lalu Johan garuk-garuk kepala. *Dia tidak tahu race condition? Dasar amatir.* Sepertinya suasana hatiku sedang tidak enak. Biasanya aku akan langsung menjelaskan apa itu *race condition* dengan penuh semangat sampai lawan bicaraku mengerti.

"*Race condition* itu adalah ketika dua proses atau lebih yang berbagi data yang sama dieksekusi secara bersamaan, Johan," terang Luna. *Terima kasih kakak cantikku.* Luna mengedipkan matanya padaku dan kubalas dengan kedipan yang sama. Perhatian Johan selanjutnya berpindah ke Luna yang menjelaskan detail demi detail tentang *race condition*.

"Gema, boleh tolong bantu aku untuk animasi ini?" Aku menoleh ke arah Kara yang sedang menunjuk ke arah layarnya. *Kenapa tiba-tiba aku jadi tutor?* Tapi Hans menyelaku ketika aku hendak berpindah ke sebelah Kara.

"Biar aku saja, Gem. Kamu lanjutkan saja bagianmu," ujarnya. Aku mengangguk sopan tanda terima kasih dan kembali ke layar komputerku.

Sudah satu bulan aku berkantor di sini, peta klien Jukebox sudah tergambar jelas di kepalaku. Lebih dari sepuluh klien tetap berbasis Australia dan beberapa klien lokal dalam delapan belas bulan semenjak mereka berdiri. *Pantas saja Pak Andrew banyak tersenyum di sekolah.* Mulai hari ini, aku mendapat bagian untuk memegang satu klien yang bergerak di bagian desain teknik dan manufaktur. Mungkin karena demonstrasiku waktu awal masuk dan kinerjaku selama tiga minggu ini, mereka merasa klien ini paling cocok untukku. Sejujurnya aku cukup kaget karena mereka mempercayakan satu klien utuh untuk kukerjakan sendiri. 

*Tapi tak masalah, aku jadi bebas berkreasi.* Kutenggelamkan lagi pikiranku ke dalam lautan kode di layar. Sesuatu yang sama nyamannya dengan tidur buatku. Setidaknya *mood*-ku akan kembali cerah.

*Wah, banyak sekali potensi race condition di sini? Parameter di banyak endpointnya kurang lengkap dan tidak seragam. Ah, ini ada vulnerability point. Yang bagian ini critical tapi tidak teroptimasi. Yang ini... Yang ini...*

Waktu aku mematikan komputer sebelum pulang, aku sudah meninggalkan dua puluh lima *commit* di *Github* untuk sistem itu.

---

**Luna**
---
*Hari baru, semangat baru!* Aku memasuki ruang kerja dengan gembira. "*Morning, guys*!" sapaku pada Hans dan Otis. Baru mereka yang sudah datang dan menempelkan mata mereka ke layar. *Atau mereka tidak pulang?*

"*Morning,* Luna," jawab mereka bersamaan. Sebagai primadona (*self-appointed*) di kantor ini, aku harus selalu membawa suasana yang cerah dan gembira. Lagipula kita sekarang punya anggota baru, seorang anak SMP yang sangat imut dan lucu, tapi luar biasa pintar. Aku tidak boleh murung dan suram, karena anak kecil itu sensitif. *Dia harusnya masih bermain, tapi sekarang memilih untuk bekerja. Semoga dia tidak dipaksa siapapun.*

---

"Kalian tidak merasa aneh dengan Gema?" tanya Otis padaku dan Hans dengan tiba-tiba. Ini masih pukul sepuluh pagi. *Untung Gema baru akan datang nanti siang*. "Mana mungkin anak seumur dia sudah bisa menghitung matriks tiga dimensi dalam kepalanya coba? Dan secepat itu pula!"

"Kenapa, Otis? Kamu ada *inferiority complex*?" jawab Hans tanpa memalingkan pandangannya dari kode yang sedang dia tulis. "Orang genius itu ada, Otis. Mungkin Gema adalah salah satunya."

"Ejek aku semaumu. Firasatku jarang salah. Gema itu tidak terlihat seperti anak kecil di mataku. Ketika aku mengajaknya bicara, itu terasa seperti aku sedang bicara dengan Pak Andrew," lawan Otis.

"Sudahlah, Otis. Mana mungkin juga Gema itu seumuran dengan Pak Andrew, kan? Mungkin mentalnya memang lebih dewasa," timpaku sambil mengangkat kepalaku. "Tapi memang walaupun dia terlihat lucu dan polos, sepertinya dia menyimpan sesuatu yang lebih dalam dari itu. Seperti sebuah beban. Ketika aku melihatnya, aku merasa seperti ini memeluknya dan mengatakan bahwa semuanya akan baik-baik saja. Mungkin aku yang terlalu sayang pada anak kecil. Tidak sepertimu," ujarku sambil menjulurkan lidah pada Otis.

*Kapan-kapan akan kuajak dia mengobrol. Sambil makan mungkin?*

---

**Hans**
---
Semua orang sudah pergi dari kantor. Hanya aku sendiri di sini masih bergulat dengan sistem pembayaran sebuah klien yang bergerak di bidang retail. *Aku bosan, terlalu banyak akun yang harus diberi perlakukan khusus.* Adalah sebuah kebiasaan di mana ketika aku bosan, aku akan menjelajahi kode-kode dari teman-teman satu timku. *Sepertinya aku akan jalan-jalan ke kliennya Gema.*

Beberapa klik sudah membawaku ke daftar *commit* di sistem yang dikerjakan Gema. *Aku tidak ingat menjelaskan bagaimana cara menaikkan kode ke github padanya, ah, biarlah. Ini Gema. Kemungkinan besar juga dia sudah tahu.* Lalu muncullah di layar itu, dua puluh lima commit message yang dilakukan Gema. *Ini semua tadi siang?! Dalam dua jam dia bekerja?!*

Kubaca satu-satu setiap *commit message*-nya. *Fix: potential race conditions in 37 processes. Fix: vulnerability point, potential SQL injection. Fix: sorting algorithm on STEP files fetching, n^2 became 2n problem. Fix: optimize STEP file parsing on upload. Fix:...*

*Anak ini gila! Jadi dia tidak cuma pintar teori!*

Niat awalku yang adalah membaca sekilas *commit message*-nya berubah tanpa kusadari menjadi eksplorasi kode baris demi baris, *file* demi *file*. Semua kode yang ditulis Gema terdokumentasi dengan baik, tidak ada satupun yang tidak dia jelaskan dalam *comment.* Seakan-akan dia tahu bahwa kode ini akan dibaca oleh orang lain. Dan membaca penjelasan itu seperti membaca sebuah cerita yang ditulis sangat indah dan konsisten. 

*Ini! Ketemu!* Aku berteriak dalam hati ketika menemukan sebuah blok kode Gema yang menyelesaikan masalah yang hampir sama dengan masalah yang kuhadapi di klienku. *Ah, jadi begini cara yang benar. Dasar Gema, dia sudah pulang tapi malah membantuku mengerjakan pekerjaanku.*

Ketika kubereskan laptopku, jam sudah menunjukkan pukul sepuluh malam.

---

**Anya**
---
Kulihat jam dinding. *Pukul delapan.* Malam ini terasa sepi dan dingin, orang tuaku juga sedang pergi. Besok tidak ada PR dan ulangan, jadi aku sekarang bebas memainkan ponselku. *Facebook* sedang *trending* sekali di sekolah. Hampir semua anak punya dan aktif membuat *post* setiap hari. Sebagian lucu, sebagian aneh. Keduanya membuatku tertawa. Tiba-tiba aku teringat sesuatu. Kuketikkan dalam kolom pencarian "Gema Cahaya". *Tidak dapat ditemukan.*

Alisku mengernyit. *Dia tidak punya sosial media? Aku juga tidak ingat pernah melihat dia menggunakan ponsel. Apa dia setertutup itu? Tapi ketika berjalan denganku dia terasa sangat hangat dan menyenangkan. Ah, mungkin dia hanya tidak punya ponsel, tidak semua anak bisa punya ponsel juga.*

Tadi siang aku memintanya menemaniku berjalan ke gerbang sekolah. Seperti biasa dia langsung berdiri di sampingku dan belagak seperti pelayan. *Tak pernah gagal membuatku tertawa.* Hal berikutnya adalah kami sedang berjalan di lorong lantai dua.

"Tumben hari ini langsung pulang?" tanyanya padaku. 

"Aku tidak ada kegiatan hari ini," jawabku.

"Jadi tuan putri bisa pulang dan beristirahat dengan tenang di rumah," ujarnya dengan nada mengejek. Membuatku melayangkan tinjuku ke lengannya. 

"Tuan putri ini akan kesal denganmu," ucapku sambil pura-pura cemberut.

"Tak apa, aku suka melihatmu cemberut," jawabnya sambil tersenyum. *Manis. Senyumnya manis sekali.* Tanpa sadar aku langsung memalingkan wajahku dan menunduk. "Lagipula, kamu tidak pernah sungguhan cemberut."

"Ehem." Aku berdeham, dalam usaha agar tidak tersipu malu. "Kalau begitu aku tidak jadi cemberut agar kamu tidak suka."

"*That's even better,*" jawabnya singkat tanpa melihatku. Garis-garis sinar matahari siang dari celah jendela tangga jatuh mengenai sisi wajahnya. Entah kenapa, Gema terlihat seperti... *Sejak kapan Gema jadi--* "Anya, kamu tidak apa-apa? Wajahmu merah. Kamu sakit?" tanyanya. Dia langsung menghentikan langkahnya meletakkan punggung tangannya di dahiku. Aku hanya bisa terdiam dan menganga. *Terlalu dekat! Terlalu dekat!*

"A-aku tak apa," jawabku sambil mendorong tangannya menjauh. "Mungkin hanya kepanasan." Gema tidak menjawab dan hanya terdiam di depanku.

"Anya," ujarnya. "Jika kamu membutuhkan apapun, jika kamu merasa berat, panggil saja aku, oke?" pintanya. *Dari mana dia bisa menawarkan hal semacam itu?* Tapi entah kenapa aku tidak ingin mendebatnya. Entah kenapa aku... *percaya?*

"Jangan menawarkan janji yang tidak bisa kamu penuhi, Gema. Cukup jadilah temanku," jawabku berusaha netral. *Itu sudah lebih dari cukup.*

Tak terasa kami sudah sampai di gerbang sekolah. Kak Kevin sudah menunggu di sana, aku melambaikan tangan agar dia melihatku lalu berputar menghadap Gema. "Terima kasih sudah menemaniku berjalan," ucapku sambil tersenyum dan melambaikan tangan.

"*Anytime,* hati-hati di jalan, tuan putri. Selamat beristirahat," jawabnya juga dengan senyum yang sama seperti tadi.

---

Kulihat pantulan wajahku sendiri di layar ponsel. *Aku tersenyum? Karena mengingat kejadian tadi siang bersama Gema? Anya! Kendalikan dirimu.* Tiba-tiba ponsel itu berdering. Panggilan dari Kak Kevin.

*"Anya, kamu sedang di rumah?"*

"Iya, kak. Ada apa?"

*"Aku sedang di depan rumahmu,"* jawabnya. *Apa? Sedang apa dia di depan rumahku? Haruskah kusuruh masuk? Tapi ayah dan ibu tidak memperbolehkan aku menerima tamu laki-laki jika sedang sendirian.* *"Boleh aku masuk?"* tanyanya mengejar. *Ah, biarlah, sepertinya dia tidak akan lama.*

"Ya, kak. Tunggu sebentar, aku akan turun." Tak lama kemudian, aku sudah membukakan pintu gerbang rumah. Dan benarlah, Kak Kevin ada di depan rumah. Sendirian. "Silakan masuk, kak. Kita mengobrol di teras, ya?" Dia masuk dan duduk di teras tanpa menjawab. Kubiarkan pintu gerbang terbuka lalu aku duduk di depannya. Menunggunya berbicara.

"Anya, kamu sedang main-main di belakangku dengan Gema?" *Hah?!*