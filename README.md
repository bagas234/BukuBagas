# BukuBagas Modern — Vite JavaScript

Aplikasi frontend modern BukuBagas yang dipindahkan dari PHP ke JavaScript + Vite. Fitur demo: login, dashboard grafik arus kas 7 hari, transaksi (buat/batalkan), produk & stok, laporan ekspor CSV, multi-cabang. Data disimpan di localStorage browser.

## Jalankan di VS Code
1. Install Node.js LTS.
2. Ekstrak folder dan buka `BukuBagas_Vite` di VS Code.
3. Buka Terminal dan jalankan:
   ```bash
   npm install
   npm run dev
   ```
4. Buka URL localhost yang Vite tampilkan.

Login demo: `081234567890` / `admin123`.

## Build dan preview
```bash
npm run build
npm run preview
```

Folder `dist` adalah hasil build untuk hosting static.

## Rilis publik
Deploy folder hasil `dist` ke Netlify, Vercel, Cloudflare Pages, atau GitHub Pages. Panduan singkat: build dengan `npm run build`, lalu upload/publish `dist` atau sambungkan repository. Untuk data multi-user, login yang aman, sinkronisasi antarperangkat, dan MySQL, frontend demo ini perlu backend/API dan database; localStorage hanya tersimpan pada browser/perangkat pengguna. Jangan gunakan demo credentials pada layanan publik.
