# Aturan dan Konteks Proyek Skripsi Maulana (`C:\Skripsi_maul`)

## Larangan Mutlak (Wajib Dipatuhi di Setiap Percakapan)
- **JANGAN PERNAH menyentuh, membaca, mengubah, atau menghapus folder `C:\Skripsi_maul\Folder Ori` beserta seluruh isinya** untuk alasan apa pun di keseluruhan proyek ini.
- Fokus utama dokumen skripsi berada pada file `C:\Skripsi_maul\Skripsi_Maulana_BAB_I_II_Revisi (1).docx`.

## Tujuan Akhir Proyek
- Menyelesaikan skripsi secara penuh hingga **BAB V** beserta sistem website pendukungnya sampai **siap untuk sidang skripsi**.

## Protokol Wajib Setiap Membuka New Conversation
1. **Baca `C:\Skripsi_maul\task.md` terlebih dahulu** sebelum melakukan tindakan apa pun.
2. Laporkan secara singkat posisi Phase saat ini, apa yang sudah selesai, dan berikan saran apa yang harus diubah, diselesaikan, atau dicek berikutnya.
3. **Aturan Per-Phase & Hemat Token**:
   - Kerjakan **1 Phase per Conversation**. Jangan melompat ke phase berikutnya sebelum user memberikan **Approve** eksplisit pada phase yang sedang berjalan.
   - Setelah user memberi Approve dan progres di-commit ke GitHub, **ingatkan user untuk membuka New Conversation** untuk phase berikutnya agar tidak boros token.
4. **Aturan Kualitas & Teknis**:
   - Jangan terburu-buru; matangkan setiap bagian terutama pada Phase 0 (BAB I & BAB II).
   - Selalu **commit ke Git** setiap selesai mengerjakan suatu bagian/progres.
   - Sebelum memulai perancangan/coding website (transisi dari Phase 1 ke Phase 2), **ingatkan user untuk menginstal/menambahkan skill yang dibutuhkan** (Laravel, UI/Bootstrap, Testing) agar tidak terjadi *AI slop*.
   - Sebelum coding sistem, buat **wireframe terpisah** dalam format HTML dan gambar (`wireframes/html/` dan `wireframes/img/`).
   - Saat implementasi website dimulai, **selalu lakukan pengujian (automated test)** pada setiap fitur agar bebas bug dan akurat.
   - Setiap progres wajib dicatat dan diperbarui di `task.md`.
5. **Aturan Efisiensi Model & Token**:
   - Sebelum mengerjakan tugas baru yang spesifik, **selalu beri saran model yang paling cocok** (misal: model ringan seperti *Flash* untuk tugas sederhana/format/commit, atau *Gemini 4 Hydrogen / Argon / Pro* atau *Claude* untuk penulisan bab skripsi, analisis mendalam, arsitektur, dan coding kompleks).
   - Setelah tugas tersebut selesai dikerjakan, **ingatkan user kembali untuk mengganti model** jika perlu agar tetap hemat token.

## Konteks dan Tujuan Skripsi
- **Judul Skripsi**: SISTEM PENDUKUNG KEPUTUSAN PEMILIHAN SUPPLIER TERBAIK UNTUK BAHAN BAKU IKAN PINDANG MENGGUNAKAN METODE TOPSIS BERBASIS WEBSITE (STUDI KASUS: RUMAH CUE DI PASAR KEBAYORAN LAMA)
- **Penulis**: Maulana Setya Prawira (NIM: 221011400322)
- **Program Studi / Fakultas / Universitas**: Teknik Informatika / Fakultas Ilmu Komputer / Universitas Pamulang (2026)
- **Dosen Pembimbing**: Dede Sunandar, S.Kom., M.Kom. (NIDN: 0418028604)
- **Ketua Program Studi**: Dr. Eng. Ahmad Musyafa, S.Kom., M.Kom. (NIDN: 0425018609)

## Objek Penelitian & Studi Kasus
- **Objek**: Rumah Cue di Pasar Kebayoran Lama, Jakarta Selatan (beroperasi sejak 2005, ~35 karyawan).
- **Kebutuhan Bahan Baku**: ~3,5 ton ikan beku per hari, mencakup 8 jenis ikan (cakalang, maesang, layang, bandeng, salem, kembung banjar, deho, dan cucut).
- **Alternatif Supplier**: Gudang-gudang ikan beku di kawasan Muara Baru, Jakarta Utara.

## Metode & Kriteria Penilaian (TOPSIS)
- **Metode SPK**: *Technique for Order Preference by Similarity to Ideal Solution* (TOPSIS).
- **Pembobotan**: Ditentukan langsung oleh pemilik Rumah Cue menggunakan skala Likert 1–5 dan dinormalisasi ($\sum w_j = 1$, dengan $w_j = s_j / \sum s_k$), tanpa metode pembobotan lain (bukan AHP).
- **Lima Kriteria Penilaian**:
  1. **C1**: Kualitas dan kesegaran ikan (*Benefit*) — skala angka.
  2. **C2**: Harga ikan per kilogram (*Cost*) — dalam rupiah per kg.
  3. **C3**: Ketepatan waktu pengiriman (*Benefit*) — skala angka.
  4. **C4**: Ketersediaan stok ikan (*Benefit*) — skala angka.
  5. **C5**: Responsivitas dan kemudahan komunikasi (*Benefit*) — skala angka.

## Spesifikasi Teknis & Pengembangan Sistem
- **Platform & Bahasa**: Website menggunakan PHP (Framework **Laravel** dengan arsitektur MVC & Blade), HTML, CSS (**Bootstrap**), JavaScript, dan basis data **MySQL**.
- **Entitas Basis Data (ERD)**: `users`, `suppliers`, `kriterias`, `sub_kriterias`, `penilaians`, `hasil_topsis`.
- **Pemodelan UML**: Use Case Diagram, Activity Diagram, Sequence Diagram, dan Class Diagram.
- **Metode Pengembangan Sistem**: *Rapid Application Development* (RAD) — *Requirements Planning*, *User Design*, *Construction*, *Cutover*.
- **Metode Pengujian**: *Black Box Testing* (fungsionalitas UI/CRUD/laporan PDF) dan *White Box Testing* (uji akurasi perhitungan TOPSIS pada sistem dibandingkan dengan perhitungan manual).
- **Batasan Sistem**: Digunakan oleh pemilik/admin Rumah Cue untuk menghasilkan rekomendasi peringkat supplier dan menyimpan riwayat penilaian; tidak mencakup transaksi pembelian atau pembayaran online.
