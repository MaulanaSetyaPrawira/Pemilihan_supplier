# Pemodelan Basis Data & UML — SPK Pemilihan Supplier Rumah Cue

Dokumen ini merangkum seluruh rancangan basis data (**ERD & LRS**) serta pemodelan sistem (**Use Case, Activity, Sequence, dan Class Diagram**) yang diselaraskan dengan alur aplikasi pada `wireframes/` (Opsi B: ketersediaan 8 jenis ikan per gudang & penilaian TOPSIS per jenis ikan).

## 1. Daftar Entitas Basis Data (8 Tabel MySQL)
1. `users` — Akun Pemilik/Admin (`id`, `name`, `email`, `password`, `role`)
2. `suppliers` — Master 25 Gudang Muara Baru (`id`, `kode_supplier`, `nama_supplier`, `alamat`, `no_telepon`, `status`)
3. `jenis_ikans` — Master 8 Jenis Ikan (`id`, `kode_ikan`, `nama_ikan`)
4. `supplier_ikan` — Tabel Relasi M:N ketersediaan ikan per gudang (`id`, `supplier_id`, `jenis_ikan_id`)
5. `kriterias` — 5 Kriteria Penilaian (`id`, `kode_kriteria`, `nama_kriteria`, `tipe`, `skor_kepentingan`, `bobot_normalisasi`)
6. `sub_kriterias` — Rubrik Penilaian Skala 1–5 per Kriteria (`id`, `kriteria_id`, `nilai`, `keterangan`)
7. `penilaians` — Skor Kinerja Supplier per Periode & Jenis Ikan (`id`, `periode`, `jenis_ikan_id`, `supplier_id`, `kriteria_id`, `user_id`, `nilai`)
8. `hasil_topsis` — Hasil Akhir Jarak Ideal & Peringkat (`id`, `periode`, `jenis_ikan_id`, `supplier_id`, `d_plus`, `d_minus`, `nilai_preferensi`, `peringkat`)

## 2. Daftar File Diagram (`diagrams/img/` & `diagrams/html/`)
- **ERD:** `01_erd.png` / `01_erd.html`
- **LRS:** `02_lrs.png` / `02_lrs.html`
- **Use Case Diagram:** `03_use_case.png` / `03_use_case.html`
- **Activity Diagram:** `04_activity.png` / `04_activity.html`
- **Sequence Diagram:** `05_sequence.png` / `05_sequence.html`
- **Class Diagram:** `06_class.png` / `06_class.html`
