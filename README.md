# Alat PDF

Situs alat PDF statis. Semua proses berjalan di browser pengguna (memakai [pdf-lib](https://pdf-lib.js.org/)), jadi tidak perlu server dan file tidak diunggah ke mana pun.

## Fitur

- Gabung PDF (atur urutan)
- Ambil halaman tertentu
- Hapus halaman
- Putar PDF (semua atau halaman tertentu)
- Nomor halaman
- Gambar (JPG/PNG) ke PDF
- Tanda air teks
- Susun ulang atau gandakan halaman (termasuk balik urutan)
- Pisah jadi beberapa PDF
- Sisipkan halaman kosong
- Pangkas tepi
- Ubah info dokumen (judul, penulis, subjek, kata kunci)
- PDF ke gambar (PNG/JPG)
- PDF ke teks (.txt)
- Kecilkan ukuran PDF (halaman dirender jadi gambar, teks tidak bisa dipilih lagi)

## Cara memasang di GitHub Pages

1. Buat repositori baru di GitHub, misalnya `alat-pdf`.
2. Unggah `index.html` dan `README.md` ke repositori itu.
3. Buka **Settings → Pages**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu 1–2 menit. Situs tersedia di `https://USERNAME.github.io/alat-pdf/`.

## Mencoba di komputer

Buka `index.html` langsung di browser. Perlu internet karena pdf-lib dimuat dari CDN (jsDelivr). Alat PDF ke gambar, PDF ke teks, dan Kecilkan ukuran juga memuat pdf.js dari cdnjs saat dipakai.

## Catatan

- PDF yang dilindungi password tidak bisa diproses.
- PDF ke Word, OCR, dan proteksi/buka kunci password tidak ada di versi ini karena butuh server atau pustaka yang jauh lebih berat.
- Alat yang merender halaman dibatasi 100 halaman sekali proses agar browser tidak macet.
