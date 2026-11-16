# Task Tracker Skripsi Maulana (`C:\Skripsi_maul`)

> **Target Akhir:** Menyelesaikan skripsi hingga **BAB V** beserta aplikasi website SPK TOPSIS (Laravel + MySQL) sampai **siap sidang**.
> **Aturan Penting:** Jangan pernah sentuh `Folder Ori/`. Kerjakan bertahap per-phase. Jangan lanjut ke phase berikutnya sebelum user memberikan **Approve**.

---

## Status Saat Ini
- **Phase Aktif:** `Phase 1 — Data Riil, Wireframe (HTML & IMG), Pemodelan (UML/ERD), & BAB III`
- **Status Approval:** Phase 0 telah **Approved**; siap memulai Phase 1 di New Conversation.
- **Status Git/GitHub:** Terhubung ke `https://github.com/MaulanaSetyaPrawira/Pemilihan_supplier.git` (branch `main` sudah di-push).

---

## Roadmap & Checklist Pengerjaan

### Phase 0: Setup Workspace, GitHub, & Pematangan BAB I – BAB II *(Selesai — Approved)*
- [x] Inisialisasi struktur folder rapi (`docs/`, `wireframes/html/`, `wireframes/img/`, `diagrams/`, `app/`)
- [x] Buat `.gitignore` (meng-ignore `Folder Ori/`) dan inisialisasi Git lokal
- [x] Update `GEMINI.md` dan buat `task.md` sebagai memori lintas-conversation
- [x] Hubungkan ke repository GitHub & push commit awal
- [x] Diskusi & konfirmasi poin kritis BAB I & BAB II (skala kriteria/sub-kriteria, mekanisme penilaian 8 jenis ikan vs harga C2, daftar supplier Muara Baru)
- [x] Audit & revisi BAB I pada `Skripsi_Maulana_BAB_I_II_Revisi (1).docx`
- [x] Audit & revisi BAB II pada `Skripsi_Maulana_BAB_I_II_Revisi (1).docx`
- [x] **Approval User untuk Phase 0** → Commit → *Ganti ke New Conversation untuk Phase 1*

### Phase 1: Data Riil, Wireframe (HTML & IMG), Pemodelan (UML/ERD), & BAB III *(New Conversation)*
- [x] Kumpulkan/verifikasi data riil supplier Muara Baru, skor bobot 1–5 pemilik, dan hitung manual TOPSIS 5 kriteria di `docs/` (25 supplier dummy Muara Baru, bobot `[5,4,4,4,3]`, `docs/data_dan_perhitungan_topsis.md` & `docs/topsis_dataset.json`)
- [x] Buat wireframe terpisah per halaman dalam format HTML (`wireframes/html/`) dan gambar (`wireframes/img/`) (7 halaman: `01_login` s.d. `07_cetak_laporan_pdf`)
- [x] Review & approval wireframe oleh user (7 wireframe modern approved)
- [x] Buat pemodelan ERD, LRS, dan UML (Use Case, Activity, Sequence, Class Diagram) di `diagrams/` (`diagrams/pemodelan_sistem.md`, `diagrams/html/`, `diagrams/img/`)
- [x] Tulis & update **BAB III** pada dokumen `.docx`
- [ ] **Pengingat Wajib:** Ingatkan user untuk menginstal/menambahkan skill (Laravel, UI/Bootstrap, Testing) sebelum masuk Phase 2
- [ ] **Approval User untuk Phase 1** → Commit → *Ganti ke New Conversation untuk Phase 2*

### Phase 2: Implementasi Website (Laravel + MySQL) & Automated Testing *(New Conversation)*
- [ ] Setup project Laravel + Bootstrap + MySQL di `app/`
- [ ] Implementasi migrasi database & seeder sesuai ERD (`users`, `suppliers`, `kriterias`, `sub_kriterias`, `penilaians`, `hasil_topsis`)
- [ ] Implementasi fitur & **automated test** per modul:
  - [ ] Autentikasi (Login/Logout) + Test
  - [ ] CRUD Supplier, Kriteria, Sub-Kriteria, & Bobot (skala 1–5 + normalisasi) + Test
  - [ ] Input Penilaian & Perhitungan TOPSIS (uji akurasi rumus terhadap hitung manual) + Test
  - [ ] Riwayat Penilaian & Cetak Laporan PDF + Test
- [ ] **Approval User untuk Phase 2** → Commit → *Ganti ke New Conversation untuk Phase 3*

### Phase 3: Pengujian Sistem (Black Box & White Box) & Penulisan BAB IV *(New Conversation)*
- [ ] Eksekusi & dokumentasi Black Box Testing seluruh fungsionalitas
- [ ] Eksekusi & dokumentasi White Box Testing (pencocokan tahap demi tahap TOPSIS sistem vs manual)
- [ ] Ambil screenshot aplikasi berjalan
- [ ] Tulis & update **BAB IV** pada dokumen `.docx`
- [ ] **Approval User untuk Phase 3** → Commit → *Ganti ke New Conversation untuk Phase 4*

### Phase 4: Finalisasi BAB V, Abstrak, & Persiapan Sidang *(New Conversation)*
- [ ] Tulis **BAB V (Kesimpulan & Saran)** pada dokumen `.docx`
- [ ] Lengkapi **ABSTRAK** & **ABSTRACT**
- [ ] Periksa Daftar Isi, Daftar Tabel, Daftar Gambar, Daftar Pustaka, dan konsistensi seluruh bab
- [ ] **Approval Final User** → Commit final ke GitHub
