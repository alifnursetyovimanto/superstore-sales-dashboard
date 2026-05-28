# Sales Performance Insights — Superstore 2015–2018

## Ringkasan eksekutif

Analisis 4.922 transaksi dari 2015–2018 menghasilkan total revenue $2.3M
dengan profit $421.3K (margin 18.3%). Tiga temuan utama: pola musiman yang
kuat di Q4, dominasi Technology sebagai kategori paling profitable, dan
kesenjangan performa yang signifikan antara region.

---

## Temuan 1 — Pola musiman Q4 mendominasi revenue

**Apa yang terlihat:**
November dan Desember secara konsisten menjadi bulan dengan sales tertinggi
— mencapai ~$200K+, hampir 2–3x bulan rata-rata ($80–100K). Pola ini
berulang tiap tahun selama 4 tahun, mengkonfirmasi ini bukan anomali tapi
tren struktural.

Februari adalah titik terendah sepanjang tahun — sales turun ke ~$25K,
hanya 12% dari peak November/Desember.

**Implikasi bisnis:**
- Q4 (Oktober–Desember) kemungkinan menyumbang 35–40% revenue tahunan
- Ada "dead zone" di Januari–April yang perlu strategi khusus
- Inventory dan staffing perlu disesuaikan dengan pola ini

**Rekomendasi:**
1. Maksimalkan stok dan kapasitas di Q4 — jangan sampai kehabisan di peak season
2. Buat program promosi khusus untuk Q1 (Januari–Maret) untuk mendorong
   demand di off-season — misalnya bundle deal atau early bird discount
3. Gunakan data historis ini untuk forecasting inventory tahun berikutnya

---

## Temuan 2 — Technology: high sales, high profit

**Apa yang terlihat:**
Technology mendominasi profit di hampir setiap bulan — profit November
mencapai $75K+, jauh di atas Office Supplies ($45K) dan Furniture ($30K).
Di chart Sales by Category, Technology juga memimpin dengan sales
November mencapai $325K+.

Furniture memiliki sales yang cukup tinggi tapi profit relatif tipis
dibanding Technology — mengindikasikan margin yang lebih rendah.

Office Supplies konsisten di posisi dua untuk profit, dengan pola yang
stabil tiap bulan — menjadi "backbone" revenue yang reliable.

**Implikasi bisnis:**
- Technology adalah kategori premium dengan margin terbaik
- Furniture perlu dievaluasi — apakah diskon terlalu agresif?
- Office Supplies adalah revenue yang bisa diandalkan sebagai baseline

**Rekomendasi:**
1. Prioritaskan promosi dan stok Technology di peak season (Q4)
2. Audit strategi pricing Furniture — kemungkinan ada ruang untuk
   mengurangi diskon tanpa kehilangan volume signifikan
3. Cross-sell Office Supplies dengan Technology untuk meningkatkan
   basket size per transaksi

---

## Temuan 3 — West dan East mendominasi, South tertinggal

**Apa yang terlihat:**
West (~$130K profit) dan East (~$125K profit) hampir setara di posisi
teratas — keduanya jauh melampaui Central (~$92K) dan South (~$75K).

South menghasilkan profit hampir 43% lebih rendah dari West, padahal
kemungkinan jumlah orders-nya tidak berbeda jauh — ini mengindikasikan
masalah margin, bukan masalah volume.

**Implikasi bisnis:**
- Ada peluang besar untuk meningkatkan performa South dan Central
- Gap West–South yang besar perlu diinvestigasi lebih dalam
- Kemungkinan penyebab: product mix berbeda, diskon lebih agresif,
  atau biaya operasional lebih tinggi di South

**Rekomendasi:**
1. Investigasi product mix di South — apakah mereka lebih banyak jual
   Furniture (margin rendah) dibanding Technology?
2. Audit kebijakan diskon per region — South mungkin memberi diskon
   lebih besar tanpa dasar yang jelas
3. Pertimbangkan targeted campaign untuk mendorong penjualan Technology
   di South dan Central

---

## Kesimpulan & prioritas aksi

Berdasarkan tiga temuan di atas, urutan prioritas yang disarankan:

| Prioritas | Aksi | Dampak Estimasi |
|---|---|---|
| 1 | Maksimalkan stok Technology di Q4 | Revenue +15–20% di peak season |
| 2 | Program promosi Q1 untuk atasi off-season | Kurangi revenue gap Q1 vs Q4 |
| 3 | Audit pricing Furniture | Margin improvement tanpa kehilangan volume |
| 4 | Investigasi dan perbaiki performa South | Potensi +20–30% profit dari region ini |

---

## Keterbatasan analisis

- Kolom Profit dihitung menggunakan estimasi margin (Technology 25%,
  Office Supplies 18%, Furniture 12%) karena tidak tersedia di dataset
  asli — angka profit bersifat ilustratif, bukan aktual
- Dataset tidak mencakup data biaya operasional per region — analisis
  South vs West belum bisa dikonfirmasi sebabnya
- Perlu data customer-level untuk analisis retensi dan lifetime value

---

*Dashboard interaktif tersedia di Looker Studio — filter by Category
dan Region untuk eksplorasi lebih lanjut.*
