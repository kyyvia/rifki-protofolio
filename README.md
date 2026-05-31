# Portofolio Rifki Ardi Gunansyah

Situs portofolio statis untuk Rifki Ardi Gunansyah. Dibuat agar mudah di-deploy ke Vercel dan dapat dikembangkan dengan integrasi Supabase.

## Struktur

- `index.html` - halaman utama portofolio
- `style.css` - gaya tampilan portofolio

## Cara Jalankan Lokal

1. Buka folder `rifki-portfolio`.
2. Buka `index.html` di browser.

## Deploy ke Vercel

1. Masuk ke https://vercel.com dan buat akun jika belum punya.
2. Buat proyek baru dan pilih `Import from Git Repository`.
3. Pilih repository GitHub yang berisi folder `rifki-portfolio`.
4. Untuk static site, gunakan `Framework Preset: Other` dan set `Output Directory` ke `/`.
5. Deploy.

## Menggunakan Supabase

Jika ingin menambahkan backend Supabase untuk formulir kontak atau data proyek:

1. Buat project di https://app.supabase.com.
2. Tambahkan tabel `contacts` atau `projects` sesuai kebutuhan.
3. Gunakan Supabase client di JavaScript untuk mengirim data dari formulir kontak.

> Catatan: versi saat ini adalah halaman statis. Untuk integrasi Supabase, tambahkan `script.js` dan endpoint Supabase.
