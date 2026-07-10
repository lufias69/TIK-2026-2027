# BAB X — ASESMEN PEMBELAJARAN

## 10.1 Prinsip Asesmen OBE

Asesmen dalam kurikulum OBE bertujuan **mengukur ketercapaian CPL** melalui penilaian CPMK dan Sub-CPMK. Prinsip asesmen mengacu pada SN-Dikti Pasal 19 sebagaimana dirangkum pada Tabel 10.1.

**Tabel 10.1 — Prinsip Asesmen OBE menurut SN-Dikti**

| Prinsip | Penjelasan |
|---------|------------|
| **Edukatif** | Memotivasi mahasiswa memperbaiki proses belajar |
| **Otentik** | Menilai kemampuan nyata dalam konteks yang relevan |
| **Objektif** | Berdasarkan kriteria yang jelas dan disepakati |
| **Akuntabel** | Prosedur dan kriteria jelas serta dipahami mahasiswa |
| **Transparan** | Hasil dapat diakses semua pemangku kepentingan |

---

## 10.2 Jenis dan Metode Asesmen

Ragam jenis dan metode asesmen beserta ranah yang diukur dan sifatnya disajikan pada Tabel 10.2.

**Tabel 10.2 — Jenis dan Metode Asesmen**

| Jenis Asesmen | Bentuk | Ranah yang Diukur | Sifat | Contoh Penggunaan |
|---------------|--------|-------------------|-------|-------------------|
| **Tes Tertulis** | UTS, UAS, kuis | Kognitif (C2–C5) | Sumatif (UTS/UAS), Formatif (kuis) | MK teori |
| **Tes Praktik** | Ujian praktik, live coding | Psikomotor (P2–P4) | Sumatif & Formatif | MK pemrograman, jaringan |
| **Proyek** | Tugas besar, capstone | Kognitif C6 + afektif | Sumatif | MK proyek, RPL |
| **Portofolio** | Kumpulan karya | Kognitif + psikomotor | Formatif → Sumatif | MK desain, multimedia |
| **Presentasi** | Seminar, demo | Komunikasi + afektif | Sumatif | Seminar, capstone |
| **Observasi** | Rubrik sikap | Afektif (A2–A4) | Formatif | Praktikum, kerja tim |
| **Peer/Self Assessment** | Penilaian sejawat | Afektif | Formatif | Proyek kelompok |

> *Asesmen **formatif** bertujuan memberi umpan balik untuk perbaikan proses belajar (tidak selalu memengaruhi nilai akhir), sedangkan asesmen **sumatif** menentukan pencapaian akhir dan berkontribusi pada nilai/kelulusan CPMK.*

---

## 10.3 Rubrik Penilaian

### 10.3.1 Rubrik Holistik (Umum)

Rubrik holistik untuk menilai ketercapaian CPMK secara menyeluruh disajikan pada Tabel 10.3.

**Tabel 10.3 — Rubrik Penilaian Holistik**

| Nilai | Huruf | Deskripsi Ketercapaian |
|:-----:|:-----:|------------------------|
| 80–100 | A | Menguasai seluruh CPMK dengan sangat baik, mampu menerapkan dalam konteks baru |
| 70–79 | B | Menguasai sebagian besar CPMK dengan baik |
| 60–69 | C | Menguasai CPMK pada tingkat cukup/minimum |
| 50–59 | D | Penguasaan CPMK kurang, perlu perbaikan |
| < 50 | E | Tidak mencapai CPMK |

### 10.3.2 Rubrik Analitik (Contoh — Proyek Pemrograman)

Contoh rubrik analitik untuk menilai proyek pemrograman secara terperinci disajikan pada Tabel 10.4.

**Tabel 10.4 — Contoh Rubrik Analitik Proyek Pemrograman**

| Kriteria | Bobot | Sangat Baik (4) | Baik (3) | Cukup (2) | Kurang (1) |
|----------|:-----:|-----------------|----------|-----------|------------|
| Fungsionalitas | 30% | Semua fitur berjalan sempurna | Sebagian besar berjalan | Fitur dasar berjalan | Banyak error |
| Kualitas Kode | 25% | Clean, terstruktur, terdokumentasi | Cukup rapi | Kurang terstruktur | Berantakan |
| Pemecahan Masalah | 25% | Solusi efisien & inovatif | Solusi tepat | Solusi standar | Solusi tidak tepat |
| Dokumentasi | 10% | Lengkap & jelas | Cukup lengkap | Minim | Tidak ada |
| Presentasi | 10% | Sangat komunikatif | Baik | Cukup | Kurang |

### 10.3.3 Rubrik Afektif (Sikap & Kerja Tim)

Rubrik penilaian ranah afektif (sikap dan kerja tim), termasuk penerapan nilai AIK, disajikan pada Tabel 10.5.

**Tabel 10.5 — Rubrik Penilaian Afektif (Sikap & Kerja Tim)**

| Aspek | Sangat Baik (4) | Baik (3) | Cukup (2) | Kurang (1) |
|-------|-----------------|----------|-----------|------------|
| Tanggung jawab | Selalu menyelesaikan tugas tepat waktu | Umumnya tepat waktu | Kadang terlambat | Sering terlambat |
| Kolaborasi | Kontributor aktif & konstruktif | Berkontribusi baik | Kontribusi terbatas | Pasif |
| Integritas | Selalu jujur & orisinal | Jujur | Cukup | Meragukan |
| Etika Islami | Menerapkan nilai AIK konsisten | Umumnya menerapkan | Kadang | Jarang |

---

## 10.4 Pengukuran Ketercapaian CPL

### 10.4.1 Alur Pengukuran

Ketercapaian CPL diukur secara berjenjang dari nilai asesmen hingga CPL tingkat prodi, sebagaimana digambarkan pada Gambar 10.1.

```
Nilai Sub-CPMK  →  Nilai CPMK  →  Nilai CPL per MK  →  Nilai CPL Program Studi
   (per asesmen)     (agregasi)      (agregasi)          (agregasi antar-MK)
```

**Gambar 10.1 — Alur Pengukuran Ketercapaian CPL secara Berjenjang**

### 10.4.2 Formula Perhitungan

**Nilai CPMK:**
$$N_{CPMK} = \sum_{i} (bobot_i \times nilai_i)$$
di mana $i$ adalah komponen asesmen yang mengukur CPMK tersebut.

**Ketercapaian CPL per Mata Kuliah (rata-rata berbobot):**
$$CPL_{MK} = \frac{\sum_{j} (w_j \times N_{CPMK_j})}{\sum_{j} w_j}$$
di mana $j$ adalah CPMK yang mendukung CPL tersebut, dan $w_j$ adalah bobot (proporsi SKS/porsi asesmen) CPMK ke-$j$. Penggunaan rata-rata **berbobot** memastikan CPMK dengan porsi lebih besar berkontribusi lebih besar pada ketercapaian CPL.

**Ketercapaian CPL Program Studi (rata-rata berbobot antar-MK):**
$$CPL_{prodi} = \frac{\sum_{k} (s_k \times CPL_{MK_k})}{\sum_{k} s_k}$$
di mana $k$ adalah mata kuliah pendukung CPL, dan $s_k$ adalah bobot mata kuliah (mis. SKS).

### 10.4.3 Ambang Ketercapaian

Kategori tingkat ketercapaian CPL beserta tindak lanjutnya ditetapkan pada Tabel 10.6.

**Tabel 10.6 — Ambang dan Kategori Ketercapaian CPL**

| Tingkat Ketercapaian CPL | Kategori | Tindak Lanjut |
|:------------------------:|----------|---------------|
| ≥ 80% mahasiswa nilai ≥ 60 | Sangat Baik | Pertahankan |
| 70–79% | Baik | Perbaikan minor |
| 60–69% | Cukup | Evaluasi metode pembelajaran |
| < 60% | Kurang | Revisi RPS & strategi (lihat BAB XI) |

---

## 10.5 Contoh Pemetaan Asesmen ke CPL

Contoh untuk mata kuliah TIN2111 Sistem Basis Data disajikan pada Tabel 10.7.

**Tabel 10.7 — Contoh Pemetaan Asesmen ke CPL (TIN2111 Sistem Basis Data)**

| Asesmen | Bobot | CPMK | CPL |
|---------|:-----:|------|:---:|
| Tugas 1 (ER Diagram) | 5% | CPMK-1 | CPL02 |
| Tugas 2 (Normalisasi) | 5% | CPMK-2 | CPL03 |
| Tugas 3 (SQL JOIN) | 5% | CPMK-3 | CPL03 |
| Kuis 1 & 2 | 10% | CPMK-2, CPMK-4 | CPL03, CPL05 |
| Proyek | 20% | CPMK-2, CPMK-3 | CPL03 |
| UTS | 25% | CPMK-1, CPMK-2 | CPL02, CPL03 |
| UAS | 25% | CPMK-3, CPMK-4 | CPL03, CPL05 |

**Agregasi ke CPL:**
- CPL02 diukur dari: Tugas 1 + UTS (porsi CPMK-1)
- CPL03 diukur dari: Tugas 2, 3 + Proyek + UTS + UAS (porsi CPMK-2, 3)
- CPL05 diukur dari: Kuis + UAS (porsi CPMK-4)

### Contoh Kedua — TIN5117 Data Science (pengukuran CPL06)

Contoh pemetaan asesmen untuk mata kuliah data/AI yang mengukur CPL06 disajikan pada Tabel 10.8.

**Tabel 10.8 — Contoh Pemetaan Asesmen ke CPL (TIN5117 Data Science)**

| Asesmen | Bobot | CPMK | CPL |
|---------|:-----:|------|:---:|
| Tugas 1 (Pengumpulan & EDA data) | 10% | CPMK-1 | CPL06 |
| Tugas 2 (Analisis statistik) | 10% | CPMK-2 | CPL06, CPL01 |
| Proyek (Model prediktif end-to-end) | 25% | CPMK-3 | CPL06 |
| Presentasi & visualisasi wawasan | 10% | CPMK-4 | CPL06, CPL02 |
| UTS | 20% | CPMK-1, CPMK-2 | CPL06, CPL01 |
| UAS | 25% | CPMK-3, CPMK-4 | CPL06, CPL02 |

**Agregasi ke CPL:**
- **CPL06** (utama) diukur dari seluruh komponen (Tugas 1–2, Proyek, Presentasi, UTS, UAS)
- CPL01 diukur dari: Tugas 2 + UTS (porsi analisis statistik)
- CPL02 diukur dari: Presentasi + UAS (porsi komunikasi wawasan)

> *Mata kuliah data/AI (Data Science, Data Mining, Analitik Data, Kecerdasan Buatan) menjadi wahana utama pengukuran CPL06; etika data dinilai melalui komponen presentasi/proyek (Sub-CPMK 4.2).*

---

## 10.6 Mekanisme Remediasi dan Perbaikan

Apabila mahasiswa **belum mencapai ambang ketercapaian CPMK/CPL** (nilai < 60 pada CPMK tertentu), diberlakukan mekanisme berikut:

**Tabel 10.9 — Mekanisme Remediasi dan Perbaikan Ketercapaian CPMK/CPL**

| Tahap | Tindakan | Penanggung Jawab |
|-------|----------|------------------|
| 1. Identifikasi | Dosen mengidentifikasi CPMK/Sub-CPMK yang belum tercapai dari lembar penilaian | Dosen pengampu |
| 2. Umpan balik | Pemberian umpan balik spesifik dan konsultasi kepada mahasiswa | Dosen pengampu |
| 3. Remediasi | Tugas perbaikan, pembelajaran ulang, atau asesmen ulang terbatas pada CPMK yang belum tercapai | Dosen pengampu |
| 4. Penilaian ulang | Asesmen ulang untuk CPMK terkait (nilai maksimal sesuai ketentuan akademik) | Dosen pengampu |
| 5. Dokumentasi | Pencatatan hasil remediasi dalam lembar penilaian CPMK | Dosen + GKM |

> *Remediasi berfokus pada **CPMK yang belum tercapai**, bukan mengulang seluruh mata kuliah, sejalan dengan prinsip OBE yang berorientasi pada penguasaan capaian. Ketentuan nilai maksimal hasil remediasi mengikuti peraturan akademik universitas.*

---

## 10.7 Dokumentasi dan Pelaporan Asesmen

1. Dosen mendokumentasikan nilai per Sub-CPMK dalam **lembar penilaian CPMK**.
2. Ketercapaian CPL per MK dilaporkan di akhir semester ke **Gugus Penjaminan Mutu Prodi**.
3. Rekapitulasi CPL tingkat prodi disusun tiap tahun sebagai dasar evaluasi kurikulum (BAB XI).
4. Data disimpan dalam sistem informasi akademik/LMS untuk keterlacakan.

---

*Asesmen ini menjadi sumber data utama bagi mekanisme Continuous Quality Improvement (CQI) yang dibahas pada BAB XI.*
