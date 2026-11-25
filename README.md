# Ryans Work — Website Statis (GitHub Pages)

Website buatan sendiri untuk proyek-proyek Ryan. HTML + CSS polos, tanpa framework.
Dibangun sendiri — bukan comot tema orang lain.

## Isi folder ini

- `index.html` — Beranda: Hero, Katalog Proyek, Tentang
- `football-legacy-pack.html` — Halaman proyek Football Legacy Pack
  (stat, yang diubah, Versi tersedia, galeri screenshot, cara import, Credit)
- `style.css` — Satu stylesheet bersama (dark, hijau lapangan #0F9D58, bokeh)
- `images/` — 4 screenshot di dalam game:
  - `klub-spanyol.jpg` — klub Spanyol di editor
  - `timnas-indonesia.jpg` — Timnas Indonesia
  - `legenda-messi-ronaldo.jpg` — Legenda, Messi & Ronaldo di atas
  - `liga-indonesia.jpg` — klub divisi 3 Indonesia

## Cara upload ke GitHub Pages

1. **Daftar akun GitHub** (gratis) di https://github.com/signup
   - Daftar pakai email `fuckinryan@gmail.com`.
   - Saat daftar, kamu diminta memilih **username GitHub** — itu nama akunmu
     di GitHub, dan akan jadi bagian dari alamat situsmu.
     ("fuckinryan" itu cuma nama Gmail yang asal, BUKAN username GitHub —
     username GitHub dipilih sendiri saat daftar.)
2. **Bikin repository baru** dengan nama persis: `ryanswork`
   - Klik `+` (kanan atas) → New repository → Repository name: `ryanswork`
   - Pilih **Public**, lalu Create repository.
3. **Upload semua file di folder ini** ke repository itu:
   - Di halaman repo, klik **Add file → Upload files**, lalu pilih
     `index.html`, `football-legacy-pack.html`, `style.css`,
     dan folder `images/` beserta isinya (atau upload pakai aplikasi GitHub di HP).
   - Commit / simpan.
4. **Nyalakan GitHub Pages:**
   - Di repo, buka **Settings → Pages**.
   - Source: **Deploy from a branch**, Branch: **main**, folder: **/ (root)** → Save.
5. **Tunggu 1–2 menit**, lalu buka situsmu di:

   ```
   https://<username-github-kamu>.github.io/ryanswork/
   ```

   Ganti `<username-github-kamu>` dengan username GitHub yang kamu pilih
   saat daftar (bukan alamat email).

## Cara menambah versi baru (Football Legacy Pack)

1. Buka `football-legacy-pack.html`.
2. Di bagian **"Versi tersedia"**, tambahkan satu kartu versi baru di atas
   kartu v1.0 (copy kartu v1.0, ubah nomor versi, tanggal, isi perubahannya,
   dan link Download-nya).
3. Pindahkan pill **"Versi terbaru"** dari kartu lama ke kartu baru.
4. Upload file yang sudah diedit ke GitHub (timpa file lama).
5. Perbarui juga pill versi di kartu Football Legacy Pack di `index.html`
   kalau versi terbarunya berubah.

## Cara menambah proyek baru

1. Buat file HTML baru, misal `nama-proyek.html` (copy
   `football-legacy-pack.html` sebagai contoh, lalu ganti isinya).
2. Di `index.html`, bagian **Katalog Proyek**, tambahkan satu kartu baru
   (copy kartu Football Legacy Pack, ganti judul, deskripsi, pill versi,
   dan link "Lihat" ke file barumu).
3. Upload file baru + `index.html` yang sudah diedit ke GitHub.

## Catatan

- Tombol Download mengarah ke Google Drive (file pack ZIP 35 MB) —
  file pack-nya TIDAK diupload ke GitHub, tetap di Drive.
- Credit: pack asli BUKAN milik Ryan — pack_mundo_completo-v58
  "Catalogo completo" dari komunitas Football Legacy di Discord.
  Ryan hanya me-re-edit dan membagikannya. Discord:
  https://discord.gg/hU3ZgnTMV
- Blog lama (Blogger) tetap ada: https://ryans-work.blogspot.com/
