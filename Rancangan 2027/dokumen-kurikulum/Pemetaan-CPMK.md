# PEMETAAN CPMK — CPL — BAHAN KAJIAN — MATA KULIAH

**Dokumen Pelengkap BAB VIII (CPMK dan Sub-CPMK) — Program Studi S1 Teknologi Informasi, Universitas Muhammadiyah, Kurikulum 2027**

> Dokumen ini menyusun **Bank CPMK** yang melekat pada CPL, dan menautkannya ke mata kuliah **melalui Bahan Kajian (BK)** — mengikuti rantai:
> **CPL → memiliki → CPMK → terhubung (via BK) → beberapa Mata Kuliah**
>
> Dari bank ini, setiap mata kuliah memperoleh **menu kandidat CPMK** (berdasarkan BK yang dimilikinya, lihat *Pemetaan-Detail-Bahan-Kajian.md*). **Dosen pengampu mata kuliah yang memilih** CPMK mana dari menu tersebut yang relevan diadopsi ke RPS mata kuliahnya — bank ini bukan penetapan wajib untuk seluruh mata kuliah terhubung.

---

## 1. Kaidah Penyusunan

| Aturan | Ketentuan |
|--------|-----------|
| **CPL → CPMK** | Setiap CPMK dimiliki oleh (di-anchor ke) tepat satu CPL, mengikuti CPL Utama dari Bahan Kajian sumbernya (lihat *Pemetaan-Detail-Bahan-Kajian.md* §2). Bila satu BK memiliki lebih dari satu CPL Utama, dibuat satu CPMK per pasangan (BK, CPL Utama). |
| **CPMK → BK → Mata Kuliah** | Setiap CPMK mewarisi daftar Mata Kuliah Pengampu dari BK sumbernya. Mata kuliah tersebut dianggap "terhubung" ke CPMK itu karena secara struktural terhubung ke CPL yang sama melalui BK yang sama. |
| **Mata Kuliah → Menu CPMK** | Menu kandidat CPMK suatu mata kuliah adalah **gabungan (union)** seluruh CPMK dari semua BK yang dimiliki mata kuliah tersebut. |
| **Dosen memilih** | Dosen pengampu **memilih** CPMK mana dari menu yang relevan dan mengadopsinya ke RPS; tidak seluruh mata kuliah dalam daftar "terhubung" wajib memakai seluruh CPMK yang tersedia pada menunya. |
| **Rumusan CPMK** | Menggunakan format BAB VIII §8.2.1: *[Kata Kerja Operasional Bloom] + [Objek] + [Konteks]*, dengan level kognitif (C2–C6) disesuaikan kedalaman BK. |

> ⚠️ **Catatan kecukupan jumlah CPMK per MK:** BAB VIII §8.1 merekomendasikan 3–5 CPMK per mata kuliah. Karena menu di dokumen ini hanya berisi CPMK yang **diwariskan dari BK**, mata kuliah dengan hanya 1 BK tunggal (dan karena itu 1–2 kandidat CPMK) **kemungkinan besar tidak akan mencukupi** rentang 3–5 tersebut. Untuk kasus ini, dosen pengampu **disarankan menambahkan 1–3 CPMK spesifik mata kuliah** di luar bank ini (mengikuti contoh penurunan CPL→CPMK→Sub-CPMK pada BAB VIII §8.4), agar cakupan CPMK tetap memadai untuk keperluan asesmen (BAB X).

---

## 2. Bank CPMK per CPL

Setiap entri CPMK mencantumkan: rumusan, Bahan Kajian sumber, dan daftar Mata Kuliah yang terhubung (diwariskan dari *Pemetaan-Detail-Bahan-Kajian.md*).

### CPL01 — Pengetahuan Matematika dan Computing (6 CPMK)

| Kode | Rumusan CPMK | BK Sumber | Mata Kuliah Terhubung |
|------|--------------|:---:|------------------------|
| CPMK-CPL01-01 | Mahasiswa mampu menjelaskan (C2) dan menerapkan (C3) konsep algoritma dan struktur data dalam pemrograman terstruktur. | BK10 | TIN1102, TIN2108, TIN2112, TIN303, TIN308, TIN1103 |
| CPMK-CPL01-02 | Mahasiswa mampu menerapkan (C3) logika proposisional, teori himpunan, dan teori graf dalam pemodelan masalah komputasional. | BK14 | TIN1101, TIN2108 |
| CPMK-CPL01-03 | Mahasiswa mampu menjelaskan (C2) arsitektur CPU, hierarki memori, dan sistem I/O pada komputer modern. | BK16 | TIN306, TIN307, TIN1103 |
| CPMK-CPL01-04 | Mahasiswa mampu menghitung (C3) distribusi probabilitas dan melakukan uji hipotesis dasar. | BK19 | TIN4125, TIN6251 |
| CPMK-CPL01-05 | Mahasiswa mampu menjelaskan (C2) konsep dasar kecerdasan buatan termasuk searching, representasi pengetahuan, dan reasoning. | BK21 | TIN4121, TIN5246, TIN4123, TIN5117 |
| CPMK-CPL01-06 | Mahasiswa mampu menerapkan (C3) konsep kalkulus, aljabar linier, dan metode numerik dalam pemodelan komputasi. | BK23 | TIN1105, TIN2110, TIN6251 |

### CPL02 — Analisis Permasalahan Computing (10 CPMK)

| Kode | Rumusan CPMK | BK Sumber | Mata Kuliah Terhubung |
|------|--------------|:---:|------------------------|
| CPMK-CPL02-01 | Mahasiswa mampu berkomunikasi (C3) secara profesional dan etis dalam kerja tim lintas budaya sesuai standar industri global. | BK08 | TIN6132, INS1106, TIN2109, TIN7260, TIN7261 |
| CPMK-CPL02-02 | Mahasiswa mampu menganalisis (C4) kebutuhan data suatu organisasi dan merumuskan strategi pengelolaan informasi. | BK09 | TIN2111, TIN5245, TIN5118, TIN4124, TIN7257 |
| CPMK-CPL02-03 | Mahasiswa mampu merencanakan (C5) proyek TI menggunakan metodologi Agile/Scrum/Waterfall termasuk estimasi dan manajemen risiko. | BK13 | INS2105, TIN308, TIN6134, TIN7141, TIN6250, TIN7260 |
| CPMK-CPL02-04 | Mahasiswa mampu menganalisis (C4) kebutuhan sistem dan memodelkannya menggunakan notasi UML/pemodelan proses. | BK17 | TIN5119, TIN5120 |
| CPMK-CPL02-05 | Mahasiswa mampu merumuskan (C5) strategi sistem informasi yang selaras dengan tujuan organisasi. | BK18 | TIN305, TIN5118 |
| CPMK-CPL02-06 | Mahasiswa mampu menganalisis (C4) permasalahan bisnis berbasis big data dan merumuskan solusi berbasis data. | BK22 | TIN4123, TIN5117, TIN5123, TIN6250 |
| CPMK-CPL02-07 | Mahasiswa mampu merancang (C6) metodologi penelitian bidang TI termasuk perumusan masalah dan analisis data. | BK24 | TIN5121, TIN8142 |
| CPMK-CPL02-08 | Mahasiswa mampu menyusun (C6) proposal dan laporan penelitian/proyek tugas akhir secara sistematis. | BK27 | TIN6134, TIN7141, TIN8143, TIN8144, TIN8142 |
| CPMK-CPL02-09 | Mahasiswa mampu menunjukkan (A3, ranah afektif) sikap kebangsaan, nasionalisme, dan tanggung jawab sebagai warga negara dalam kehidupan akademik dan profesional. | BK28 | NAS1101, NAS1102, NAS2103 |
| CPMK-CPL02-10 | Mahasiswa mampu menginternalisasi (A4, ranah afektif) nilai-nilai Al-Islam dan Kemuhammadiyahan dalam kehidupan akademik dan pengembangan profesi TI. | BK29 | INS1101, INS2102, INS301, INS4104 |

### CPL03 — Perancangan dan Evaluasi Solusi (10 CPMK)

| Kode | Rumusan CPMK | BK Sumber | Mata Kuliah Terhubung |
|------|--------------|:---:|------------------------|
| CPMK-CPL03-01 | Mahasiswa mampu merancang (C6) integrasi sistem heterogen menggunakan middleware, API, dan pola arsitektur SOA/microservices. | BK04 | TIN6130, TIN5120 |
| CPMK-CPL03-02 | Mahasiswa mampu merancang (C6) solusi berbasis platform cloud/mobile menggunakan model PaaS/SaaS. | BK05 | TIN6131, TIN4120, TIN6253, TIN7138 |
| CPMK-CPL03-03 | Mahasiswa mampu mengembangkan (C6) aplikasi web dan mobile lintas-platform yang responsif dan dapat diakses lintas perangkat. | BK06 | TIN304, TIN4120, TIN6253, TIN7138 |
| CPMK-CPL03-04 | Mahasiswa mampu merancang (C6) perangkat lunak menggunakan paradigma pemrograman dan prinsip rekayasa perangkat lunak yang tepat. | BK10 | TIN1102, TIN2108, TIN2112, TIN303, TIN308, TIN1103 |
| CPMK-CPL03-05 | Mahasiswa mampu merancang (C6) antarmuka dan pengalaman pengguna yang usable dan aksesibel berdasarkan riset pengguna. | BK11 | TIN4126, TIN7140 |
| CPMK-CPL03-06 | Mahasiswa mampu mengelola (C3) eksekusi proyek pengembangan solusi TI dari perancangan hingga penyerahan. | BK13 | INS2105, TIN308, TIN6134, TIN7141, TIN6250, TIN7260 |
| CPMK-CPL03-07 | Mahasiswa mampu merancang (C6) arsitektur sistem berdasarkan hasil analisis kebutuhan. | BK17 | TIN5119, TIN5120 |
| CPMK-CPL03-08 | Mahasiswa mampu mengembangkan (C6) aplikasi grafika komputer dan multimedia interaktif. | BK20 | TIN2106, TIN5247 |
| CPMK-CPL03-09 | Mahasiswa mampu merancang (C6) sistem informasi kesehatan yang interoperable menggunakan standar HL7/FHIR. | BK25 | TIN4124, TIN5249, TIN7257 |
| CPMK-CPL03-10 | Mahasiswa mampu merancang (C6), mengimplementasikan, dan mengevaluasi solusi TI dalam proyek capstone/skripsi. | BK27 | TIN6134, TIN7141, TIN8143, TIN8144, TIN8142 |

### CPL04 — Integrasi dan Administrasi Infrastruktur TI (9 CPMK)

| Kode | Rumusan CPMK | BK Sumber | Mata Kuliah Terhubung |
|------|--------------|:---:|------------------------|
| CPMK-CPL04-01 | Mahasiswa mampu mengimplementasikan (C3) virtualisasi server, jaringan, dan layanan cloud untuk mendukung infrastruktur TI organisasi. | BK01 | TIN6254, TIN6131, TIN2107 |
| CPMK-CPL04-02 | Mahasiswa mampu merancang (C6) arsitektur sistem IoT yang mengintegrasikan sensor, aktuator, dan protokol komunikasi untuk aplikasi tertanam. | BK02 | TIN6252, TIN4122 |
| CPMK-CPL04-03 | Mahasiswa mampu mengkonfigurasi (C3) dan mengelola (C3) jaringan komputer kabel dan nirkabel menggunakan protokol TCP/IP, routing, dan switching. | BK03 | TIN302, TIN5248 |
| CPMK-CPL04-04 | Mahasiswa mampu mengimplementasikan (C3) infrastruktur integrasi sistem lintas platform yang andal dan skalabel. | BK04 | TIN6130, TIN5120 |
| CPMK-CPL04-05 | Mahasiswa mampu mengelola (C3) deployment aplikasi pada platform komputasi awan dan kontainer. | BK05 | TIN6131, TIN4120, TIN6253, TIN7138 |
| CPMK-CPL04-06 | Mahasiswa mampu mengembangkan (C6) firmware dan antarmuka hardware-software untuk sistem tertanam. | BK12 | TIN4122, TIN6252, TIN306 |
| CPMK-CPL04-07 | Mahasiswa mampu menganalisis (C4) mekanisme manajemen proses, memori, dan berkas pada sistem operasi modern. | BK15 | TIN2107, TIN307 |
| CPMK-CPL04-08 | Mahasiswa mampu mengkonfigurasi (C3) dan melakukan troubleshooting perangkat keras dan interaksinya dengan perangkat lunak. | BK16 | TIN306, TIN307, TIN1103 |
| CPMK-CPL04-09 | Mahasiswa mampu menjelaskan (C2) prinsip transmisi data, modulasi, dan protokol komunikasi dasar. | BK26 | TIN1104, TIN302 |

### CPL05 — Keamanan dan Manajemen Sistem Informasi (4 CPMK)

| Kode | Rumusan CPMK | BK Sumber | Mata Kuliah Terhubung |
|------|--------------|:---:|------------------------|
| CPMK-CPL05-01 | Mahasiswa mampu menerapkan (C3) prinsip kriptografi dan keamanan jaringan untuk melindungi sistem dari ancaman siber. | BK07 | TIN6133, TIN6254 |
| CPMK-CPL05-02 | Mahasiswa mampu mengelola (C3) keamanan dan integritas basis data serta tata kelola informasi organisasi. | BK09 | TIN2111, TIN5245, TIN5118, TIN4124, TIN7257 |
| CPMK-CPL05-03 | Mahasiswa mampu menerapkan (C3) tata kelola TI (IT governance) berdasarkan kerangka kerja seperti ITIL. | BK18 | TIN305, TIN5118 |
| CPMK-CPL05-04 | Mahasiswa mampu menerapkan (C3) prinsip keamanan dan privasi data kesehatan dalam sistem informasi medis. | BK25 | TIN4124, TIN5249, TIN7257 |

### CPL06 — Analitik Data dan Kecerdasan Buatan (3 CPMK)

| Kode | Rumusan CPMK | BK Sumber | Mata Kuliah Terhubung |
|------|--------------|:---:|------------------------|
| CPMK-CPL06-01 | Mahasiswa mampu menerapkan (C3) teknik statistika deskriptif dan inferensial untuk analisis data. | BK19 | TIN4125, TIN6251 |
| CPMK-CPL06-02 | Mahasiswa mampu membangun (C6) model machine learning/deep learning untuk menyelesaikan masalah kecerdasan buatan. | BK21 | TIN4121, TIN5246, TIN4123, TIN5117 |
| CPMK-CPL06-03 | Mahasiswa mampu menerapkan (C3) teknik data mining dan analitik data untuk menghasilkan wawasan bisnis. | BK22 | TIN4123, TIN5117, TIN5123, TIN6250 |

**Total: 42 CPMK** (CPL01: 6, CPL02: 10, CPL03: 10, CPL04: 9, CPL05: 4, CPL06: 3).

---

## 3. Menu Kandidat CPMK per Mata Kuliah (Untuk Dipilih Dosen Pengampu)

Kolom "BK" mengacu ke Bahan Kajian mata kuliah (dari *Pemetaan-Detail-Bahan-Kajian.md* §4). Kolom "Kandidat CPMK" adalah gabungan CPMK dari seluruh BK tersebut — **dosen pengampu memilih** subset yang relevan (dan dapat menambah CPMK spesifik MK bila kandidat < 3, lihat catatan §1).

| Sem | Kode | Mata Kuliah | BK | Kandidat CPMK (pilih sesuai relevansi RPS) | Jml |
|:---:|------|-------------|----|---------------------------------------------|:---:|
| 1 | INS1101 | AIK I | BK29 | CPMK-CPL02-10 | 1 |
| 1 | INS1106 | Bahasa Inggris | BK08 | CPMK-CPL02-01 | 1 |
| 1 | NAS1101 | Pancasila | BK28 | CPMK-CPL02-09 | 1 |
| 1 | NAS1102 | Bahasa Indonesia | BK28 | CPMK-CPL02-09 | 1 |
| 1 | TIN1101 | Logika Informatika | BK14 | CPMK-CPL01-02 | 1 |
| 1 | TIN1102 | Algoritma dan Pemrograman | BK10 | CPMK-CPL01-01, CPMK-CPL03-04 | 2 |
| 1 | TIN1103 | Pengantar Teknologi Informasi | BK10, BK16 | CPMK-CPL01-01, CPMK-CPL03-04, CPMK-CPL01-03, CPMK-CPL04-08 | 4 |
| 1 | TIN1104 | Komunikasi Data | BK26 | CPMK-CPL04-09 | 1 |
| 1 | TIN1105 | Aljabar Linier dan Matriks | BK23 | CPMK-CPL01-06 | 1 |
| 2 | INS2102 | AIK II | BK29 | CPMK-CPL02-10 | 1 |
| 2 | INS2105 | Kewirausahaan | BK13 | CPMK-CPL02-03, CPMK-CPL03-06 | 2 |
| 2 | NAS2103 | Kewarganegaraan | BK28 | CPMK-CPL02-09 | 1 |
| 2 | TIN2106 | Komputer Grafis | BK20 | CPMK-CPL03-08 | 1 |
| 2 | TIN2107 | Sistem Operasi | BK15, BK01 | CPMK-CPL04-07, CPMK-CPL04-01 | 2 |
| 2 | TIN2108 | Struktur Data | BK10, BK14 | CPMK-CPL01-01, CPMK-CPL03-04, CPMK-CPL01-02 | 3 |
| 2 | TIN2109 | Bahasa Inggris Sains | BK08 | CPMK-CPL02-01 | 1 |
| 2 | TIN2110 | Kalkulus | BK23 | CPMK-CPL01-06 | 1 |
| 2 | TIN2111 | Sistem Basis Data | BK09 | CPMK-CPL05-02, CPMK-CPL02-02 | 2 |
| 2 | TIN2112 | Dasar-Dasar Perangkat Lunak | BK10 | CPMK-CPL01-01, CPMK-CPL03-04 | 2 |
| 3 | INS301 | Kemuhammadiyahan dan Ke'Aisyiyahan | BK29 | CPMK-CPL02-10 | 1 |
| 3 | TIN302 | Jaringan Komputer 1 | BK03, BK26 | CPMK-CPL04-03, CPMK-CPL04-09 | 2 |
| 3 | TIN303 | Pemrograman Berorientasi Objek | BK10 | CPMK-CPL01-01, CPMK-CPL03-04 | 2 |
| 3 | TIN304 | Pemrograman Web Dasar | BK06 | CPMK-CPL03-03 | 1 |
| 3 | TIN305 | Manajemen Sistem Informasi | BK18 | CPMK-CPL02-05, CPMK-CPL05-03 | 2 |
| 3 | TIN306 | Hardware/Software | BK16, BK12 | CPMK-CPL01-03, CPMK-CPL04-08, CPMK-CPL04-06 | 3 |
| 3 | TIN307 | Organisasi dan Arsitektur Komputer | BK16, BK15 | CPMK-CPL01-03, CPMK-CPL04-08, CPMK-CPL04-07 | 3 |
| 3 | TIN308 | Rekayasa Perangkat Lunak | BK10, BK13 | CPMK-CPL01-01, CPMK-CPL03-04, CPMK-CPL02-03, CPMK-CPL03-06 | 4 |
| 4 | INS4104 | AIK IV | BK29 | CPMK-CPL02-10 | 1 |
| 4 | TIN4120 | Pemrograman Web Lanjut | BK06, BK05 | CPMK-CPL03-03, CPMK-CPL03-02, CPMK-CPL04-05 | 3 |
| 4 | TIN4121 | Pengantar Kecerdasan Buatan | BK21 | CPMK-CPL06-02, CPMK-CPL01-05 | 2 |
| 4 | TIN4122 | Embedded Sistem | BK12, BK02 | CPMK-CPL04-06, CPMK-CPL04-02 | 2 |
| 4 | TIN4123 | Data Mining | BK22, BK21 | CPMK-CPL06-03, CPMK-CPL02-06, CPMK-CPL06-02, CPMK-CPL01-05 | 4 |
| 4 | TIN4124 | Sistem Informasi Kesehatan | BK25, BK09 | CPMK-CPL03-09, CPMK-CPL05-04, CPMK-CPL05-02, CPMK-CPL02-02 | 4 |
| 4 | TIN4125 | Statistik | BK19 | CPMK-CPL06-01, CPMK-CPL01-04 | 2 |
| 4 | TIN4126 | Interaksi Manusia dan Komputer | BK11 | CPMK-CPL03-05 | 1 |
| 5 | TIN5117 | Data Science | BK22, BK21 | CPMK-CPL06-03, CPMK-CPL02-06, CPMK-CPL06-02, CPMK-CPL01-05 | 4 |
| 5 | TIN5118 | Manajemen Informasi | BK09, BK18 | CPMK-CPL05-02, CPMK-CPL02-02, CPMK-CPL02-05, CPMK-CPL05-03 | 4 |
| 5 | TIN5119 | Paradigma Sistem | BK17 | CPMK-CPL02-04, CPMK-CPL03-07 | 2 |
| 5 | TIN5120 | Perancangan dan Integrasi Sistem | BK04, BK17 | CPMK-CPL03-01, CPMK-CPL04-04, CPMK-CPL02-04, CPMK-CPL03-07 | 4 |
| 5 | TIN5121 | Metodologi Penelitian | BK24 | CPMK-CPL02-07 | 1 |
| 5 | TIN5123 | Analitik Data | BK22 | CPMK-CPL06-03, CPMK-CPL02-06 | 2 |
| 5 | TIN5245 | Sistem Basis Data Lanjut *(Pil)* | BK09 | CPMK-CPL05-02, CPMK-CPL02-02 | 2 |
| 5 | TIN5246 | Kecerdasan Buatan *(Pil)* | BK21 | CPMK-CPL06-02, CPMK-CPL01-05 | 2 |
| 5 | TIN5247 | Multimedia *(Pil)* | BK20 | CPMK-CPL03-08 | 1 |
| 5 | TIN5248 | Jaringan Komputer 2 *(Pil)* | BK03 | CPMK-CPL04-03 | 1 |
| 5 | TIN5249 | Informatika Medis *(Pil)* | BK25 | CPMK-CPL03-09, CPMK-CPL05-04 | 2 |
| 6 | TIN6130 | Teknologi Sistem Terintegrasi | BK04 | CPMK-CPL03-01, CPMK-CPL04-04 | 2 |
| 6 | TIN6131 | Teknologi Platform | BK05, BK01 | CPMK-CPL03-02, CPMK-CPL04-05, CPMK-CPL04-01 | 3 |
| 6 | TIN6132 | Praktek Profesional Global | BK08 | CPMK-CPL02-01 | 1 |
| 6 | TIN6133 | Prinsip Keamanan Siber | BK07 | CPMK-CPL05-01 | 1 |
| 6 | TIN6134 | Capstone Project 1 | BK27, BK13 | CPMK-CPL02-08, CPMK-CPL03-10, CPMK-CPL02-03, CPMK-CPL03-06 | 4 |
| 6 | TIN6250 | Business Problem & DS Solution *(Pil)* | BK22, BK13 | CPMK-CPL06-03, CPMK-CPL02-06, CPMK-CPL02-03, CPMK-CPL03-06 | 4 |
| 6 | TIN6251 | Riset Operasi *(Pil)* | BK19, BK23 | CPMK-CPL06-01, CPMK-CPL01-04, CPMK-CPL01-06 | 3 |
| 6 | TIN6252 | Internet of Things *(Pil)* | BK02, BK12 | CPMK-CPL04-02, CPMK-CPL04-06 | 2 |
| 6 | TIN6254 | Sistem dan Layanan Virtual *(Pil)* | BK01, BK07 | CPMK-CPL04-01, CPMK-CPL05-01 | 2 |
| 7 | TIN6253 | Aplikasi Seluler *(Pil)* | BK06, BK05 | CPMK-CPL03-03, CPMK-CPL03-02, CPMK-CPL04-05 | 3 |
| 7 | TIN7138 | Sistem Web dan Seluler | BK06, BK05 | CPMK-CPL03-03, CPMK-CPL03-02, CPMK-CPL04-05 | 3 |
| 7 | TIN7140 | Design User Experience | BK11 | CPMK-CPL03-05 | 1 |
| 7 | TIN7141 | Capstone Project 2 | BK27, BK13 | CPMK-CPL02-08, CPMK-CPL03-10, CPMK-CPL02-03, CPMK-CPL03-06 | 4 |
| 7 | TIN7257 | E-Health *(Pil)* | BK25, BK09 | CPMK-CPL03-09, CPMK-CPL05-04, CPMK-CPL05-02, CPMK-CPL02-02 | 4 |
| 7 | TIN7260 | Magang/Praktik Kerja *(MBKM)* | BK08, BK13 | CPMK-CPL02-01, CPMK-CPL02-03, CPMK-CPL03-06 | 3 |
| 7 | TIN7261 | Kuliah Kerja Nyata *(MBKM)* | BK08 | CPMK-CPL02-01 | 1 |
| 7 | TIN8142 | Seminar Proposal | BK24, BK27 | CPMK-CPL02-07, CPMK-CPL02-08, CPMK-CPL03-10 | 3 |
| 8 | TIN8143 | Seminar Hasil | BK27 | CPMK-CPL02-08, CPMK-CPL03-10 | 2 |
| 8 | TIN8144 | Skripsi | BK27 | CPMK-CPL02-08, CPMK-CPL03-10 | 2 |

---

## 4. Verifikasi

- **CPL → CPMK:** Seluruh 6 CPL memiliki CPMK (CPL01: 6, CPL02: 10, CPL03: 10, CPL04: 9, CPL05: 4, CPL06: 3 — total 42 CPMK). ✅
- **CPMK → Mata Kuliah:** Seluruh 42 CPMK terhubung ke minimal 2 mata kuliah (mewarisi daftar MK dari BK sumbernya sesuai *Pemetaan-Detail-Bahan-Kajian.md*). ✅
- **Mata Kuliah → Menu CPMK:** Seluruh 65 mata kuliah memiliki menu kandidat CPMK tidak kosong (minimum 1 kandidat). ✅
- **Mata kuliah dengan kandidat < 3** (44 dari 65 MK — umumnya MK dengan 1 BK tunggal, termasuk seluruh MK Wajib Nasional/Institusi serta banyak MK Prodi/Pilihan yang bersifat spesialis-tunggal): direkomendasikan dosen pengampu menambahkan CPMK spesifik MK agar total mencapai 3–5 CPMK sesuai BAB VIII §8.1. Ini menegaskan bahwa bank CPMK berbasis BK ini adalah **titik awal (starting set)**, bukan daftar CPMK final per mata kuliah.

---

## 5. Catatan Penting untuk Validasi Prodi

1. **Pendekatan "bank CPMK via BK" ini melengkapi**, bukan menggantikan, contoh penurunan CPL→CPMK→Sub-CPMK yang sudah ditulis lengkap per-MK di BAB VIII §8.4 (mis. TIN1102, TIN2111) — dokumen ini menyediakan kerangka *shared CPMK* lintas mata kuliah sejenis, sedangkan BAB VIII §8.4 tetap menjadi rujukan format Sub-CPMK per mata kuliah.
2. **Rumusan CPMK** pada bank ini bersifat generik-representatif per BK; dosen pengampu **wajib menyesuaikan konteks** (KKO, objek, tingkat kedalaman) dengan karakteristik mata kuliahnya saat menuliskannya ke RPS — bukan disalin literal.
3. **CPMK dengan tag afektif (A3/A4)** pada BK28/BK29 mengikuti sifat MK Wajib Umum/AIK yang menilai sikap, bukan capaian kognitif teknis — penilaiannya mengacu ke Rubrik Afektif BAB X §10.3.3, bukan rubrik kognitif/analitik.
4. **Kandidat CPMK yang tumpang-tindih antar-MK** (mis. CPMK-CPL03-04 muncul di 6 MK BK10) adalah wajar karena BK10 memang materi inti yang tersebar di banyak mata kuliah — dosen tiap MK tetap memilih Sub-CPMK yang berbeda kedalamannya sesuai posisi MK dalam alur (lihat BAB VI §6.6 Diagram Alur Prasyarat).
5. Dokumen ini berstatus **draf untuk validasi Tim Kurikulum**, khususnya untuk memastikan rumusan CPMK selaras dengan ekspektasi dosen pengampu masing-masing mata kuliah sebelum diintegrasikan ke RPS (BAB IX).

---

*Dokumen ini disusun sebagai pelengkap BAB VIII — CPMK dan Sub-CPMK, serta Pemetaan-Detail-Bahan-Kajian.md, Dokumen Kurikulum OBE Program Studi S1 Teknologi Informasi 2027, Universitas Muhammadiyah.*
