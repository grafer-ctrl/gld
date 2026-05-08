# 📊 Gold Signal Dashboard — XAU/USD

> Dashboard sinyal trading emas real-time dengan 8 indikator teknikal gabungan.

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?logo=github)
![License](https://img.shields.io/badge/License-MIT-blue)
![Data](https://img.shields.io/badge/Data-Yahoo%20Finance-blueviolet)

---

## ✨ Fitur

| Indikator | Keterangan |
|-----------|------------|
| **RSI (14)** | Deteksi zona oversold / overbought |
| **MACD (12,26,9)** | Sinyal crossover bullish / bearish |
| **Bollinger Bands** | Posisi harga relatif terhadap volatilitas |
| **Stochastic (14)** | Momentum harga jangka pendek |
| **MA20 vs MA50** | Golden cross / death cross |
| **EMA9 vs EMA21** | Tren jangka pendek |
| **Rate of Change (10)** | Kekuatan momentum 10 hari |
| **ATR Volatilitas** | Kisaran rata-rata harian |

- Sinyal gabungan **BELI / JUAL / TUNGGU** otomatis
- Grafik 60 hari dengan MA20, MA50, titik sinyal
- Level resistansi & dukungan otomatis
- Data real-time dari Yahoo Finance (fallback simulasi)
- Satu file HTML — tidak butuh server / build tool

---

## 🚀 Deploy ke GitHub Pages (5 menit)

### Langkah 1 — Buat repository baru

```
Repository name: gold-signal  (atau nama apa saja)
Visibility: Public
☑ Add a README file
```

### Langkah 2 — Upload file

1. Klik **Add file → Upload files**
2. Upload `index.html` dari repo ini
3. Klik **Commit changes**

### Langkah 3 — Aktifkan GitHub Pages

1. Buka **Settings** → **Pages** (sidebar kiri)
2. Source: **Deploy from a branch**
3. Branch: `main` → folder: `/ (root)`
4. Klik **Save**

### Langkah 4 — Akses dashboard

Tunggu ~1 menit, lalu buka:

```
https://<username>.github.io/<repository-name>/
```

---

## 📁 Struktur File

```
gold-signal/
└── index.html    ← Semua kode dalam satu file
└── README.md     ← Dokumentasi ini
```

---

## ⚠️ Disclaimer

Tool ini hanya untuk **tujuan edukasi dan analisis teknikal**.
Bukan merupakan saran investasi. Selalu lakukan riset mandiri
dan konsultasikan dengan profesional keuangan sebelum berinvestasi.

---

## 📄 Lisensi

MIT License — bebas digunakan dan dimodifikasi.
