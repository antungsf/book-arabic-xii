# Bahasa Arab Kelas XII — Materi Audio & Audio-Visual

Prototipe pembelajaran interaktif berbasis web untuk Buku Siswa Bahasa Arab MA Kelas XII, mencakup 3 unit: **Teknologi Informasi dan Komunikasi**, **Tokoh-tokoh Besar Islam**, dan **Studi di Universitas**.

## 🔊 Coba langsung
Buka halaman: `https://<username-anda>.github.io/<nama-repo>/`

Setiap unit memuat subtema:
- **Mufradat** — kosakata baru
- **Hiwar 1 & 2** — dialog percakapan
- **Qira'ah** — teks bacaan

Setiap kata/kalimat Arab punya tombol putar (▶) yang membacakannya menggunakan suara sintesis bawaan peramban (Web Speech API).

## 📄 Naskah audio
Naskah lengkap untuk direkam manual (jika ingin memakai suara manusia asli, bukan sintesis) tersedia di [`docs/Skrip_Audio_Bahasa_Arab_Kelas_12.docx`](docs/Skrip_Audio_Bahasa_Arab_Kelas_12.docx), juga bisa diunduh langsung dari tombol di halaman web.

## ⚙️ Catatan teknis
- Halaman ini murni HTML/CSS/JS statis, tidak memerlukan server atau build tool apa pun.
- Fitur audio memakai [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis) — kualitas suara Arab bergantung pada peramban dan sistem operasi pengguna. Disarankan menggunakan **Google Chrome** dengan koneksi internet aktif.
- Tidak ada data yang dikirim ke server mana pun; semuanya berjalan di sisi klien (browser pengguna).

## 🚀 Cara mengaktifkan GitHub Pages
1. Buka **Settings** → **Pages** pada repo ini.
2. Pilih branch `main` dan folder `/ (root)`.
3. Simpan — situs akan aktif di beberapa menit pada alamat di atas.
