# PKBM Lam Alif

Website statis PKBM Lam Alif, siap di-deploy ke Vercel.

## File
- `index.html` — website utama, CSS dan JavaScript sudah menyatu.
- `vercel.json` — konfigurasi deployment Vercel.

## Upload ke Vercel
1. Upload folder `pkbm-lam-alif` ke repository GitHub.
2. Di Vercel pilih **Add New Project**.
3. Import repository tersebut.
4. Untuk project statis ini tidak perlu build command.
5. Klik **Deploy**.

## Sebelum dipublikasikan
Di `index.html`, cari:
`const nomorAdmin="628XXXXXXXXXX";`

Ganti dengan nomor WhatsApp admin PKBM menggunakan format internasional tanpa tanda `+`.

Contoh:
`081234567890` menjadi `6281234567890`.

Alamat, email, berita, dan informasi PKBM pada website juga masih berupa contoh dan dapat diganti dengan data resmi PKBM.
