# RENCANA PEMBELAJARAN SEMESTER (RPS)
## TIN5245 — Sistem Basis Data Lanjut

## A. IDENTITAS MATA KULIAH

| Item | Keterangan |
|------|------------|
| Nama Program Studi | S1 Teknologi Informasi |
| Nama Mata Kuliah | Sistem Basis Data Lanjut |
| Kode Mata Kuliah | TIN5245 |
| Bobot SKS | 4 SKS (= 200 menit tatap muka/minggu) |
| Semester | 5 |
| Kelompok MK | MKP (Pilihan/Peminatan) |
| Mata Kuliah Prasyarat | TIN2111 (Sistem Basis Data) |
| Dosen Pengampu | [Nama dosen] |
| Tanggal Penyusunan | [Tanggal] |

---

## B. CAPAIAN PEMBELAJARAN

### CPL yang Dibebankan pada Mata Kuliah

| Kode CPL | Rumusan CPL |
|----------|-------------|
| CPL02 | Mampu mengidentifikasi, menganalisis, dan mendefinisikan masalah computing kompleks |
| CPL03 | Mampu merancang, mengimplementasikan, dan mengevaluasi solusi berbasis computing |
| CPL05 | Mampu menerapkan prinsip keamanan siber, manajemen risiko, dan tata kelola informasi |

### Capaian Pembelajaran Mata Kuliah (CPMK)

| Kode | Rumusan CPMK | CPL |
|------|--------------|:---:|
| CPMK-1 | Mahasiswa mampu menjelaskan (C2) konsep basis data terdistribusi dan NoSQL | CPL02 |
| CPMK-2 | Mahasiswa mampu menerapkan (C3) data warehouse dan ETL | CPL03 |
| CPMK-3 | Mahasiswa mampu menerapkan (C3) optimasi query dan tuning performa | CPL03 |
| CPMK-4 | Mahasiswa mampu mengevaluasi (C5) keamanan basis data lanjut | CPL05 |

> *Sub-CPMK beserta bobot dan indikatornya dirinci pada Bagian F.*

---

## C. DESKRIPSI SINGKAT MATA KULIAH

Mata kuliah ini membekali mahasiswa dengan konsep basis data terdistribusi, NoSQL, data warehouse, optimasi query, tuning performa, dan keamanan basis data lanjut. Mahasiswa mempelajari MongoDB/Cassandra, ETL pipeline, indexing, partisi, serta evaluasi keamanan basis data.

---

## D. BAHAN KAJIAN / MATERI PEMBELAJARAN

- **Bahan Kajian:** BK09 (Manajemen Data)
- Basis data terdistribusi
- NoSQL (MongoDB/Cassandra — document, key-value, column)
- Data warehouse dan ETL
- Optimasi query dan indexing
- Partisi dan tuning performa
- Keamanan basis data lanjut

---

## E. METODE PEMBELAJARAN

| Metode | Penerapan |
|--------|-----------|
| Ceramah interaktif | Penyampaian konsep basis data lanjut |
| Praktikum laboratorium | Implementasi NoSQL, data warehouse, optimasi query |
| Proyek berbasis kasus | Tuning performa dan evaluasi keamanan basis data |

---

## F. SUB-CPMK, INDIKATOR, DAN BOBOT (Inti OBE)

Bobot tiap Sub-CPMK = jumlah minggu ÷ 14. UTS (minggu 8) dan UAS (minggu 16) adalah wadah pengukuran, tanpa bobot tersendiri.

| Kode | Sub-CPMK (kemampuan akhir terukur) | CPMK | Minggu | Bobot | Indikator Ketercapaian (terukur) | Instrumen |
|------|-------------------------------------|:----:|:------:|:-----:|----------------------------------|-----------|
| Sub-CPMK 1 | Menjelaskan konsep basis data terdistribusi dan NoSQL | CPMK-1 | 1–2 (2 mgg) | 14,3% | Ketepatan ≥ 80% menjelaskan DB terdistribusi dan NoSQL | Kuis 1 |
| Sub-CPMK 2 | Menjelaskan kategori dan karakteristik NoSQL | CPMK-1 | 3–4 (2 mgg) | 14,3% | Ketepatan ≥ 75% menjelaskan kategori NoSQL | Soal UTS |
| Sub-CPMK 3 | Menerapkan implementasi NoSQL (MongoDB/Cassandra) | CPMK-2 | 5–6 (2 mgg) | 14,3% | Kelengkapan ≥ 80% implementasi NoSQL | Tugas 1 |
| Sub-CPMK 4 | Menerapkan data warehouse dan ETL pipeline | CPMK-2 | 7 (1 mgg) | 7,1% | Kebenaran ≥ 75% implementasi data warehouse dan ETL | Soal UTS |
| Sub-CPMK 5 | Menerapkan optimasi query dan indexing | CPMK-3 | 9–10 (2 mgg) | 14,3% | Ketepatan ≥ 80% optimasi query dan indexing | Tugas 2 |
| Sub-CPMK 6 | Menerapkan partisi dan sharding | CPMK-3 | 11–12 (2 mgg) | 14,3% | Ketepatan ≥ 75% implementasi partisi dan sharding | Kuis 2 |
| Sub-CPMK 7 | Menerapkan tuning performa basis data | CPMK-3 | 13–14 (2 mgg) | 14,3% | Kelengkapan ≥ 80% tuning performa | Proyek |
| Sub-CPMK 8 | Mengevaluasi keamanan basis data lanjut | CPMK-4 | 15 (1 mgg) | 7,1% | Ketepatan ≥ 75% evaluasi keamanan DB lanjut | Soal UAS |
| **Total** | | | **14 mgg** | **100%** | | |

> *UTS (minggu 8) mengukur Sub-CPMK 2 dan 4 (materi minggu 3–7). UAS (minggu 16) mengukur Sub-CPMK 8 (materi minggu 15). Sub-CPMK 1 dan 6 diukur melalui Kuis, Sub-CPMK 3 dan 5 melalui Tugas, dan Sub-CPMK 7 melalui Proyek.*

---

## G. RENCANA PEMBELAJARAN MINGGUAN

| Minggu | Sub-CPMK | Materi | Metode | Instrumen Penilaian |
|:------:|----------|--------|--------|---------------------|
| 1 | Sub-CPMK 1 | Konsep basis data terdistribusi | Ceramah | — |
| 2 | Sub-CPMK 1 | Karakteristik dan kategori NoSQL | Ceramah, diskusi | Kuis 1 |
| 3 | Sub-CPMK 2 | NoSQL document (MongoDB) | Praktikum | — |
| 4 | Sub-CPMK 2 | NoSQL key-value dan column (Cassandra) | Praktikum | — |
| 5 | Sub-CPMK 3 | Implementasi MongoDB — operasi CRUD | Praktikum terbimbing | — |
| 6 | Sub-CPMK 3 | Studi kasus implementasi NoSQL | Studi kasus | Tugas 1 |
| 7 | Sub-CPMK 4 | Data warehouse dan ETL pipeline | Praktikum | — |
| 8 | — | **Ujian Tengah Semester (UTS)** — mengukur Sub-CPMK 2 & 4 | Tes | Soal UTS |
| 9 | Sub-CPMK 5 | Optimasi query | Praktikum | — |
| 10 | Sub-CPMK 5 | Indexing strategi | Praktikum | Tugas 2 |
| 11 | Sub-CPMK 6 | Partisi dan sharding | Praktikum | — |
| 12 | Sub-CPMK 6 | Studi kasus partisi dan sharding | Praktikum, studi kasus | Kuis 2 |
| 13 | Sub-CPMK 7 | Tuning performa basis data | Praktikum | — |
| 14 | Sub-CPMK 7 | Studi kasus tuning performa | Proyek | Proyek |
| 15 | Sub-CPMK 8 | Keamanan basis data lanjut | Ceramah, studi kasus | — |
| 16 | — | **Ujian Akhir Semester (UAS)** — mengukur Sub-CPMK 8 | Tes | Soal UAS |

---

## H. REKAPITULASI BOBOT PER INSTRUMEN

| Instrumen | Sub-CPMK yang Diukur | Total Bobot |
|-----------|----------------------|:-----------:|
| Kuis 1 | Sub-CPMK 1 | 14,3% |
| Soal UTS | Sub-CPMK 2, 4 | 21,4% |
| Tugas 1 | Sub-CPMK 3 | 14,3% |
| Tugas 2 | Sub-CPMK 5 | 14,3% |
| Kuis 2 | Sub-CPMK 6 | 14,3% |
| Proyek | Sub-CPMK 7 | 14,3% |
| Soal UAS | Sub-CPMK 8 | 7,1% |
| **Total** | | **100%** |

### Konversi Nilai Akhir

| Nilai Angka | Huruf | Bobot | Kategori |
|:-----------:|:-----:|:-----:|----------|
| 80–100 | A | 4,00 | Sangat Baik |
| 70–79 | B | 3,00 | Baik |
| 60–69 | C | 2,00 | Cukup |
| 50–59 | D | 1,00 | Kurang |
| < 50 | E | 0,00 | Gagal |

> *Ambang ketercapaian minimum tiap Sub-CPMK adalah nilai ≥ 60.*

---

## I. REFERENSI

**Utama:**
1. Elmasri, R. & Navathe, S.B. (2016). *Fundamentals of Database Systems* (7th ed.). Pearson.
2. Sadalage, P.J. & Fowler, M. (2012). *NoSQL Distilled*. Addison-Wesley.

**Pendukung:**
1. Kimball, R. & Ross, M. (2013). *The Data Warehouse Toolkit* (3rd ed.). Wiley.

---

*RPS ini disusun dengan metodologi bobot Sub-CPMK berbasis minggu (OBE), mengacu pada Dokumen Kurikulum Prodi S1 TI 2027.*