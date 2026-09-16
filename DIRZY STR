# DIRZY STORE ONLINE

## File
- `index.html` = toko publik
- `admin.html` = panel admin
- `config.js` = URL + publishable key Supabase
- `schema.sql` = database + RLS + Storage

## Setup
1. Buat project di Supabase.
2. Buka SQL Editor.
3. Edit email `GANTI_EMAIL_ADMIN@example.com` di `schema.sql`, lalu jalankan SQL.
4. Di Authentication > Users, buat user dengan email admin yang sama.
5. Salin Project URL dan Publishable/anon key dari Supabase.
6. Isi `config.js`.
7. Upload ke hosting statis/GitHub Pages/Netlify/Vercel.
8. Buka `admin.html`, login dengan email/password Supabase.
9. Tambah ID + foto dari HP. Perubahan akan tersimpan online dan terlihat di `index.html`.

PENTING:
- Jangan memasukkan `service_role`/secret key ke `config.js`.
- `publishable/anon key` memang dapat berada di browser, tetapi keamanan tetap bergantung pada RLS.
- Foto produk disimpan di Supabase Storage bucket `product-images`.
