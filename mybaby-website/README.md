# MY BABY — Website

Pusat Perlengkapan Bayi Terlengkap di Kalimantan · Sejak 2007

## Isi folder
```
index.html        ← Website lengkap (HTML + CSS internal + JS). Buka file ini di browser.
images/           ← Semua foto produk & toko (sudah dioptimasi untuk web)
  ├─ pakaian/     ← Pakaian bayi
  ├─ tidur/       ← Perlengkapan tidur
  ├─ makan/       ← Botol & makan
  ├─ kesehatan/   ← Popok, perawatan, pump
  ├─ stroller/    ← Travel & stroller
  ├─ mainan/      ← Mainan edukasi
  └─ toko/        ← Foto cabang (Berau, Bulungan, Malinau)
```

## Cara melihat
Cukup buka `index.html` di browser (double-click). Tidak butuh server atau backend.

## Cara deploy ke Netlify (gratis)
1. Buka https://app.netlify.com/drop
2. Drag-and-drop **seluruh folder** `mybaby-website` ke halaman tersebut.
3. Website langsung online dengan URL gratis. Selesai.

(Alternatif: Vercel atau GitHub Pages — sama-sama bisa, cukup upload folder ini.)

## Catatan
- Semua tombol & link (CTA, kategori, kontak) mengarah ke WhatsApp **+62 821-5841-6509**.
- Peta cabang memakai Google Maps embed berbasis pencarian nama toko. Jika ingin titik
  lokasi yang lebih presisi, ganti URL `src` di tiap `<iframe>` (cari kata `maps.google.com`
  di dalam `index.html`) dengan link "Embed a map" dari Google Maps untuk masing-masing toko.
- Kategori **Travel & Stroller** memakai foto interior toko sebagai sementara, karena belum
  ada foto khusus stroller di aset yang diberikan. Ganti `images/stroller/stroller-1.jpg`
  dengan foto stroller asli kapan saja — nama file-nya sudah otomatis terpakai.
- Link Facebook tiap cabang masih memakai pencarian Facebook. Ganti dengan URL halaman
  Facebook asli bila sudah tersedia (cari `facebook.com/search` di `index.html`).
