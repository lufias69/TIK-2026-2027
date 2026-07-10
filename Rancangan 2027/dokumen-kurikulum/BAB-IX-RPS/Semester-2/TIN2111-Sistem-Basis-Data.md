# RENCANA PEMBELAJARAN SEMESTER (RPS)
## TIN2111 — Sistem Basis Data

## A. IDENTITAS MATA KULIAH

| Item | Keterangan |
|------|------------|
| Nama Program Studi | S1 Teknologi Informasi |
| Nama Mata Kuliah | Sistem Basis Data |
| Kode Mata Kuliah | TIN2111 |
| Bobot SKS | 4 SKS (= 200 menit tatap muka/minggu) |
| Semester | 2 |
| Kelompok MK | MKW-P (Wajib Prodi) |
| Mata Kuliah Prasyarat | — |
| Dosen Pengampu | [Nama dosen] |
| Tanggal Penyusunan | [Tanggal] |

---

## B. CAPAIAN PEMBELAJARAN

### CPL yang Dibebankan pada Mata Kuliah

| Kode CPL | Rumusan CPL |
|----------|-------------|
| CPL02 | Mampu mengidentifikasi, menganalisis, dan mendefinisikan permasalahan computing yang kompleks menggunakan prinsip-prinsip ilmu komputer, teknologi informasi, dan pengetahuan domain yang relevan |
| CPL03 | Mampu merancang, mengimplementasikan, dan mengevaluasi solusi berbasis computing yang memenuhi kebutuhan tertentu, dengan mempertimbangkan aspek keandalan, keamanan, efisiensi, dan keterbatasan |
| CPL05 | Mampu menerapkan prinsip-prinsip keamanan siber, manajemen risiko, dan tata kelola informasi dalam merancang dan mengelola sistem informasi terdistribusi yang aman dan andal |

### Capaian Pembelajaran Mata Kuliah (CPMK)

| Kode | Rumusan CPMK | CPL |
|------|--------------|:---:|
| CPMK-1 | Menganalisis (C4) kebutuhan data suatu sistem dan memodelkannya dalam diagram ER | CPL02 |
| CPMK-2 | Merancang (C6) skema basis data relasional dengan normalisasi hingga 3NF | CPL03 |
| CPMK-3 | Menerapkan (C3) query SQL untuk manipulasi dan pengambilan data | CPL03 |
| CPMK-4 | Mengevaluasi (C5) aspek integritas dan keamanan basis data | CPL05 |

> *Sub-CPMK beserta bobot dan indikatornya dirinci pada Bagian F.*

---

## C. DESKRIPSI SINGKAT MATA KULIAH

Mata kuliah ini membahas perancangan basis data relasional secara komprehensif, mencakup model ER, normalisasi, SQL, transaksi, integritas, dan keamanan data. Mahasiswa memperoleh pengalaman praktis dalam implementasi DBMS melalui praktikum. Mata kuliah ini menjadi fondasi untuk pengembangan sistem informasi dan aplikasi berbasis data.

---

## D. BAHAN KAJIAN / MATERI PEMBELAJARAN

- **Bahan Kajian:** BK09 (Manajemen Data)
- Konsep basis data dan DBMS
- Model Entity-Relationship (ER) dan kardinalitas
- Transformasi ER ke skema relasional
- Normalisasi (1NF, 2NF, 3NF)
- SQL: DDL (CREATE, ALTER, DROP)
- SQL: DML (INSERT, UPDATE, DELETE, SELECT), JOIN, subquery
- Constraint integritas dan transaksi (ACID)
- Hak akses dan keamanan basis data

---

## E. METODE PEMBELAJARAN

| Metode | Penerapan |
|--------|-----------|
| Ceramah interaktif | Penyampaian konsep basis data, normalisasi, dan SQL |
| Latihan terbimbing | Praktik perancangan ERD dan penulisan query SQL |
| Praktikum di lab | Implementasi DBMS, query, transaksi, dan keamanan |
| Studi kasus | Perancangan basis data untuk sistem nyata |
| Proyek | Implementasi basis data lengkap dengan constraint dan keamanan |

---

## F. SUB-CPMK, INDIKATOR, DAN BOBOT (Inti OBE)

Bobot tiap Sub-CPMK = jumlah minggu ÷ 14. UTS (minggu 8) dan UAS (minggu 16) adalah wadah pengukuran, tanpa bobot tersendiri.

| Kode | Sub-CPMK (kemampuan akhir terukur) | CPMK | Minggu | Bobot | Indikator Ketercapaian (terukur) | Instrumen |
|------|-------------------------------------|:----:|:------:|:-----:|----------------------------------|-----------|
| Sub-CPMK 1 | Mengidentifikasi entitas, atribut, dan relasi dari kasus | CPMK-1 | 1–2 (2 mgg) | 14,3% | Kelengkapan ≥ 80% identifikasi entitas, atribut, dan relasi | Kuis 1 |
| Sub-CPMK 2 | Menyusun diagram ER lengkap dengan kardinalitas | CPMK-1 | 3–4 (2 mgg) | 14,3% | Ketepatan ≥ 75% penyusunan ERD dengan kardinalitas | Soal UTS |
| Sub-CPMK 3 | Mentransformasi ER ke skema relasional | CPMK-2 | 5–6 (2 mgg) | 14,3% | Ketepatan ≥ 80% transformasi ER ke skema relasional | Tugas 1 |
| Sub-CPMK 4 | Menerapkan normalisasi 1NF–3NF | CPMK-2 | 7 (1 mgg) | 7,1% | Kebenaran ≥ 75% proses normalisasi hingga 3NF | Soal UTS |
| Sub-CPMK 5 | Menulis query DDL (CREATE, ALTER, DROP) | CPMK-3 | 9–10 (2 mgg) | 14,3% | Ketepatan ≥ 80% penulisan DDL sesuai sintaks | Tugas 2 |
| Sub-CPMK 6 | Menulis query DML dan JOIN kompleks | CPMK-3 | 11–12 (2 mgg) | 14,3% | Ketepatan ≥ 75% query DML, JOIN, dan subquery | Kuis 2 |
| Sub-CPMK 7 | Menerapkan constraint integritas dan transaksi (ACID) | CPMK-4 | 13–14 (2 mgg) | 14,3% | Kelengkapan ≥ 80% implementasi constraint dan transaksi | Proyek |
| Sub-CPMK 8 | Mengevaluasi hak akses dan keamanan basis data | CPMK-4 | 15 (1 mgg) | 7,1% | Ketepatan ≥ 75% evaluasi hak akses dan keamanan DB | Soal UAS |
| **Total** | | | **14 mgg** | **100%** | | |

> *UTS (minggu 8) mengukur Sub-CPMK 2 dan 4 (materi minggu 3–7). UAS (minggu 16) mengukur Sub-CPMK 8 (materi minggu 15). Sub-CPMK 1 dan 6 diukur melalui Kuis, Sub-CPMK 3 dan 5 melalui Tugas, dan Sub-CPMK 7 melalui Proyek.*

---

## G. RENCANA PEMBELAJARAN MINGGUAN

| Minggu | Sub-CPMK | Materi | Metode | Instrumen Penilaian |
|:------:|----------|--------|--------|---------------------|
| 1 | Sub-CPMK 1 | Konsep basis data & DBMS | Ceramah | — |
| 2 | Sub-CPMK 1 | Identifikasi entitas, atribut, dan relasi | Latihan terbimbing | Kuis 1 |
| 3 | Sub-CPMK 2 | Diagram ER & notasi kardinalitas | Ceramah, latihan | — |
| 4 | Sub-CPMK 2 | Penyusunan ERD lengkap untuk kasus nyata | Studi kasus | — |
| 5 | Sub-CPMK 3 | Transformasi ER ke skema relasional | Ceramah, praktikum | — |
| 6 | Sub-CPMK 3 | Verifikasi & validasi skema relasional | Praktikum | Tugas 1 |
| 7 | Sub-CPMK 4 | Normalisasi (1NF, 2NF, 3NF) | Latihan terbimbing | — |
| 8 | — | **Ujian Tengah Semester (UTS)** — mengukur Sub-CPMK 2 & 4 | Tes | Soal UTS |
| 9 | Sub-CPMK 5 | SQL DDL: CREATE, ALTER, DROP | Ceramah, praktikum | — |
| 10 | Sub-CPMK 5 | Praktik DDL pada DBMS | Praktikum | Tugas 2 |
| 11 | Sub-CPMK 6 | SQL DML: INSERT, UPDATE, DELETE, SELECT | Ceramah, praktikum | — |
| 12 | Sub-CPMK 6 | JOIN & subquery kompleks | Praktikum, studi kasus | Kuis 2 |
| 13 | Sub-CPMK 7 | Constraint integritas (PK, FK, unique, check) | Ceramah, praktikum | — |
| 14 | Sub-CPMK 7 | Transaksi & ACID | Praktikum, proyek | Proyek |
| 15 | Sub-CPMK 8 | Hak akses (GRANT/REVOKE) & keamanan DB | Praktikum | — |
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
1. Elmasri, R. & Navathe, S. B. (2016). *Fundamentals of Database Systems* (7th ed.). Pearson.
2. Silberschatz, A., Korth, H. F., & Sudarshan, S. (2019). *Database System Concepts* (7th ed.). McGraw-Hill.

**Pendukung:**
1. Connolly, T. & Begg, C. (2015). *Database Systems: A Practical Approach* (6th ed.). Pearson.
2. Date, C. J. (2003). *An Introduction to Database Systems* (8th ed.). Addison-Wesley.

---

*RPS ini disusun dengan metodologi bobot Sub-CPMK berbasis minggu (OBE), mengacu pada Dokumen Kurikulum Prodi S1 TI 2027.*