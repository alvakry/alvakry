# alvakry.exe — v2.0

> *"good design is quiet. bad governance is loud."*

Personal portfolio website. Handcrafted. No frameworks. No subsidies received.

---

## stack

- Pure HTML + CSS + Vanilla JS — satu file, tidak ada dependencies
- [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) + [Space Mono](https://fonts.google.com/specimen/Space+Mono) via Google Fonts
- Dark / light mode — deteksi sistem otomatis, tersimpan di localStorage
- Bahasa Indonesia / English toggle — tersimpan di localStorage
- Fully responsive — mobile, tablet, desktop

---

## features

```
✦ bilingual          EN ⇄ ID
✦ theme toggle       light ⇄ dark
✦ custom cursor      desktop only, touch-aware
✦ glitch animation   hero headline
✦ marquee strip      slow scroll, government critiques
✦ scroll fade-in     IntersectionObserver
✦ mobile drawer      fullscreen nav overlay
✦ noise texture      subtle analog grain
✦ sticky nav         frosted glass blur
✦ zero dependencies  no frameworks harmed
```

---

## struktur

```
portfolio/
└── index.html   ← semua ada di sini
```

Sengaja satu file. Karena bisa.

---

## cara pakai

Tidak perlu build step, tidak perlu `npm install`, tidak perlu menjelaskan diri ke komite manapun.

```bash
git clone https://github.com/alvakry/your-repo.git
cd your-repo
# buka index.html di browser
```

Atau langsung deploy ke GitHub Pages, Vercel, Netlify — pilih sesuai selera.

---

## kustomisasi

Cari dan ganti placeholder berikut di `index.html`:

| Placeholder | Ganti dengan |
|---|---|
| `alvakry` | nama kamu (sudah benar) |
| `[Kota]` / `[City]` | kota tempat tinggal |
| `hello@yourdomain.com` | email kamu |
| `yourhandle` (×3) | username Instagram, GitHub, YouTube |
| konten project & artikel | karya dan tulisan nyata kamu |

---

## deployment

```bash
# GitHub Pages — push ke branch main, aktifkan Pages dari Settings
# Vercel / Netlify — drag & drop folder, selesai
```

---

## lisensi

MIT — bebas dipakai, dimodifikasi, dijadikan referensi.  
Sama bebasnya seperti janji kampanye, tapi ini sungguhan.

---

<sub>dibuat tangan · tidak disponsori pemerintah · pajak tetap dibayar</sub>
