# Petualangan Pikachu — Game Edukasi 3D v2

## Fitur
- Three.js 3D scene dengan hutan, jalan, fog, pencahayaan, pepohonan, dan sprite hero/musuh sebagai billboard 3D.
- Pikachu bergerak maju otomatis, bergerak kanan-kiri dengan swipe, lompat, dan menembak listrik.
- Musuh bergerak maju dan menembakkan proyektil ke Pikachu.
- 3 nyawa; terkena serangan mengurangi nyawa. Nyawa habis = kalah.
- 2 musuh (mudah), 3 musuh (sedang), 4 musuh (sulit) sebagai target aktif.
- **SETIAP kali pemain menekan TEMBAK atau mengetuk arena untuk menembak, 1 soal langsung muncul.** Setelah soal dijawab, barulah listrik ditembakkan ke sasaran. Jawaban benar memberi +100 skor dan damage penuh; jawaban salah tetap menembak dengan damage lebih kecil.
- 10 soal / 10 kesempatan menembak setiap misi.
- Kelas 1–6, 10 mapel: PAI, Matematika, Bahasa Indonesia, Pendidikan Pancasila, IPAS, Bahasa Jawa, Bahasa Inggris, PJOK, Koding, Seni Rupa.
- Solo, Duo, Squad (versi saat ini merupakan mode kerja sama bergiliran pada satu perangkat).
- Pause, kembali ke menu, reward bintang, skor.
- Audio dibuat dengan Web Audio API sebagai efek orisinal bertema petualangan/elektrik; tidak menggunakan rekaman audio resmi Pokémon.

## Menjalankan
Ekstrak ZIP, lalu dari folder proyek jalankan:
`python -m http.server 8000`
Kemudian buka:
`http://localhost:8000`

Three.js dan font dimuat dari CDN sehingga koneksi internet diperlukan.

## Kontrol
HP/tablet/papan interaktif:
- Swipe kiri/kanan pada arena = menghindar.
- TEMBAK = listrik.
- LOMPAT = melompat.
- Ketuk arena = memulai satu soal tembakan; setelah menjawab, Pikachu menembak.

Laptop:
- A/D atau panah kiri/kanan = gerak.
- W/↑ = lompat.
- Spasi = tembak.
- Esc = pause.

## Catatan kurikulum
Bank soal yang disertakan adalah konten starter/prototipe. Untuk penggunaan sekolah/asesmen, guru perlu meninjau dan memperkaya soal per kelas sesuai CP/ATP/modul ajar dan konteks satuan pendidikan. Desain permainan diarahkan pada aktivitas yang berkesadaran, bermakna, dan menggembirakan.
