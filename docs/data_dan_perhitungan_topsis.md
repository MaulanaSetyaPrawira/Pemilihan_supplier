# Data Sampel & Perhitungan Manual Metode TOPSIS (Per Jenis Ikan)

- **Objek Penelitian:** Rumah Cue Pasar Kebayoran Lama, Jakarta Selatan
- **Periode Penilaian Sampel:** November 2026
- **Total Master Supplier:** 25 Gudang Ikan Beku di Muara Baru (masing-masing memiliki ketersediaan jenis ikan yang berbeda)
- **8 Jenis Ikan Bahan Baku:** Cakalang, Maesang, Layang, Bandeng, Salem, Kembung Banjar, Deho, Cucut
- **Sampel Perhitungan Manual:** **Ikan Salem** (tersedia pada **17 supplier** dari 25 gudang terdaftar)

## 1. Bobot Kriteria (Skala Likert 1–5 & Normalisasi)

| Kode | Nama Kriteria | Tipe | Skor Pemilik ($s_j$) | Bobot Normalisasi ($w_j = s_j / \sum s_k$) |
| :---: | :--- | :---: | :---: | :---: |
| C1 | Kualitas dan kesegaran ikan | Benefit | 5 | 0.25 |
| C2 | Harga ikan per kilogram | Cost | 4 | 0.20 |
| C3 | Ketepatan waktu pengiriman | Benefit | 4 | 0.20 |
| C4 | Ketersediaan stok ikan | Benefit | 4 | 0.20 |
| C5 | Responsivitas dan kemudahan komunikasi | Benefit | 3 | 0.15 |
| **Total** | | | **20** | **1.00** |

## 2. Daftar Sub-Kriteria (Skala Penilaian 1–5)

### C1 — Kualitas dan kesegaran ikan (Benefit)
| Nilai | Keterangan |
| :---: | :--- |
| 5 | Sangat Baik (Ikan beku sempurna, daging kenyal saat thawing, mata cerah, insang merah, bebas bau) |
| 4 | Baik (Ikan beku baik, tekstur cukup kenyal, kondisi fisik segar, bau normal) |
| 3 | Cukup (Ikan cukup segar, sedikit pelunakan tekstur saat thawing namun masih layak olah) |
| 2 | Kurang (Kesegaran menurun, daging mulai lembek saat thawing, berisiko hancur saat direbus) |
| 1 | Sangat Kurang (Ikan tidak segar, daging lembek/rusak, bau menyengat) |

### C2 — Harga ikan per kilogram (Cost)
| Nilai | Keterangan |
| :---: | :--- |
| 1 | Sangat Murah (>10% di bawah rata-rata harga pasar Muara Baru untuk jenis ikan terkait) |
| 2 | Murah (5% - 10% di bawah rata-rata harga pasar Muara Baru untuk jenis ikan terkait) |
| 3 | Normal (Sesuai / setara rata-rata harga pasar Muara Baru untuk jenis ikan terkait) |
| 4 | Mahal (5% - 10% di atas rata-rata harga pasar Muara Baru untuk jenis ikan terkait) |
| 5 | Sangat Mahal (>10% di atas rata-rata harga pasar Muara Baru untuk jenis ikan terkait) |

### C3 — Ketepatan waktu pengiriman (Benefit)
| Nilai | Keterangan |
| :---: | :--- |
| 5 | Sangat Tepat Waktu (Selalu tiba sesuai jadwal atau lebih awal, 0 keterlambatan) |
| 4 | Tepat Waktu (Umumnya tepat waktu, toleransi keterlambatan sangat jarang <30 menit) |
| 3 | Cukup Tepat (Sesekali terlambat 30-60 menit namun masih dalam hari yang sama) |
| 2 | Kurang Tepat (Sering terlambat >1 jam sehingga mengganggu jadwal produksi) |
| 1 | Tidak Tepat Waktu (Sangat sering terlambat atau mundur ke hari berikutnya) |

### C4 — Ketersediaan stok ikan (Benefit)
| Nilai | Keterangan |
| :---: | :--- |
| 5 | Sangat Lengkap (Stok jenis ikan terkait selalu tersedia dan mampu penuhi kebutuhan harian) |
| 4 | Lengkap (Stok umumnya tersedia dengan volume memadai) |
| 3 | Cukup Tersedia (Stok tersedia namun sesekali terbatas) |
| 2 | Kurang Tersedia (Stok terbatas, sering kekurangan volume) |
| 1 | Sangat Terbatas (Stok tidak menentu dan sering kosong) |

### C5 — Responsivitas dan kemudahan komunikasi (Benefit)
| Nilai | Keterangan |
| :---: | :--- |
| 5 | Sangat Responsif (Respon cepat <15 menit, komunikatif, mudah dihubungi kapan saja) |
| 4 | Responsif (Respon baik 15-30 menit, kooperatif dalam koordinasi pengiriman) |
| 3 | Cukup Responsif (Respon standar 30-60 menit, komunikasi cukup jelas) |
| 2 | Kurang Responsif (Respon lambat >1 jam, sering perlu dihubungi berulang kali) |
| 1 | Tidak Responsif (Sulit dihubungi dan tidak kooperatif) |

## 3. Master Data 25 Supplier & Ketersediaan Jenis Ikan

| Kode | Nama Supplier | Alamat | No. Telepon | Jenis Ikan Tersedia |
| :---: | :--- | :--- | :--- | :--- |
| S01 | UD Mina Muara Jaya | Jl. Muara Baru Ujung Blok A No. 12, Jakarta Utara | 0812-8801-1101 | Cakalang, Layang, Salem, Kembung Banjar, Deho |
| S02 | PT Samudra Beku Nusantara | Jl. Muara Baru Raya Blok B No. 04, Jakarta Utara | 0813-8801-1102 | Cakalang, Maesang, Layang, Bandeng, Salem, Kembung Banjar, Deho, Cucut |
| S03 | CV Bahari Segar Abadi | Jl. Muara Baru Ujung Blok C No. 18, Jakarta Utara | 0812-8801-1103 | Layang, Salem, Kembung Banjar, Cucut |
| S04 | UD Bintang Laut Mandiri | Jl. Tuna Raya Muara Baru No. 07, Jakarta Utara | 0857-8801-1104 | Cakalang, Maesang, Deho, Cucut |
| S05 | PT Nelayan Makmur Sentosa | Jl. Cakalang Muara Baru Blok D No. 09, Jakarta Utara | 0811-8801-1105 | Cakalang, Layang, Bandeng, Salem, Kembung Banjar |
| S06 | UD Cahaya Ikan Sejahtera | Jl. Muara Baru Ujung Blok E No. 21, Jakarta Utara | 0812-8801-1106 | Bandeng, Salem, Kembung Banjar |
| S07 | CV Pelabuhan Baru Coldstorage | Jl. Dermaga Barat Muara Baru No. 15, Jakarta Utara | 0813-8801-1107 | Cakalang, Maesang, Layang, Salem, Deho |
| S08 | UD Sinar Bahari Utama | Jl. Muara Baru Raya Blok F No. 02, Jakarta Utara | 0815-8801-1108 | Bandeng, Kembung Banjar, Cucut |
| S09 | PT Maritim Indo Beku | Jl. Tongkol Muara Baru Blok G No. 11, Jakarta Utara | 0812-8801-1109 | Cakalang, Layang, Salem, Deho, Cucut |
| S10 | UD Karya Samudra Jaya | Jl. Muara Baru Ujung Blok H No. 06, Jakarta Utara | 0856-8801-1110 | Maesang, Bandeng, Salem, Kembung Banjar |
| S11 | CV Sumber Rezeki Laut | Jl. Muara Baru Raya Blok A No. 25, Jakarta Utara | 0812-8801-1111 | Cakalang, Layang, Salem, Kembung Banjar, Deho |
| S12 | UD Mutiara Pesisir | Jl. Cakalang Muara Baru Blok B No. 14, Jakarta Utara | 0813-8801-1112 | Cakalang, Maesang, Deho |
| S13 | PT Nusantara Fish Supply | Jl. Dermaga Timur Muara Baru No. 03, Jakarta Utara | 0811-8801-1113 | Cakalang, Layang, Bandeng, Salem, Kembung Banjar, Cucut |
| S14 | UD Berkah Nelayan Baru | Jl. Muara Baru Ujung Blok J No. 19, Jakarta Utara | 0812-8801-1114 | Layang, Salem, Kembung Banjar |
| S15 | CV Agung Lautan Beku | Jl. Tuna Raya Muara Baru No. 22, Jakarta Utara | 0857-8801-1115 | Cakalang, Maesang, Cucut |
| S16 | UD Putra Muara Sejati | Jl. Muara Baru Raya Blok K No. 08, Jakarta Utara | 0813-8801-1116 | Layang, Bandeng, Salem, Deho |
| S17 | PT Prima Coldchain Jakarta | Jl. Tongkol Muara Baru Blok C No. 30, Jakarta Utara | 0812-8801-1117 | Cakalang, Maesang, Layang, Bandeng, Salem, Kembung Banjar, Deho, Cucut |
| S18 | UD Harapan Laut Nusantara | Jl. Muara Baru Ujung Blok L No. 05, Jakarta Utara | 0815-8801-1118 | Bandeng, Kembung Banjar, Deho |
| S19 | CV Mitra Pindang Sejahtera | Jl. Dermaga Barat Muara Baru No. 19, Jakarta Utara | 0812-8801-1119 | Layang, Bandeng, Salem, Kembung Banjar, Deho |
| S20 | UD Sentosa Fishindo | Jl. Muara Baru Raya Blok M No. 17, Jakarta Utara | 0856-8801-1120 | Cakalang, Maesang, Cucut |
| S21 | PT Pasifik Beku Mandiri | Jl. Cakalang Muara Baru Blok E No. 27, Jakarta Utara | 0811-8801-1121 | Cakalang, Layang, Salem, Kembung Banjar |
| S22 | UD Rizki Bahari Jaya | Jl. Muara Baru Ujung Blok N No. 10, Jakarta Utara | 0812-8801-1122 | Bandeng, Salem, Deho, Cucut |
| S23 | CV Lautan Mas Abadi | Jl. Tuna Raya Muara Baru No. 13, Jakarta Utara | 0813-8801-1123 | Cakalang, Maesang, Layang, Deho |
| S24 | UD Aneka Ikan Muara | Jl. Muara Baru Raya Blok P No. 01, Jakarta Utara | 0857-8801-1124 | Layang, Salem, Kembung Banjar |
| S25 | PT Delta Samudra Utama | Jl. Dermaga Timur Muara Baru No. 28, Jakarta Utara | 0812-8801-1125 | Cakalang, Bandeng, Kembung Banjar, Cucut |

## 4. Matriks Keputusan ($X$) — Sampel Penilaian Ikan Salem (17 Supplier)

| Kode | Nama Supplier | C1 | C2 | C3 | C4 | C5 |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: |
| S01 | UD Mina Muara Jaya | 5 | 2 | 5 | 4 | 4 |
| S02 | PT Samudra Beku Nusantara | 5 | 3 | 4 | 5 | 4 |
| S03 | CV Bahari Segar Abadi | 4 | 2 | 4 | 4 | 5 |
| S05 | PT Nelayan Makmur Sentosa | 5 | 4 | 5 | 5 | 5 |
| S06 | UD Cahaya Ikan Sejahtera | 3 | 1 | 4 | 4 | 3 |
| S07 | CV Pelabuhan Baru Coldstorage | 4 | 3 | 5 | 4 | 4 |
| S09 | PT Maritim Indo Beku | 5 | 3 | 5 | 4 | 3 |
| S10 | UD Karya Samudra Jaya | 2 | 1 | 3 | 4 | 2 |
| S11 | CV Sumber Rezeki Laut | 4 | 2 | 5 | 5 | 4 |
| S13 | PT Nusantara Fish Supply | 5 | 4 | 4 | 5 | 4 |
| S14 | UD Berkah Nelayan Baru | 4 | 2 | 3 | 4 | 3 |
| S16 | UD Putra Muara Sejati | 4 | 3 | 4 | 3 | 5 |
| S17 | PT Prima Coldchain Jakarta | 5 | 5 | 5 | 5 | 4 |
| S19 | CV Mitra Pindang Sejahtera | 4 | 1 | 4 | 5 | 4 |
| S21 | PT Pasifik Beku Mandiri | 5 | 2 | 4 | 4 | 5 |
| S22 | UD Rizki Bahari Jaya | 3 | 3 | 3 | 5 | 3 |
| S24 | UD Aneka Ikan Muara | 2 | 3 | 2 | 2 | 3 |

## 5. Pembagi Normalisasi ($\sqrt{\sum x_{ij}^2}$)

| Kriteria | $\sum x_{ij}^2$ | Pembagi ($\sqrt{\sum x_{ij}^2}$) |
| :---: | :---: | :---: |
| C1 | 297 | 17.2337 |
| C2 | 134 | 11.5758 |
| C3 | 293 | 17.1172 |
| C4 | 316 | 17.7764 |
| C5 | 261 | 16.1555 |

## 6. Matriks Keputusan Ternormalisasi ($R$)

| Kode | $r_{i1}$ (C1) | $r_{i2}$ (C2) | $r_{i3}$ (C3) | $r_{i4}$ (C4) | $r_{i5}$ (C5) |
| :---: | :---: | :---: | :---: | :---: | :---: |
| S01 | 0.2901 | 0.1728 | 0.2921 | 0.2250 | 0.2476 |
| S02 | 0.2901 | 0.2592 | 0.2337 | 0.2813 | 0.2476 |
| S03 | 0.2321 | 0.1728 | 0.2337 | 0.2250 | 0.3095 |
| S05 | 0.2901 | 0.3455 | 0.2921 | 0.2813 | 0.3095 |
| S06 | 0.1741 | 0.0864 | 0.2337 | 0.2250 | 0.1857 |
| S07 | 0.2321 | 0.2592 | 0.2921 | 0.2250 | 0.2476 |
| S09 | 0.2901 | 0.2592 | 0.2921 | 0.2250 | 0.1857 |
| S10 | 0.1161 | 0.0864 | 0.1753 | 0.2250 | 0.1238 |
| S11 | 0.2321 | 0.1728 | 0.2921 | 0.2813 | 0.2476 |
| S13 | 0.2901 | 0.3455 | 0.2337 | 0.2813 | 0.2476 |
| S14 | 0.2321 | 0.1728 | 0.1753 | 0.2250 | 0.1857 |
| S16 | 0.2321 | 0.2592 | 0.2337 | 0.1688 | 0.3095 |
| S17 | 0.2901 | 0.4319 | 0.2921 | 0.2813 | 0.2476 |
| S19 | 0.2321 | 0.0864 | 0.2337 | 0.2813 | 0.2476 |
| S21 | 0.2901 | 0.1728 | 0.2337 | 0.2250 | 0.3095 |
| S22 | 0.1741 | 0.2592 | 0.1753 | 0.2813 | 0.1857 |
| S24 | 0.1161 | 0.2592 | 0.1168 | 0.1125 | 0.1857 |

## 7. Matriks Keputusan Ternormalisasi Terbobot ($Y = w_j \cdot r_{ij}$)

| Kode | $y_{i1}$ (C1) | $y_{i2}$ (C2) | $y_{i3}$ (C3) | $y_{i4}$ (C4) | $y_{i5}$ (C5) |
| :---: | :---: | :---: | :---: | :---: | :---: |
| S01 | 0.0725 | 0.0346 | 0.0584 | 0.0450 | 0.0371 |
| S02 | 0.0725 | 0.0518 | 0.0467 | 0.0563 | 0.0371 |
| S03 | 0.0580 | 0.0346 | 0.0467 | 0.0450 | 0.0464 |
| S05 | 0.0725 | 0.0691 | 0.0584 | 0.0563 | 0.0464 |
| S06 | 0.0435 | 0.0173 | 0.0467 | 0.0450 | 0.0279 |
| S07 | 0.0580 | 0.0518 | 0.0584 | 0.0450 | 0.0371 |
| S09 | 0.0725 | 0.0518 | 0.0584 | 0.0450 | 0.0279 |
| S10 | 0.0290 | 0.0173 | 0.0351 | 0.0450 | 0.0186 |
| S11 | 0.0580 | 0.0346 | 0.0584 | 0.0563 | 0.0371 |
| S13 | 0.0725 | 0.0691 | 0.0467 | 0.0563 | 0.0371 |
| S14 | 0.0580 | 0.0346 | 0.0351 | 0.0450 | 0.0279 |
| S16 | 0.0580 | 0.0518 | 0.0467 | 0.0338 | 0.0464 |
| S17 | 0.0725 | 0.0864 | 0.0584 | 0.0563 | 0.0371 |
| S19 | 0.0580 | 0.0173 | 0.0467 | 0.0563 | 0.0371 |
| S21 | 0.0725 | 0.0346 | 0.0467 | 0.0450 | 0.0464 |
| S22 | 0.0435 | 0.0518 | 0.0351 | 0.0563 | 0.0279 |
| S24 | 0.0290 | 0.0518 | 0.0234 | 0.0225 | 0.0279 |

## 8. Solusi Ideal Positif ($A^+$) dan Solusi Ideal Negatif ($A^-$)

| Solusi Ideal | C1 (Benefit) | C2 (Cost) | C3 (Benefit) | C4 (Benefit) | C5 (Benefit) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **$A^+$ (Terbaik)** | 0.0725 | 0.0173 | 0.0584 | 0.0563 | 0.0464 |
| **$A^-$ (Terburuk)** | 0.0290 | 0.0864 | 0.0234 | 0.0225 | 0.0186 |

## 9. Jarak Solusi Ideal ($D_i^+$, $D_i^-$), Nilai Preferensi ($V_i$), dan Peringkat (Ikan Salem)

| Peringkat | Kode | Nama Supplier | $D_i^+$ | $D_i^-$ | Nilai Preferensi ($V_i$) |
| :---: | :---: | :--- | :---: | :---: | :---: |
| 1 | S19 | CV Mitra Pindang Sejahtera | 0.0208 | 0.0875 | **0.8078** |
| 2 | S01 | UD Mina Muara Jaya | 0.0226 | 0.0816 | **0.7830** |
| 3 | S21 | PT Pasifik Beku Mandiri | 0.0237 | 0.0801 | **0.7716** |
| 4 | S11 | CV Sumber Rezeki Laut | 0.0244 | 0.0790 | **0.7641** |
| 5 | S03 | CV Bahari Segar Abadi | 0.0278 | 0.0732 | **0.7248** |
| 6 | S06 | UD Cahaya Ikan Sejahtera | 0.0381 | 0.0783 | **0.6727** |
| 7 | S02 | PT Samudra Beku Nusantara | 0.0376 | 0.0715 | **0.6553** |
| 8 | S09 | PT Maritim Indo Beku | 0.0408 | 0.0701 | **0.6319** |
| 9 | S14 | UD Berkah Nelayan Baru | 0.0391 | 0.0652 | **0.6255** |
| 10 | S07 | CV Pelabuhan Baru Coldstorage | 0.0402 | 0.0642 | **0.6147** |
| 11 | S05 | PT Nelayan Makmur Sentosa | 0.0518 | 0.0730 | **0.5849** |
| 12 | S16 | UD Putra Muara Sejati | 0.0452 | 0.0590 | **0.5661** |
| 13 | S10 | UD Karya Samudra Jaya | 0.0578 | 0.0736 | **0.5601** |
| 14 | S13 | PT Nusantara Fish Supply | 0.0539 | 0.0650 | **0.5464** |
| 15 | S17 | PT Prima Coldchain Jakarta | 0.0697 | 0.0679 | **0.4932** |
| 16 | S22 | UD Rizki Bahari Jaya | 0.0541 | 0.0526 | **0.4930** |
| 17 | S24 | UD Aneka Ikan Muara | 0.0762 | 0.0358 | **0.3196** |
