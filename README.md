# TaxoEdu — Paket GitHub Pages

Folder ini adalah varian web siap deploy manual ke GitHub Pages.

## Deploy

1. Jalankan npm install lalu npm run build jika ingin rebuild.
2. Upload isi folder dist/ (index.html dan folder assets/) ke branch yang dipakai GitHub Pages.
3. Di GitHub buka Settings → Pages → Deploy from a branch, lalu pilih branch tersebut.
4. Aplikasi menggunakan base relatif (./) sehingga dapat berjalan pada subpath repository.

Data Input Data/Koreksi disimpan di LocalStorage browser pengunjung. Gambar dan lookup otomatis menggunakan sumber/API online (Wikimedia Commons, iNaturalist, GBIF, Wikipedia).
