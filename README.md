# RangerHQ-Rational-Therapeutics
Bismillah RT A

# 💊 Ranger HQ · Rational Therapeutics
 
Database belajar untuk **Blok Rational Therapeutics** (Semester 7, FK UMS): rangkuman 30 materi kuliah dalam format HTML interaktif, disusun berdasarkan **blueprint soal ujian blok** supaya belajarnya bisa mulai dari materi yang paling banyak keluar.
 
Dibuat untuk belajar sendiri, dibagikan kalau ada teman yang mau ikut pakai.
 
---
 
## ✨ Fitur
 
- **Prioritas berdasarkan blueprint**: materi dikelompokkan menurut jumlah soal per materi (5, 4, 3, dan 2 soal, total 100 soal). Materi pengantar yang tidak punya soal ada di grup tersendiri.
- **Peta belajar**: 5 kelompok tema (Dasar Farmakologi, Resep & Sediaan, Antibiotik & Antiinfeksi, Obat per Sistem Organ, Etika & Penggunaan Obat Rasional). Klik sub-materi untuk loncat ke kuliahnya.
- **Filter dan pencarian**: cari judul atau dosen, filter per prioritas, dan filter per dosen (15 dosen pengampu).
- **Tutorial, praktikum, dan responsi** per pekan.
- **Mode terang/gelap** dengan tombol di pojok kanan atas. Pilihan tersimpan di browser.
- **Slot latihan soal** (bank soal campuran dan per topik) yang diisi bertahap.
---
 
## 📁 Struktur
 
```
rational-therapeutics/
├── rt-index.html                 # Halaman utama (buka file ini)
├── K.2 Rasionalisasi AB AINS KS - dr. Devi.html
├── K.4 Personal Drug ... - Prof EM.html
├── K.x ...                       # Rangkuman kuliah, satu file per materi
├── README.md
├── LICENSE
└── .gitignore
```
 
Semua file rangkuman harus **satu folder** dengan `rt-index.html`. Kartu kuliah tertaut lewat nama file, jadi nama file tidak boleh diubah tanpa mengubah link di halaman utama. Penamaan file: `K.<nomor> <judul> - <dosen>.html`.
 
---
 
## 🚀 Cara Pakai
 
Tidak perlu install apa pun:
 
1. Clone atau download repositori ini.
2. Buka `rt-index.html` di browser.
3. Pilih materi dari peta belajar atau daftar kuliah.
Kalau dipasang lewat **GitHub Pages**, ganti nama `rt-index.html` menjadi `index.html` supaya terbuka otomatis di alamat utamanya.
 
---
 
## 🎨 Kustomisasi Warna
 
Semua warna ada di bagian `:root` (mode terang) dan `html[data-theme="dark"]` (mode gelap) di dalam `rt-index.html`. Cukup ganti kode hex-nya, semua elemen ikut berubah.
 
---
 
## 🧱 Teknologi
 
HTML, CSS, dan JavaScript biasa. Tidak ada framework dan tidak ada proses build. Koneksi internet hanya dipakai untuk memuat Google Fonts.
 
---
 
## 📄 Lisensi dan Catatan
 
Lisensi **CC BY-NC 4.0**, lihat [LICENSE](./LICENSE). Boleh dipakai dan disebarkan untuk belajar, tidak untuk keperluan komersial.
 
> ⚠️ Rangkuman ini dibuat untuk belajar pribadi berdasarkan materi kuliah FK UMS. Ini bukan sumber medis resmi. Selalu cek dosis dan tata laksana ke buku rujukan dan arahan dosen.
 
---
 
> *"Selamat berjuang! Sukses! ✊🏻🤟🏻👍🏻👏🏻"*
 
