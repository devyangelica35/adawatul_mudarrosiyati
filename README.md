# adawatul_mudarrosiyati
Game edukasi interaktif berbasis single-file HTML5 untuk pembelajaran kosakata Bahasa Arab (Adawatul Madrasiyyah) dengan efek suara Web Audio API dan Sertifikat Digital Canvas
# 🎒 Tangkap Mufradat: Alat Sekolahku

**Tangkap Mufradat: Alat Sekolahku** adalah game edukasi interaktif berbasis *Single-File HTML5* yang dirancang untuk membantu siswa/anak-anak belajar serta menguji hafalan kosakata Bahasa Arab materi *Adawatul Madrasiyyah* (Peralatan Sekolah) secara menyenangkan, responsif, dan melatih refleks.

---

## 🌟 Fitur Utama

- 🎮 **Mekanik Game Refleks & Pemilahan:** Pemain mencocokkan kartu kata Bahasa Arab (lengkap dengan harakat dan transliterasi Latin) yang jatuh dari atas dengan zona gambar target di bagian bawah.
- 🔊 **Efek Suara Sintetis (Web Audio API):** Menggunakan frekuensi audio sintetis browser (*Ting!* untuk jawaban benar dan *Tetot!* untuk jawaban salah) tanpa memerlukan file audio eksternal (`.mp3`/`.wav`).
- 📜 **Sertifikat Digital Otomatis:** Menggunakan HTML5 `<canvas>` untuk merender Sertifikat Kelulusan secara dinamis berdasarkan Nama Pemain, Skor Akhir, dan Tanggal Bermain. Sertifikat dapat diunduh langsung dalam format `.png`.
- ❤️ **Sistem Nyawa & Timer:** Dilengkapi batas waktu 60 detik dan 3 nyawa (❤️) untuk meningkatkan tantangan permainan.
- 📱 **Desain Ramah Anak & Responsif:** Tampilan cerah, menarik, dan dapat dimainkan baik di perangkat seluler (HP/Tablet) maupun PC/Laptop.
- ⚡ **Zero Dependencies / Single File:** Dibuat menggunakan murni HTML5, CSS3, dan Vanilla JavaScript tanpa library external.

---

## 📚 Materi Kosakata (Adawatul Madrasiyyah)

| No. | Objek Visual | Tulisan Arab | Transliterasi (Latin) | Arti |
| :--: | :--: | :--: | :--: | :--: |
| 1 | 🎒 | حَقِيبَةٌ | Ḥaqībatun | Tas |
| 2 | 📚 | كِتَابٌ | Kitābun | Buku Paket |
| 3 | 📓 | دَفْتَرٌ | Daftarun | Buku Tulis |
| 4 | ✏️ | قَلَمُ الرَّصَاصِ | Qalamur-raṣāṣi | Pensil |
| 5 | 🖋️ | قَلَمٌ | Qalamun | Pulpen / Pena |
| 6 | 📏 | مِسْطَرَةٌ | Misṭaratun | Penggaris |
| 7 | 🧽 | مِمْحَاةٌ | Mimḥātun | Penghapus |
| 8 | 👝 | مِقْلَمَةٌ | Miqlamatun | Tempat Pensil |
| 9 | 🪑 | كُرْسِيٌّ | Kursiyyun | Kursi |
| 10 | 🗄️ | مَكْتَبٌ | Maktabun | Meja Belajar |

---

## 🛠️ Teknologi yang Digunakan

- **HTML5:** Struktur aplikasi & elemen `<canvas>` untuk generator sertifikat.
- **CSS3:** Animasi kartu jatuh, efek visual (flash hijau/merah, screen shake), dan tata letak responsif.
- **JavaScript (ES6+):** Logika permainan, pengacak target, timer, dan manajemen nyawa.
- **Web Audio API:** Pembuatan efek audio sintetis instan.

---

## 🚀 Cara Menjalankan Project

1. **Clone repositori ini:**
   ```bash
   git clone [https://github.com/USERNAME/tangkap-mufradat.git](https://github.com/USERNAME/tangkap-mufradat.git)
