# BAB VIII — CPMK DAN SUB-CPMK

## 8.1 Konsep CPMK dan Sub-CPMK

Dalam kerangka OBE, CPL diturunkan menjadi capaian yang lebih spesifik pada tingkat mata kuliah sebagaimana digambarkan pada Gambar 8.1:

```
CPL (Capaian Pembelajaran Lulusan)
   ↓ diturunkan menjadi
CPMK (Capaian Pembelajaran Mata Kuliah)
   ↓ dirinci menjadi
Sub-CPMK (indikator terukur per tahap pembelajaran)
   ↓ dinilai melalui
Asesmen (tugas, kuis, UTS, UAS, proyek)
```

**Gambar 8.1 — Alur Penurunan CPL menjadi CPMK, Sub-CPMK, dan Asesmen**

Definisi istilah CPMK dan Sub-CPMK diberikan pada Tabel 8.1.

**Tabel 8.1 — Definisi CPMK dan Sub-CPMK**

| Istilah | Definisi |
|---------|----------|
| **CPMK** | Kemampuan yang dibebankan pada mata kuliah untuk mendukung pencapaian CPL. Satu MK memiliki 3–5 CPMK. |
| **Sub-CPMK** | Kemampuan akhir tiap tahap belajar yang bersifat spesifik, terukur, dan dapat diamati; menjadi dasar penilaian mingguan. |

---

## 8.2 Kaidah Perumusan CPMK

### 8.2.1 Formula Perumusan

Setiap CPMK dirumuskan dengan struktur:

> **[Kata Kerja Operasional (KKO)] + [Objek] + [Konteks/Kondisi]**

Contoh: *"Mahasiswa mampu **merancang** (C6) **basis data relasional** **untuk kasus sistem informasi nyata** dengan menerapkan normalisasi hingga 3NF."*

### 8.2.2 Taksonomi Bloom (Ranah Kognitif)

Kata kerja operasional (KKO) untuk setiap tingkat ranah kognitif Bloom disajikan pada Tabel 8.2.

**Tabel 8.2 — Taksonomi Bloom Ranah Kognitif dan KKO Representatif**

| Level | KKO Representatif | Penggunaan |
|:-----:|-------------------|------------|
| C2 — Memahami | menjelaskan, mengklasifikasi, merangkum | MK dasar/pengantar |
| C3 — Menerapkan | menerapkan, menghitung, mengimplementasikan | MK keterampilan |
| C4 — Menganalisis | menganalisis, membandingkan, menguji | MK analisis |
| C5 — Mengevaluasi | mengevaluasi, menilai, mengkritik | MK lanjut |
| C6 — Mencipta | merancang, membangun, mengembangkan | MK proyek/capstone |

### 8.2.3 Ranah Afektif (A) dan Psikomotor (P)

Tingkatan ranah afektif dan psikomotor beserta KKO-nya ditunjukkan pada Tabel 8.3.

**Tabel 8.3 — Ranah Afektif dan Psikomotor beserta KKO**

| Ranah | Level | Contoh KKO |
|-------|-------|-----------|
| Afektif | A1–A5 | menerima, merespons, menghargai, mengorganisasi, menginternalisasi |
| Psikomotor | P1–P5 | meniru, memanipulasi, mempresisikan, mengartikulasi, menaturalisasi |

---

## 8.3 Prinsip Traceability (Keterlacakan)

Setiap CPMK **wajib** dapat ditelusuri ke minimal satu CPL. Setiap Sub-CPMK **wajib** mendukung CPMK induknya, sebagaimana diilustrasikan pada Gambar 8.2.

```
CPL03 ──→ CPMK-2 (MK: PBO) ──→ Sub-CPMK 2.1
                             └─→ Sub-CPMK 2.2
                             └─→ Sub-CPMK 2.3
```

**Gambar 8.2 — Ilustrasi Keterlacakan CPL → CPMK → Sub-CPMK**

---

## 8.4 Contoh Penurunan CPMK Lengkap

Berikut contoh penurunan CPL → CPMK → Sub-CPMK untuk mata kuliah representatif dari tiap kluster kompetensi. Pola ini menjadi acuan untuk seluruh 65 mata kuliah dalam RPS (BAB IX).

---

### Contoh 1 — TIN1102 Algoritma dan Pemrograman (4 SKS)

**CPL didukung:** CPL01, CPL03

| Kode | CPMK | CPL |
|------|------|:---:|
| CPMK-1 | Mahasiswa mampu **menjelaskan** (C2) konsep algoritma dan notasi penulisannya | CPL01 |
| CPMK-2 | Mahasiswa mampu **menerapkan** (C3) struktur kontrol (percabangan, perulangan) dalam pemrograman | CPL01 |
| CPMK-3 | Mahasiswa mampu **merancang** (C6) program untuk menyelesaikan permasalahan komputasi dasar | CPL03 |

| Kode | Sub-CPMK | CPMK |
|------|----------|:----:|
| Sub-CPMK 1.1 | Menjelaskan definisi algoritma, ciri, dan cara penyajian (flowchart/pseudocode) | CPMK-1 |
| Sub-CPMK 1.2 | Mengklasifikasikan tipe data dan operator | CPMK-1 |
| Sub-CPMK 2.1 | Menerapkan struktur percabangan (if, switch) | CPMK-2 |
| Sub-CPMK 2.2 | Menerapkan struktur perulangan (for, while) | CPMK-2 |
| Sub-CPMK 2.3 | Menerapkan array dan fungsi | CPMK-2 |
| Sub-CPMK 3.1 | Merancang algoritma untuk kasus sederhana | CPMK-3 |
| Sub-CPMK 3.2 | Mengimplementasikan dan menguji program | CPMK-3 |

---

### Contoh 2 — TIN2111 Sistem Basis Data (4 SKS)

**CPL didukung:** CPL02, CPL03, CPL05

| Kode | CPMK | CPL |
|------|------|:---:|
| CPMK-1 | Mahasiswa mampu **menganalisis** (C4) kebutuhan data suatu sistem dan memodelkannya dalam diagram ER | CPL02 |
| CPMK-2 | Mahasiswa mampu **merancang** (C6) skema basis data relasional dengan normalisasi hingga 3NF | CPL03 |
| CPMK-3 | Mahasiswa mampu **menerapkan** (C3) query SQL untuk manipulasi dan pengambilan data | CPL03 |
| CPMK-4 | Mahasiswa mampu **mengevaluasi** (C5) aspek integritas dan keamanan basis data | CPL05 |

| Kode | Sub-CPMK | CPMK |
|------|----------|:----:|
| Sub-CPMK 1.1 | Mengidentifikasi entitas, atribut, dan relasi dari kasus | CPMK-1 |
| Sub-CPMK 1.2 | Menyusun diagram ER lengkap dengan kardinalitas | CPMK-1 |
| Sub-CPMK 2.1 | Mentransformasi ER ke skema relasional | CPMK-2 |
| Sub-CPMK 2.2 | Menerapkan normalisasi 1NF–3NF | CPMK-2 |
| Sub-CPMK 3.1 | Menulis query DDL (CREATE, ALTER) | CPMK-3 |
| Sub-CPMK 3.2 | Menulis query DML dan JOIN kompleks | CPMK-3 |
| Sub-CPMK 4.1 | Menerapkan constraint integritas | CPMK-4 |
| Sub-CPMK 4.2 | Mengevaluasi hak akses dan keamanan data | CPMK-4 |

---

### Contoh 3 — TIN303 Pemrograman Berorientasi Objek (4 SKS)

**CPL didukung:** CPL03

| Kode | CPMK | CPL |
|------|------|:---:|
| CPMK-1 | Mahasiswa mampu **menjelaskan** (C2) konsep dasar OOP | CPL03 |
| CPMK-2 | Mahasiswa mampu **menerapkan** (C3) enkapsulasi, pewarisan, dan polimorfisme | CPL03 |
| CPMK-3 | Mahasiswa mampu **merancang** (C6) aplikasi berorientasi objek dengan design pattern | CPL03 |

| Kode | Sub-CPMK | CPMK |
|------|----------|:----:|
| Sub-CPMK 1.1 | Menjelaskan kelas, objek, atribut, dan method | CPMK-1 |
| Sub-CPMK 1.2 | Membedakan paradigma prosedural dan OOP | CPMK-1 |
| Sub-CPMK 2.1 | Menerapkan enkapsulasi dan access modifier | CPMK-2 |
| Sub-CPMK 2.2 | Menerapkan pewarisan dan polimorfisme | CPMK-2 |
| Sub-CPMK 3.1 | Merancang class diagram untuk kasus nyata | CPMK-3 |
| Sub-CPMK 3.2 | Mengimplementasikan design pattern dasar | CPMK-3 |

---

### Contoh 4 — TIN6133 Prinsip Keamanan Siber (2 SKS)

**CPL didukung:** CPL04, CPL05

| Kode | CPMK | CPL |
|------|------|:---:|
| CPMK-1 | Mahasiswa mampu **menjelaskan** (C2) konsep keamanan informasi (CIA triad) dan lanskap ancaman | CPL05 |
| CPMK-2 | Mahasiswa mampu **menganalisis** (C4) kerentanan dan risiko keamanan pada sistem/jaringan | CPL04 |
| CPMK-3 | Mahasiswa mampu **menerapkan** (C3) mekanisme keamanan (kriptografi, autentikasi) | CPL05 |
| CPMK-4 | Mahasiswa mampu **mengevaluasi** (C5) kebijakan keamanan sesuai standar | CPL05 |

| Kode | Sub-CPMK | CPMK |
|------|----------|:----:|
| Sub-CPMK 1.1 | Menjelaskan CIA triad dan prinsip keamanan | CPMK-1 |
| Sub-CPMK 1.2 | Mengklasifikasi jenis ancaman dan serangan | CPMK-1 |
| Sub-CPMK 2.1 | Menganalisis kerentanan sistem (vulnerability assessment) | CPMK-2 |
| Sub-CPMK 2.2 | Menilai tingkat risiko dan dampak | CPMK-2 |
| Sub-CPMK 3.1 | Menerapkan enkripsi simetris/asimetris | CPMK-3 |
| Sub-CPMK 3.2 | Menerapkan mekanisme autentikasi dan otorisasi | CPMK-3 |
| Sub-CPMK 4.1 | Mengevaluasi kebijakan keamanan (ISO 27001/NIST) | CPMK-4 |

---

### Contoh 5 — TIN8144 Skripsi (4 SKS)

**CPL didukung:** CPL01, CPL02, CPL03

| Kode | CPMK | CPL |
|------|------|:---:|
| CPMK-1 | Mahasiswa mampu **menganalisis** (C4) permasalahan TI dan merumuskannya secara ilmiah | CPL02 |
| CPMK-2 | Mahasiswa mampu **merancang** (C6) solusi TI yang orisinal dan dapat dipertanggungjawabkan | CPL03 |
| CPMK-3 | Mahasiswa mampu **mengevaluasi** (C5) hasil penelitian dan mengomunikasikannya secara ilmiah | CPL01, CPL02 |

| Kode | Sub-CPMK | CPMK |
|------|----------|:----:|
| Sub-CPMK 1.1 | Merumuskan latar belakang dan rumusan masalah | CPMK-1 |
| Sub-CPMK 1.2 | Menyusun kajian pustaka dan kerangka teori | CPMK-1 |
| Sub-CPMK 2.1 | Merancang metodologi dan solusi | CPMK-2 |
| Sub-CPMK 2.2 | Mengimplementasikan solusi | CPMK-2 |
| Sub-CPMK 3.1 | Menganalisis dan membahas hasil | CPMK-3 |
| Sub-CPMK 3.2 | Menyusun laporan dan mempertahankan dalam ujian | CPMK-3 |

---

### Contoh 6 — TIN5117 Data Science (4 SKS)

**CPL didukung:** CPL06 (utama), CPL01, CPL02

| Kode | CPMK | CPL |
|------|------|:---:|
| CPMK-1 | Mahasiswa mampu **menerapkan** (C3) proses pengumpulan, pembersihan, dan eksplorasi data | CPL06 |
| CPMK-2 | Mahasiswa mampu **menganalisis** (C4) data menggunakan teknik statistika dan machine learning | CPL06, CPL01 |
| CPMK-3 | Mahasiswa mampu **membangun dan mengevaluasi** (C6/C5) model prediktif berbasis data | CPL06 |
| CPMK-4 | Mahasiswa mampu **mengomunikasikan** (C4) wawasan data secara visual dan etis | CPL06, CPL02 |

| Kode | Sub-CPMK | CPMK |
|------|----------|:----:|
| Sub-CPMK 1.1 | Mengumpulkan dan mengintegrasikan data dari berbagai sumber | CPMK-1 |
| Sub-CPMK 1.2 | Melakukan pembersihan dan eksplorasi data (EDA) | CPMK-1 |
| Sub-CPMK 2.1 | Menerapkan teknik statistika untuk analisis data | CPMK-2 |
| Sub-CPMK 2.2 | Menerapkan algoritma machine learning yang sesuai | CPMK-2 |
| Sub-CPMK 3.1 | Membangun dan melatih model prediktif | CPMK-3 |
| Sub-CPMK 3.2 | Mengevaluasi performa model (akurasi, presisi, recall) | CPMK-3 |
| Sub-CPMK 4.1 | Memvisualisasikan hasil analisis data | CPMK-4 |
| Sub-CPMK 4.2 | Menerapkan etika data (privasi, transparansi) dalam pelaporan | CPMK-4 |

---

## 8.5 Rekapitulasi CPMK per Mata Kuliah

Tabel berikut menunjukkan jumlah CPMK dan CPL yang didukung setiap mata kuliah inti (MKW-P). RPS lengkap dengan seluruh Sub-CPMK tercantum pada BAB IX.

**Tabel 8.4 — Rekapitulasi Jumlah CPMK dan CPL per Mata Kuliah (MKW-P)**

| Kode | Mata Kuliah | Jumlah CPMK | CPL Didukung |
|------|-------------|:-----------:|--------------|
| TIN1101 | Logika Informatika | 3 | CPL01 |
| TIN1102 | Algoritma dan Pemrograman | 3 | CPL01, CPL03 |
| TIN1103 | Pengantar TI | 3 | CPL01, CPL02, CPL04 |
| TIN1104 | Komunikasi Data | 3 | CPL04 |
| TIN1105 | Aljabar Linier dan Matriks | 3 | CPL01 |
| TIN2106 | Komputer Grafis | 3 | CPL03 |
| TIN2107 | Sistem Operasi | 3 | CPL04 |
| TIN2108 | Struktur Data | 4 | CPL01, CPL03 |
| TIN2109 | Bahasa Inggris Sains | 3 | CPL02 |
| TIN2110 | Kalkulus | 3 | CPL01 |
| TIN2111 | Sistem Basis Data | 4 | CPL02, CPL03, CPL05 |
| TIN2112 | Dasar-Dasar PL | 3 | CPL01, CPL03 |
| TIN302 | Jaringan Komputer 1 | 4 | CPL04 |
| TIN303 | PBO | 3 | CPL03 |
| TIN304 | Pemrograman Web Dasar | 3 | CPL03 |
| TIN305 | Manajemen Sistem Informasi | 3 | CPL02, CPL05 |
| TIN306 | Hardware/Software | 3 | CPL01, CPL04 |
| TIN307 | Organisasi & Arsitektur Komputer | 3 | CPL01, CPL04 |
| TIN308 | Rekayasa Perangkat Lunak | 4 | CPL02, CPL03 |
| TIN4120 | Pemrograman Web Lanjut | 4 | CPL03, CPL04 |
| TIN4121 | Pengantar Kecerdasan Buatan | 3 | CPL06, CPL01, CPL02 |
| TIN4122 | Embedded Sistem | 3 | CPL04 |
| TIN4123 | Data Mining | 4 | CPL06, CPL01, CPL02 |
| TIN4124 | Sistem Informasi Kesehatan | 3 | CPL02, CPL03, CPL05 |
| TIN4125 | Statistik | 3 | CPL06, CPL01 |
| TIN4126 | Interaksi Manusia dan Komputer | 3 | CPL02, CPL03 |
| TIN5117 | Data Science | 4 | CPL06, CPL01, CPL02 |
| TIN5118 | Manajemen Informasi | 3 | CPL02, CPL05 |
| TIN5119 | Paradigma Sistem | 3 | CPL02, CPL03 |
| TIN5120 | Perancangan & Integrasi Sistem | 4 | CPL02, CPL03, CPL04 |
| TIN5121 | Metodologi Penelitian | 3 | CPL02 |
| TIN5123 | Analitik Data | 3 | CPL06, CPL01, CPL02 |
| TIN5123 | Analitik Data | 3 | CPL01, CPL02 |
| TIN6130 | Teknologi Sistem Terintegrasi | 3 | CPL03, CPL04 |
| TIN6131 | Teknologi Platform | 3 | CPL03, CPL04 |
| TIN6132 | Praktek Profesional Global | 3 | CPL02 |
| TIN6133 | Prinsip Keamanan Siber | 4 | CPL04, CPL05 |
| TIN6134 | Capstone Project 1 | 3 | CPL02, CPL03 |
| TIN7138 | Sistem Web dan Seluler | 4 | CPL03, CPL04 |
| TIN7140 | Design User Experience | 3 | CPL02, CPL03 |
| TIN7141 | Capstone Project 2 | 3 | CPL02, CPL03 |
| TIN8142 | Seminar Proposal | 2 | CPL02, CPL03 |
| TIN8143 | Seminar Hasil | 2 | CPL02, CPL03 |
| TIN8144 | Skripsi | 3 | CPL01, CPL02, CPL03 |

> *Mata kuliah pilihan (MKP) memiliki struktur CPMK serupa; rinciannya tercantum dalam RPS masing-masing (BAB IX).*

> **Catatan Cakupan:** Tabel §8.5 di atas memuat 43 mata kuliah Wajib Prodi (MKW-P). Ke-13 mata kuliah Pilihan Prodi (MKP) — seperti Kecerdasan Buatan, Sistem Basis Data Lanjut, Internet of Things, E-Health — mengikuti pola perumusan CPMK yang sama (3–4 CPMK per MK, ditelusuri ke CPL sesuai [BAB VI §6.4]) dan didokumentasikan lengkap dalam RPS masing-masing.

---

## 8.6 Matriks Kelengkapan CPL melalui CPMK

Verifikasi bahwa setiap CPL didukung oleh CPMK dari sejumlah mata kuliah dengan **kontribusi utama (●)** (dihitung dari matriks MK–CPL [BAB VI §6.4]):

**Tabel 8.5 — Verifikasi Kelengkapan Cakupan CPL melalui CPMK**

| CPL | Jumlah MK Utama (●) | Status Cakupan |
|-----|:-------------------:|:--------------:|
| CPL01 | 7 | ✅ Terpenuhi (≥3) |
| CPL02 | 14 | ✅ Terpenuhi (≥3) |
| CPL03 | 21 | ✅ Terpenuhi (≥3) |
| CPL04 | 11 | ✅ Terpenuhi (≥3) |
| CPL05 | 7 | ✅ Terpenuhi (≥3) |
| CPL06 | 7 | ✅ Terpenuhi (≥3) |

> *Angka ini identik dengan Tabel Verifikasi Matriks MK–CPL di [BAB VI §6.5], menggunakan metodologi penghitungan yang sama (kontribusi utama ● pada matriks §6.4). Setelah penambahan CPL06, mata kuliah data/AI berpindah kontribusi utama ke CPL06.*

---

*CPMK dan Sub-CPMK ini menjadi jantung setiap RPS (BAB IX). Setiap dosen pengampu wajib menyelaraskan asesmen (BAB X) dengan Sub-CPMK agar pencapaian CPL dapat diukur secara valid.*
