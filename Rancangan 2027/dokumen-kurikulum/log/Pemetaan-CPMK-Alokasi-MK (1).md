# PEMETAAN ALOKASI CPMK KE MATA KULIAH

**Dokumen Pelengkap Pemetaan-CPMK.md dan BAB VIII (CPMK) — Program Studi S1 Teknologi Informasi, Institut Sains Teknologi dan Kesehatan Aisyiyah Kendari, Kurikulum 2027**

> Dokumen ini menjawab kebutuhan alokasi CPMK ke mata kuliah secara eksplisit dan terkontrol, melengkapi **Pemetaan-CPMK.md** (yang berhenti pada tingkat "MK Utama" tanpa batasan kuantitatif) dan **Pemetaan-Detail-Bahan-Kajian.md** (BK → CPL → MK). Alokasi dihitung terprogram (Python) agar konsisten dan dapat diverifikasi ulang.
>
> **[REVISI]** Setelah analisis lanjutan terhadap 22 MK berbobot 4 SKS, ditemukan bahwa beberapa MK hanya memanfaatkan 1 dari ≥2 CPL yang secara sah menjadi haknya (via BK) — padahal cakupan materinya secara pedagogis jelas melibatkan lebih dari satu CPL. **9 MK diperkuat dengan 1 CPMK tambahan** (ditandai `*` pada §4, `` `+` `` pada §3) tanpa mengubah alokasi yang sudah ada. Lihat §2.2 untuk kriteria dan daftar lengkap.

---

## 1. Konsep dan Rantai Keterlacakan

```
CPL (8 CPL Prodi)
 ↓ didekomposisi menjadi (lihat Pemetaan-CPMK.md §2)
CPMK (26 CPMK)
 ↓ dialokasikan ke
Mata Kuliah (65 MK) — HANYA MK yang memiliki BK yang terhubung ke CPL induk CPMK tersebut
```

CPMK **tidak boleh dialokasikan ke MK yang berada di luar CPL induknya**. Batasan ini ditegakkan melalui rantai **CPL → Bahan Kajian (BK) → Mata Kuliah** dari `Pemetaan-Detail-Bahan-Kajian.md`: sebuah MK hanya boleh menerima CPMK dari CPL X jika MK tersebut memiliki minimal satu BK yang terhubung ke CPL X (baik sebagai CPL utama maupun pendukung BK itu).

---

## 2. Aturan Alokasi

| Aturan | Ketentuan |
|--------|-----------|
| **CPMK → MK (minimum)** | Setiap CPMK dialokasikan ke **lebih dari 3 mata kuliah** (≥4 MK), diambil dari kumpulan MK yang sah menurut CPL induknya (via BK). |
| **MK → CPMK (maksimum)** | Jumlah CPMK yang boleh diampu satu MK **dibatasi oleh bobot SKS**-nya: MK 1 SKS → maks. 1 CPMK; MK 2 SKS → maks. 2 CPMK; MK 4 SKS → maks. 4 CPMK. Tidak boleh melebihi angka SKS. |
| **Batas CPL** | CPMK tidak boleh ditugaskan ke MK yang tidak memiliki keterhubungan CPL (via BK) dengan CPL induk CPMK tersebut. |
| **Cakupan MK** | **Seluruh 65 mata kuliah wajib memiliki minimal 1 CPMK** — tidak ada MK yang kosong. |

### 2.1 Pengecualian yang Didokumentasikan (CPL07 dan CPL08)

Dua CPL memiliki kolam MK yang sangat sempit karena hanya terhubung ke satu Bahan Kajian tunggal (BK29 untuk CPL07, BK28 untuk CPL08):

- **CPL07 (Sikap Keislaman)** hanya terhubung ke **4 MK** (AIK I, AIK II, Kemuhammadiyahan, AIK IV) — pas memenuhi syarat "≥4 MK" karena seluruh kolamnya digunakan.
- **CPL08 (Sikap Kebangsaan)** hanya terhubung ke **3 MK** (Pancasila, Bahasa Indonesia, Kewarganegaraan) — **secara struktural tidak dapat mencapai 4 MK** karena memang hanya ada 3 mata kuliah Wajib Nasional dalam kurikulum ini yang terhubung ke BK28. CPMK081–083 dialokasikan ke ketiga MK tersebut (maksimum yang tersedia), dan ini didokumentasikan sebagai **penyimpangan yang disengaja**, bukan kesalahan alokasi.

Konsekuensi kedua: ke-4 MK AIK (2 SKS) dan ke-3 MK Wajib Nasional (2 SKS) masing-masing harus menampung **3 CPMK sekaligus** (CPMK071–073 atau CPMK081–083) — melebihi batas normal "2 SKS → maks. 2 CPMK". Ini juga merupakan **penyimpangan terdokumentasi**: seluruh materi mata kuliah tersebut memang secara utuh membangun satu kompetensi sikap (CPL07/CPL08) yang telah dipecah menjadi 3 klausa kata kerja SMART, bukan tiga kompetensi berbeda yang bersaing dalam SKS — berbeda dari MK teknis yang mengampu CPMK dari CPL yang berbeda-beda. Ketujuh MK ini ditandai **`**`** pada tabel §4.

### 2.2 [REVISI] Analisis Penguatan CPMK pada MK 4 SKS yang Masih di Bawah Kapasitas

Seluruh 22 MK berbobot 4 SKS awalnya hanya memperoleh 1–2 CPMK dari maksimum 4 (lihat riwayat pada §5). Angka ini **tidak salah** — CPMK per MK memang tidak wajib memenuhi plafon SKS-nya (lihat pembahasan umum: jumlah CPMK yang wajar per MK adalah soal kedalaman asesmen, bukan mengejar plafon). Namun analisis lebih lanjut terhadap **cakupan CPL yang sah dimiliki tiap MK** (via BK, kolom "CPL_elig" pada verifikasi internal) menemukan bahwa 9 dari 22 MK tersebut memiliki **cakupan CPL yang jauh lebih luas dari yang tercermin pada CPMK-nya** — MK itu berhak (dan secara substansi materi juga cocok) atas CPMK dari CPL lain yang selama ini belum terwakili sama sekali.

**Kriteria penambahan:** CPMK baru hanya ditambahkan jika (a) MK tersebut secara sah eligible pada CPL asal CPMK itu (via rantai BK, tidak melanggar §1), (b) penambahan tidak melebihi batas SKS (§2), dan (c) ada kesesuaian substansi nyata antara isi CPMK dan materi MK — bukan sekadar mengisi slot kosong.

| MK | CPMK Ditambahkan | Alasan |
|----|-------------------|--------|
| **TIN1102** Algoritma dan Pemrograman | + CPMK032 (Mengimplementasikan solusi) | MK ini mengajarkan mahasiswa menulis program nyata — implementasi (CPL03) sama sentralnya dengan fondasi logika/algoritma (CPL01) yang sudah tercatat |
| **TIN2108** Struktur Data | + CPMK032 (Mengimplementasikan solusi) | Struktur data dipelajari dengan mengimplementasikannya dalam program, bukan sekadar dikuasai konsepnya |
| **TIN302** Jaringan Komputer 1 | + CPMK041 (Mengintegrasikan infrastruktur) | Sebelumnya hanya tercatat pada CPL05 (keamanan/tata kelola); padahal MK ini secara inti adalah integrasi infrastruktur jaringan (CPL04) |
| **TIN5248** Jaringan Komputer 2 | + CPMK041 (Mengintegrasikan infrastruktur) | Sama seperti Jaringan Komputer 1 — integrasi infrastruktur (CPL04) semestinya eksplisit pada MK lanjutannya |
| **TIN6252** Internet of Things | + CPMK032 (Mengimplementasikan solusi) | Sebelumnya hanya 1 CPMK (25% kapasitas); pengembangan solusi IoT menuntut implementasi (CPL03), tidak hanya integrasi infrastruktur (CPL04) |
| **TIN6253** Aplikasi Seluler | + CPMK032 (Mengimplementasikan solusi) | Sebelumnya hanya 1 CPMK; pengembangan aplikasi mobile secara inti adalah implementasi solusi computing (CPL03) |
| **TIN7138** Sistem Web dan Seluler | + CPMK032 (Mengimplementasikan solusi) | Sebelumnya hanya 1 CPMK; sama seperti Aplikasi Seluler, inti MK ini adalah implementasi (CPL03), bukan hanya konfigurasi (CPL04) |
| **TIN7260** Magang/Praktik Kerja | + CPMK032 (Mengimplementasikan solusi) | Praktik kerja nyata mencerminkan implementasi solusi computing (CPL03), melengkapi analisis (CPL02) dan konfigurasi (CPL04) yang sudah ada |
| **TIN8144** Skripsi | + CPMK033 (Mengevaluasi solusi) | Sebagai karya integratif puncak, skripsi semestinya juga mencakup evaluasi solusi/temuan (CPL03), melengkapi fondasi (CPL01) dan analisis masalah (CPL02) |

MK 4 SKS lain **sengaja tidak ditambah** karena CPL yang tersisa dari kolamnya bersifat pendukung tidak langsung terhadap materi inti MK (misalnya menambahkan CPL01 "menguasai konsep matematika" ke Data Science/Kecerdasan Buatan/Riset Operasi dinilai kurang tepat karena kompetensi matematika dasar itu sudah dibebankan pada MK Kalkulus/Aljabar Linier tersendiri), atau karena kolam CPL-nya memang sudah terwakili penuh (Pemrograman Web Dasar, Pemrograman Web Lanjut, Multimedia).

---

## 3. Pemetaan CPL → CPMK → Mata Kuliah

### CPL01 — Pengetahuan Matematika dan Computing

| CPMK | Deskripsi Singkat | Jml MK | Mata Kuliah Pengampu (kode, semester, SKS) |
|------|--------------------|:---:|---------------------------------------------|
| **CPMK011** | Menguasai konsep matematika (aljabar linier, kalkulus, matematika terapan) yang relevan untuk komputasi | 4 | Algoritma dan Pemrograman (TIN1102, sem 1, 4 SKS); Struktur Data (TIN2108, sem 2, 4 SKS); Pemrograman Berorientasi Objek (PBO) (TIN303, sem 3, 4 SKS); Skripsi (TIN8144, sem 8, 4 SKS) |
| **CPMK012** | Menguasai konsep dasar sains komputasi meliputi logika, algoritma, dan struktur data | 4 | Logika Informatika (TIN1101, sem 1, 2 SKS); Dasar Dasar Perangkat Lunak (TIN2112, sem 2, 2 SKS); Organisasi & Arsitektur Komputer (TIN307, sem 3, 2 SKS); Rekayasa Perangkat Lunak (RPL) (TIN308, sem 3, 2 SKS) |
| **CPMK013** | Menguasai fondasi teknologi informasi meliputi arsitektur sistem dan perangkat keras/lunak | 4 | Embedded Sistem (TIN4122, sem 4, 2 SKS); Analitik Data (TIN5123, sem 5, 2 SKS); Capstone Project 1 (TIN6134, sem 6, 2 SKS); Capstone Project 2 (TIN7141, sem 7, 2 SKS) |
| **CPMK014** | Menganalisis dan memecahkan permasalahan computing kompleks menggunakan pengetahuan matematika, sains komputasi, dan fondasi TI | 4 | Algoritma dan Pemrograman (TIN1102, sem 1, 4 SKS); Struktur Data (TIN2108, sem 2, 4 SKS); Seminar Proposal (TIN8142, sem 7, 1 SKS); Seminar Hasil (TIN8143, sem 8, 1 SKS) |

> Total 4 CPMK untuk CPL01.

### CPL02 — Analisis Permasalahan Computing

| CPMK | Deskripsi Singkat | Jml MK | Mata Kuliah Pengampu (kode, semester, SKS) |
|------|--------------------|:---:|---------------------------------------------|
| **CPMK021** | Mengidentifikasi permasalahan computing yang kompleks | 4 | Data Mining (TIN4123, sem 4, 4 SKS); Data Science (TIN5117, sem 5, 4 SKS); Kecerdasan Buatan (TIN5246, sem 5, 4 SKS); Business Problem & DS Solution (TIN6250, sem 6, 4 SKS) |
| **CPMK022** | Menganalisis permasalahan computing kompleks menggunakan prinsip ilmu komputer dan teknologi informasi | 4 | Riset Operasi (TIN6251, sem 6, 4 SKS); E-Health (TIN7257, sem 7, 4 SKS); Magang/Praktik Kerja (TIN7260, sem 7, 4 SKS); Kuliah Kerja Nyata (KKN) (TIN7261, sem 7, 4 SKS) |
| **CPMK023** | Mendefinisikan permasalahan computing kompleks berdasarkan pengetahuan domain yang relevan | 4 | Bahasa Inggris (INS1106, sem 1, 2 SKS); Kewirausahaan (INS2105, sem 2, 2 SKS); Pengantar Teknologi Informasi (TIN1103, sem 1, 2 SKS); Skripsi (TIN8144, sem 8, 4 SKS) |

> Total 3 CPMK untuk CPL02.

### CPL03 — Perancangan dan Evaluasi Solusi

| CPMK | Deskripsi Singkat | Jml MK | Mata Kuliah Pengampu (kode, semester, SKS) |
|------|--------------------|:---:|---------------------------------------------|
| **CPMK031** | Merancang solusi berbasis computing yang memenuhi kebutuhan tertentu | 4 | Kewirausahaan (INS2105, sem 2, 2 SKS); Interaksi Manusia dan Komputer (TIN4126, sem 4, 2 SKS); Paradigma Sistem (TIN5119, sem 5, 2 SKS); Perancangan dan Integrasi Sistem (TIN5120, sem 5, 2 SKS) |
| **CPMK032** | Mengimplementasikan solusi berbasis computing | 10 | Algoritma dan Pemrograman (TIN1102, sem 1, 4 SKS) `+`; Struktur Data (TIN2108, sem 2, 4 SKS) `+`; Metodologi Penelitian (TIN5121, sem 5, 2 SKS); Teknologi Sistem Terintegrasi (TIN6130, sem 6, 2 SKS); Praktek Professional Global (TIN6132, sem 6, 2 SKS); Internet of Things (TIN6252, sem 6, 4 SKS) `+`; Aplikasi Seluler(Mobile) (TIN6253, sem 7, 4 SKS) `+`; Sistem Web dan Seluler (Mobile) (TIN7138, sem 7, 4 SKS) `+`; Design User Experience (TIN7140, sem 7, 2 SKS); Magang/Praktik Kerja (TIN7260, sem 7, 4 SKS) `+` |
| **CPMK033** | Mengevaluasi solusi berbasis computing dari aspek keandalan, keamanan, dan efisiensi | 5 | Pemrograman Berorientasi Objek (PBO) (TIN303, sem 3, 4 SKS); Pemrograman Web Dasar (TIN304, sem 3, 4 SKS); Pemrograman Web Lanjut (TIN4120, sem 4, 4 SKS); Multimedia (TIN5247, sem 5, 4 SKS); Skripsi (TIN8144, sem 8, 4 SKS) `+` |

> Total 3 CPMK untuk CPL03.

### CPL04 — Integrasi dan Administrasi Infrastruktur TI

| CPMK | Deskripsi Singkat | Jml MK | Mata Kuliah Pengampu (kode, semester, SKS) |
|------|--------------------|:---:|---------------------------------------------|
| **CPMK041** | Mengintegrasikan infrastruktur teknologi informasi (jaringan, server, platform, layanan) | 6 | Jaringan Komputer 1 (TIN302, sem 3, 4 SKS) `+`; Pemrograman Web Dasar (TIN304, sem 3, 4 SKS); Pemrograman Web Lanjut (TIN4120, sem 4, 4 SKS); Jaringan Komputer 2 (TIN5248, sem 5, 4 SKS) `+`; Internet of Things (TIN6252, sem 6, 4 SKS); Aplikasi Seluler(Mobile) (TIN6253, sem 7, 4 SKS) |
| **CPMK042** | Mengkonfigurasi infrastruktur teknologi informasi | 4 | Bahasa Inggris (INS1106, sem 1, 2 SKS); Sistem Web dan Seluler (Mobile) (TIN7138, sem 7, 4 SKS); Magang/Praktik Kerja (TIN7260, sem 7, 4 SKS); Kuliah Kerja Nyata (KKN) (TIN7261, sem 7, 4 SKS) |
| **CPMK043** | Mengadministrasikan infrastruktur teknologi informasi untuk mendukung kebutuhan organisasi secara efektif | 4 | Pengantar Teknologi Informasi (TIN1103, sem 1, 2 SKS); Komunikasi Data (TIN1104, sem 1, 2 SKS); Bahasa Inggris Sains (TIN2109, sem 2, 2 SKS); Hardware/Software (TIN306, sem 3, 2 SKS) |

> Total 3 CPMK untuk CPL04.

### CPL05 — Keamanan dan Manajemen Sistem Informasi

| CPMK | Deskripsi Singkat | Jml MK | Mata Kuliah Pengampu (kode, semester, SKS) |
|------|--------------------|:---:|---------------------------------------------|
| **CPMK051** | Menerapkan prinsip-prinsip keamanan siber dalam merancang dan mengelola sistem informasi | 4 | Sistem Operasi (TIN2107, sem 2, 2 SKS); Jaringan Komputer 1 (TIN302, sem 3, 4 SKS); Manajemen Sistem Informasi (TIN305, sem 3, 2 SKS); Jaringan Komputer 2 (TIN5248, sem 5, 4 SKS) |
| **CPMK052** | Menerapkan manajemen risiko dalam sistem informasi terdistribusi | 4 | Infomatika Medis (TIN5249, sem 5, 2 SKS); Teknologi Platform (TIN6131, sem 6, 2 SKS); Prinsip Keamanan Siber (TIN6133, sem 6, 2 SKS); Sistem dan Layanan Virtual (TIN6254, sem 6, 2 SKS) |
| **CPMK053** | Menerapkan tata kelola informasi untuk sistem informasi yang aman dan andal | 4 | Sistem Basis Data (TIN2111, sem 2, 4 SKS); Jaringan Komputer 1 (TIN302, sem 3, 4 SKS); Sistem Basis Data Lanjut (TIN5245, sem 5, 4 SKS); Jaringan Komputer 2 (TIN5248, sem 5, 4 SKS) |

> Total 3 CPMK untuk CPL05.

### CPL06 — Analitik Data dan Kecerdasan Buatan

| CPMK | Deskripsi Singkat | Jml MK | Mata Kuliah Pengampu (kode, semester, SKS) |
|------|--------------------|:---:|---------------------------------------------|
| **CPMK061** | Menerapkan teknik analitik data (deskriptif, prediktif, preskriptif) | 4 | Sistem Basis Data (TIN2111, sem 2, 4 SKS); Data Mining (TIN4123, sem 4, 4 SKS); Data Science (TIN5117, sem 5, 4 SKS); Sistem Basis Data Lanjut (TIN5245, sem 5, 4 SKS) |
| **CPMK062** | Menerapkan machine learning dan kecerdasan buatan untuk membangun model | 4 | Kecerdasan Buatan (TIN5246, sem 5, 4 SKS); Multimedia (TIN5247, sem 5, 4 SKS); Business Problem & DS Solution (TIN6250, sem 6, 4 SKS); Riset Operasi (TIN6251, sem 6, 4 SKS) |
| **CPMK063** | Menghasilkan wawasan berbasis data yang mendukung pengambilan keputusan | 4 | Aljabar Linier dan Matriks (TIN1105, sem 1, 2 SKS); Komputer Grafis (TIN2106, sem 2, 2 SKS); Kalkulus (TIN2110, sem 2, 2 SKS); E-Health (TIN7257, sem 7, 4 SKS) |
| **CPMK064** | Menjunjung etika data (privasi, keadilan algoritmik, transparansi) dalam praktik analitik dan AI | 4 | Pengantar Kecerdasan Buatan (TIN4121, sem 4, 2 SKS); Sistem Informasi Kesehatan (TIN4124, sem 4, 2 SKS); Statistik (TIN4125, sem 4, 2 SKS); Manajemen Informasi (TIN5118, sem 5, 2 SKS) |

> Total 4 CPMK untuk CPL06.

### CPL07 — Sikap dan Wawasan Keislaman

| CPMK | Deskripsi Singkat | Jml MK | Mata Kuliah Pengampu (kode, semester, SKS) |
|------|--------------------|:---:|---------------------------------------------|
| **CPMK071** | Menginternalisasi nilai keimanan dan akhlak sesuai paham Al-Islam | 4 | AIK I (Keimanan, Kemanusiaan dan Akhlak) (INS1101, sem 1, 2 SKS); AIK II (Ibadah dan Muamalah) (INS2102, sem 2, 2 SKS); Kemuhammadiyahan dan Ke'Aisyiyahan (INS301, sem 3, 2 SKS); AIK IV (Islam dan IPTEK) (INS4104, sem 4, 2 SKS) |
| **CPMK072** | Menginternalisasi nilai ibadah dan muamalah sesuai paham Kemuhammadiyahan/'Aisyiyah | 4 | AIK I (Keimanan, Kemanusiaan dan Akhlak) (INS1101, sem 1, 2 SKS); AIK II (Ibadah dan Muamalah) (INS2102, sem 2, 2 SKS); Kemuhammadiyahan dan Ke'Aisyiyahan (INS301, sem 3, 2 SKS); AIK IV (Islam dan IPTEK) (INS4104, sem 4, 2 SKS) |
| **CPMK073** | Mengintegrasikan nilai Al-Islam Kemuhammadiyahan dalam kehidupan akademik dan pengembangan profesi TI | 4 | AIK I (Keimanan, Kemanusiaan dan Akhlak) (INS1101, sem 1, 2 SKS); AIK II (Ibadah dan Muamalah) (INS2102, sem 2, 2 SKS); Kemuhammadiyahan dan Ke'Aisyiyahan (INS301, sem 3, 2 SKS); AIK IV (Islam dan IPTEK) (INS4104, sem 4, 2 SKS) |

> Total 3 CPMK untuk CPL07.

### CPL08 — Sikap dan Wawasan Kebangsaan

| CPMK | Deskripsi Singkat | Jml MK | Mata Kuliah Pengampu (kode, semester, SKS) |
|------|--------------------|:---:|---------------------------------------------|
| **CPMK081** | Menunjukkan sikap kebangsaan dan nasionalisme sebagai warga negara Indonesia | 3 | Pancasila (NAS1101, sem 1, 2 SKS); Bahasa Indonesia (NAS1102, sem 1, 2 SKS); Kewarganegaraan (NAS2103, sem 2, 2 SKS) |
| **CPMK082** | Menunjukkan kepekaan sosial dan ketaatan hukum dalam kehidupan bermasyarakat dan bernegara | 3 | Pancasila (NAS1101, sem 1, 2 SKS); Bahasa Indonesia (NAS1102, sem 1, 2 SKS); Kewarganegaraan (NAS2103, sem 2, 2 SKS) |
| **CPMK083** | Berkontribusi pada peningkatan mutu kehidupan bermasyarakat berdasarkan Pancasila | 3 | Pancasila (NAS1101, sem 1, 2 SKS); Bahasa Indonesia (NAS1102, sem 1, 2 SKS); Kewarganegaraan (NAS2103, sem 2, 2 SKS) |

> Total 3 CPMK untuk CPL08. *(Catatan: hanya 3 MK Wajib Nasional tersedia — lihat §6 poin 2 untuk penjelasan pengecualian jumlah MK.)*

---

## 4. Lampiran — Rekap Alokasi per Mata Kuliah (Seluruh 65 MK)

`**` = MK dengan batas maksimum CPMK yang dilonggarkan dari SKS (lihat pengecualian §2.1). `*` = MK 4 SKS yang diperkuat dengan 1 CPMK tambahan pada revisi §2.2.

| Sem | Kode | Mata Kuliah | SKS | Maks. CPMK | CPMK Ditugaskan | Jml |
|:---:|------|-------------|:---:|:---:|------------------|:---:|
| 1 | INS1101 | AIK I (Keimanan, Kemanusiaan dan Akhlak) | 2 | 3\*\* | CPMK071, CPMK072, CPMK073 | 3 |
| 1 | INS1106 | Bahasa Inggris | 2 | 2 | CPMK023, CPMK042 | 2 |
| 1 | NAS1101 | Pancasila | 2 | 3\*\* | CPMK081, CPMK082, CPMK083 | 3 |
| 1 | NAS1102 | Bahasa Indonesia | 2 | 3\*\* | CPMK081, CPMK082, CPMK083 | 3 |
| 1 | TIN1101 | Logika Informatika | 2 | 2 | CPMK012 | 1 |
| 1 | TIN1102 | Algoritma dan Pemrograman | 4 | 4\* | CPMK011, CPMK014, CPMK032 | 3 |
| 1 | TIN1103 | Pengantar Teknologi Informasi | 2 | 2 | CPMK023, CPMK043 | 2 |
| 1 | TIN1104 | Komunikasi Data | 2 | 2 | CPMK043 | 1 |
| 1 | TIN1105 | Aljabar Linier dan Matriks | 2 | 2 | CPMK063 | 1 |
| 2 | INS2102 | AIK II (Ibadah dan Muamalah) | 2 | 3\*\* | CPMK071, CPMK072, CPMK073 | 3 |
| 2 | INS2105 | Kewirausahaan | 2 | 2 | CPMK023, CPMK031 | 2 |
| 2 | NAS2103 | Kewarganegaraan | 2 | 3\*\* | CPMK081, CPMK082, CPMK083 | 3 |
| 2 | TIN2106 | Komputer Grafis | 2 | 2 | CPMK063 | 1 |
| 2 | TIN2107 | Sistem Operasi | 2 | 2 | CPMK051 | 1 |
| 2 | TIN2108 | Struktur Data | 4 | 4\* | CPMK011, CPMK014, CPMK032 | 3 |
| 2 | TIN2109 | Bahasa Inggris Sains | 2 | 2 | CPMK043 | 1 |
| 2 | TIN2110 | Kalkulus | 2 | 2 | CPMK063 | 1 |
| 2 | TIN2111 | Sistem Basis Data | 4 | 4 | CPMK053, CPMK061 | 2 |
| 2 | TIN2112 | Dasar Dasar Perangkat Lunak | 2 | 2 | CPMK012 | 1 |
| 3 | INS301 | Kemuhammadiyahan dan Ke'Aisyiyahan | 2 | 3\*\* | CPMK071, CPMK072, CPMK073 | 3 |
| 3 | TIN302 | Jaringan Komputer 1 | 4 | 4\* | CPMK041, CPMK051, CPMK053 | 3 |
| 3 | TIN303 | Pemrograman Berorientasi Objek (PBO) | 4 | 4 | CPMK011, CPMK033 | 2 |
| 3 | TIN304 | Pemrograman Web Dasar | 4 | 4 | CPMK033, CPMK041 | 2 |
| 3 | TIN305 | Manajemen Sistem Informasi | 2 | 2 | CPMK051 | 1 |
| 3 | TIN306 | Hardware/Software | 2 | 2 | CPMK043 | 1 |
| 3 | TIN307 | Organisasi & Arsitektur Komputer | 2 | 2 | CPMK012 | 1 |
| 3 | TIN308 | Rekayasa Perangkat Lunak (RPL) | 2 | 2 | CPMK012 | 1 |
| 4 | INS4104 | AIK IV (Islam dan IPTEK) | 2 | 3\*\* | CPMK071, CPMK072, CPMK073 | 3 |
| 4 | TIN4120 | Pemrograman Web Lanjut | 4 | 4 | CPMK033, CPMK041 | 2 |
| 4 | TIN4121 | Pengantar Kecerdasan Buatan | 2 | 2 | CPMK064 | 1 |
| 4 | TIN4122 | Embedded Sistem | 2 | 2 | CPMK013 | 1 |
| 4 | TIN4123 | Data Mining | 4 | 4 | CPMK021, CPMK061 | 2 |
| 4 | TIN4124 | Sistem Informasi Kesehatan | 2 | 2 | CPMK064 | 1 |
| 4 | TIN4125 | Statistik | 2 | 2 | CPMK064 | 1 |
| 4 | TIN4126 | Interaksi Manusia dan Komputer | 2 | 2 | CPMK031 | 1 |
| 5 | TIN5117 | Data Science | 4 | 4 | CPMK021, CPMK061 | 2 |
| 5 | TIN5118 | Manajemen Informasi | 2 | 2 | CPMK064 | 1 |
| 5 | TIN5119 | Paradigma Sistem | 2 | 2 | CPMK031 | 1 |
| 5 | TIN5120 | Perancangan dan Integrasi Sistem | 2 | 2 | CPMK031 | 1 |
| 5 | TIN5121 | Metodologi Penelitian | 2 | 2 | CPMK032 | 1 |
| 5 | TIN5123 | Analitik Data | 2 | 2 | CPMK013 | 1 |
| 5 | TIN5245 | Sistem Basis Data Lanjut | 4 | 4 | CPMK053, CPMK061 | 2 |
| 5 | TIN5246 | Kecerdasan Buatan | 4 | 4 | CPMK021, CPMK062 | 2 |
| 5 | TIN5247 | Multimedia | 4 | 4 | CPMK033, CPMK062 | 2 |
| 5 | TIN5248 | Jaringan Komputer 2 | 4 | 4\* | CPMK041, CPMK051, CPMK053 | 3 |
| 5 | TIN5249 | Infomatika Medis | 2 | 2 | CPMK052 | 1 |
| 6 | TIN6130 | Teknologi Sistem Terintegrasi | 2 | 2 | CPMK032 | 1 |
| 6 | TIN6131 | Teknologi Platform | 2 | 2 | CPMK052 | 1 |
| 6 | TIN6132 | Praktek Professional Global | 2 | 2 | CPMK032 | 1 |
| 6 | TIN6133 | Prinsip Keamanan Siber | 2 | 2 | CPMK052 | 1 |
| 6 | TIN6134 | Capstone Project 1 | 2 | 2 | CPMK013 | 1 |
| 6 | TIN6250 | Business Problem & DS Solution | 4 | 4 | CPMK021, CPMK062 | 2 |
| 6 | TIN6251 | Riset Operasi | 4 | 4 | CPMK022, CPMK062 | 2 |
| 6 | TIN6252 | Internet of Things | 4 | 4\* | CPMK032, CPMK041 | 2 |
| 6 | TIN6254 | Sistem dan Layanan Virtual | 2 | 2 | CPMK052 | 1 |
| 7 | TIN6253 | Aplikasi Seluler(Mobile) | 4 | 4\* | CPMK032, CPMK041 | 2 |
| 7 | TIN7138 | Sistem Web dan Seluler (Mobile) | 4 | 4\* | CPMK032, CPMK042 | 2 |
| 7 | TIN7140 | Design User Experience | 2 | 2 | CPMK032 | 1 |
| 7 | TIN7141 | Capstone Project 2 | 2 | 2 | CPMK013 | 1 |
| 7 | TIN7257 | E-Health | 4 | 4 | CPMK022, CPMK063 | 2 |
| 7 | TIN7260 | Magang/Praktik Kerja | 4 | 4\* | CPMK022, CPMK032, CPMK042 | 3 |
| 7 | TIN7261 | Kuliah Kerja Nyata (KKN) | 4 | 4 | CPMK022, CPMK042 | 2 |
| 7 | TIN8142 | Seminar Proposal | 1 | 1 | CPMK014 | 1 |
| 8 | TIN8143 | Seminar Hasil | 1 | 1 | CPMK014 | 1 |
| 8 | TIN8144 | Skripsi | 4 | 4\* | CPMK011, CPMK023, CPMK033 | 3 |

---

## 5. Ringkasan Statistik

| Metrik | Nilai |
|--------|-------|
| Total CPMK | 26 |
| Total Mata Kuliah | 65 |
| Total pasangan (CPMK, MK) teralokasi | 110 (setelah revisi §2.2; semula 101) |
| CPMK dengan ≥4 MK | 23 dari 26 (CPMK081–083 = 3 MK, lihat pengecualian §2.1) |
| MK dengan 1 CPMK | 33 |
| MK dengan 2 CPMK | 19 |
| MK dengan 3 CPMK (7 AIK/Wajib Nasional + 6 hasil revisi §2.2) | 13 |
| MK dengan 0 CPMK | 0 ✅ |
| Pelanggaran batas SKS | 0 ✅ |
| Pelanggaran batas CPL (CPMK ke MK di luar CPL induknya) | 0 ✅ |

---

## 6. Verifikasi dan Catatan Penting untuk Validasi Prodi

1. **Verifikasi terprogram** (skrip Python) mengonfirmasi: seluruh 65 MK memiliki ≥1 CPMK; seluruh alokasi CPMK→MK berada dalam batas CPL yang sah (tidak ada CPMK yang "bocor" ke MK di luar CPL induknya, ditelusuri via BK); tidak ada MK yang melebihi batas maksimum CPMK sesuai SKS-nya (termasuk yang dilonggarkan pada 7 MK pengecualian).
2. **CPL08 hanya memiliki 3 MK terhubung** (Pancasila, Bahasa Indonesia, Kewarganegaraan) karena BK28 (Wawasan Kebangsaan) — satu-satunya Bahan Kajian yang memuat CPL08 — hanya diampu oleh 3 mata kuliah dalam struktur kurikulum saat ini. Untuk memenuhi kaidah "≥4 MK per CPMK" secara ketat, Tim Kurikulum dapat mempertimbangkan: (a) menerima pengecualian ini apa adanya karena sifat MK Wajib Nasional yang memang terbatas jumlahnya secara nasional, atau (b) menambahkan mata kuliah lain yang secara substansi relevan (misalnya menjadikan BK29/AIK juga berkontribusi pendukung ke CPL08, atau menambah MK Wajib Nasional baru) — perubahan ini harus melalui validasi resmi karena akan mengubah BK28 di `Pemetaan-Detail-Bahan-Kajian.md`.
3. **7 MK (AIK I, AIK II, Kemuhammadiyahan, AIK IV, Pancasila, Bahasa Indonesia, Kewarganegaraan)** ditandai `**` karena menampung 3 CPMK meski hanya 2 SKS — didokumentasikan sebagai penyimpangan wajar mengingat seluruh CPMK dalam kelompok tersebut berasal dari **satu CPL afektif yang sama**, bukan kompetensi kognitif/psikomotorik yang bersaing memperebutkan jam SKS.
4. **Alokasi bersifat alokasi tingkat Program Studi (kurikulum)**, menunjukkan MK mana yang *berwenang* mengampu CPMK tertentu berdasarkan cakupan CPL/BK-nya. Dosen pengampu tiap MK tetap perlu memilih dan merumuskan Sub-CPMK spesifik dari CPMK yang dialokasikan ke mata kuliahnya (lihat BAB VIII §8.4 untuk contoh penurunan Sub-CPMK), sesuai arahan pengguna sebelumnya bahwa "dosen memilih CPMK mana saja yang terhubung dengan mata kuliah tersebut" — dokumen ini menyediakan **kolam pilihan yang sah** (bukan penugasan final tunggal per MK jika dosen ingin menekankan CPMK lain dalam kolam yang sama, selama tidak melanggar batas SKS dan batas CPL).
5. MK dengan 4 SKS pada umumnya diberi 2 CPMK (bukan dimaksimalkan ke 4) untuk menjaga distribusi merata CPMK ke berbagai MK lain yang juga memerlukan cakupan (agar tidak ada CPMK yang menumpuk hanya di sedikit MK besar). Setelah revisi §2.2: 6 MK (Algoritma dan Pemrograman, Struktur Data, Jaringan Komputer 1, Jaringan Komputer 2, Magang/Praktik Kerja, Skripsi) diperkuat dari 2 menjadi 3 CPMK; 3 MK (Internet of Things, Aplikasi Seluler, Sistem Web dan Seluler) diperkuat dari 1 menjadi 2 CPMK; 13 MK 4-SKS lainnya tidak diubah, tetap di 1–2 CPMK karena dinilai sudah cukup mewakili kolam CPL-nya. Tidak ada MK 4-SKS yang dimaksimalkan hingga 4 CPMK — Tim Kurikulum tetap berwenang menambah lebih lanjut (maks. hingga 4 CPMK) apabila dipandang perlu berdasarkan RPS masing-masing.
6. Dokumen ini bersifat **draf alokasi untuk validasi Tim Kurikulum** dan melengkapi (bukan menggantikan) `Pemetaan-CPMK.md` (metode dekomposisi CPL→CPMK resmi APTIKOM) dan `Pemetaan-Detail-Bahan-Kajian.md` (BK→CPL→MK). Kriteria dan daftar penambahan CPMK pada revisi ini didokumentasikan di §2.2 agar dapat ditelusuri dan divalidasi ulang oleh Tim Kurikulum.

---

*Dokumen ini disusun sebagai pelengkap Pemetaan-CPMK.md dan BAB VIII — CPMK dan Sub-CPMK, Dokumen Kurikulum OBE Program Studi S1 Teknologi Informasi 2027, Institut Sains Teknologi dan Kesehatan Aisyiyah Kendari.*
