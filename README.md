# Reymix

Aplikasi web sederhana untuk menggabungkan beberapa suara (misalnya hujan di atap seng, air dari tepi atap, dan hujan jauh) menjadi satu mix yang enak didengar. Cocok untuk konten ASMR, suara tidur, dan live yang lama.

Semua proses jalan di browser. File suara tidak dikirim ke mana pun.

## Fitur

- Tiga layer suara dengan volume dan posisi kiri-kanan sendiri-sendiri
- Contoh awal: hujan atap seng, hujan di jendela, hujan di hutan, dan bebas
- Efek jauh untuk suara latar
- Rapikan suara: buang dengung rendah, haluskan desis tajam, ratakan suara
- Haluskan bagian yang tiba-tiba keras, tiap suara sendiri-sendiri
- Sambungan mulus (crossfade) supaya suara yang diulang tidak terasa
- Pratinjau langsung, dengan pengukur level
- Atur volume otomatis (sekitar -22 LUFS)
- Cek untuk live: kekerasan, lonjakan, puncak suara, dan keseimbangan antar layer
- Simpan hasil sebagai WAV stereo 16-bit

## Cara pakai

1. Buka `index.html` di browser (Chrome atau Safari), atau lewat alamat GitHub Pages.
2. Pilih contoh, lalu pilih file suara di tiap kartu (WAV, MP3, atau M4A).
3. Tekan **Putar pratinjau** dan setel slider sambil mendengar.
4. Tekan **Cek untuk live** untuk melihat saran.
5. Tekan **Simpan hasil**.

## Pasang di GitHub Pages

1. Upload semua isi folder ini ke repository baru.
2. Buka **Settings**, lalu **Pages**.
3. Di bagian **Build and deployment**, pilih **Deploy from a branch**, pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Tunggu beberapa menit, alamat aplikasimu akan muncul di halaman yang sama.

## Catatan

- Hasil dibatasi 10 menit per file karena keterbatasan memori HP.
- Angka batas di Cek untuk live adalah patokan umum, bukan aturan mutlak.
- Fitur looping untuk durasi panjang belum ada dan direncanakan terpisah.
