# PEMETAAN SUB-CPMK — SELURUH MATA KULIAH

**Dokumen Pelengkap Pemetaan-CPMK.md, Pemetaan-CPMK-Alokasi-MK.md, dan BAB VIII (CPMK dan Sub-CPMK) — Program Studi S1 Teknologi Informasi, Institut Sains Teknologi dan Kesehatan Aisyiyah Kendari, Kurikulum 2027**

> Dokumen ini merinci **Sub-CPMK** untuk seluruh 65 mata kuliah, sebagai turunan operasional dari alokasi CPMK→MK yang telah divalidasi pada `Pemetaan-CPMK-Alokasi-MK.md` (122 pasangan CPMK-MK, revisi §2.3). Sub-CPMK adalah rincian capaian per pertemuan/kelompok pertemuan yang harus dicapai mahasiswa agar CPMK pada mata kuliah tersebut tercapai secara utuh, mengikuti kode **Sub-CPMK + [kode CPMK] + [nomor urut]** (APTIKOM 2023 §9.3).

---

## 1. Konsep dan Alur Penyusunan

```
Mata Kuliah (dikelompokkan per semester)
 ↓ CPMK yang dialokasikan ke MK tersebut (lihat Pemetaan-CPMK-Alokasi-MK.md §4)
 ↓ Sub-CPMK (dirinci per kelompok CPMK, mempertimbangkan Bahan Kajian MK + CPL induk)
```

Urutan penyusunan mengikuti permintaan Tim Kurikulum:

1. **Mata kuliah dikumpulkan per semester** (1–8), mengikuti struktur kurikulum yang sudah ada.
2. **CPMK milik tiap mata kuliah** diambil langsung dari alokasi final (`Pemetaan-CPMK-Alokasi-MK.md` §4) — tidak ada CPMK baru yang ditambahkan atau dihapus pada tahap ini.
3. **Sub-CPMK dirumuskan berkelompok per CPMK** di bawah tiap mata kuliah — bukan dicampur lintas-CPMK — agar keterlacakan Sub-CPMK → CPMK → CPL tetap eksplisit.

---

## 2. Aturan Penyusunan Sub-CPMK

| Aturan | Ketentuan |
|--------|-----------|
| **Keterikatan MK** | Setiap Sub-CPMK melekat pada satu mata kuliah spesifik — tidak ada Sub-CPMK lintas-MK (berbeda dari CPMK yang boleh lintas-MK). |
| **Sumber isi/deskripsi** | Deskripsi Sub-CPMK disusun dengan mempertimbangkan **tiga rujukan sekaligus**: (a) Bahan Kajian (BK) yang terhubung ke MK tersebut (`Pemetaan-Detail-Bahan-Kajian.md`), (b) rumusan CPMK induk (`Pemetaan-CPMK.md` §2), dan (c) CPL yang dibebankan (agar tidak menyimpang dari kompetensi lulusan). |
| **Jumlah — MK 1 SKS** | *(Ekstrapolasi metodologis — lihat catatan §2.1)* minimal 2, maksimal 4 Sub-CPMK. |
| **Jumlah — MK 2 SKS** | Minimal **4**, maksimal **8** Sub-CPMK. |
| **Jumlah — MK 4 SKS** | Minimal **6**, maksimal **10** Sub-CPMK. |
| **Relevansi industri** | Sub-CPMK pada mata kuliah **terapan/spesialisasi** disusun mempertimbangkan kebutuhan dan tren industri TI terkini (mis. cloud-native, generative AI, zero-trust security, framework modern), **kecuali** mata kuliah tersebut adalah **teori dasar** (lihat klasifikasi §2.2) atau mata kuliah wajib umum/karakter — keduanya cukup mengikuti kaidah SMART dan progresi taksonomi Bloom/Gagne tanpa dipaksakan mengikuti tren pasar. |

### 2.1 Catatan Metodologis — MK 1 SKS

Aturan asli dari Tim Kurikulum hanya menetapkan pita jumlah Sub-CPMK untuk MK 2 SKS (4–8) dan 4 SKS (6–10); tidak ada MK 3 SKS dalam kurikulum ini, tetapi terdapat **2 MK berbobot 1 SKS** (Seminar Proposal TIN8142, Seminar Hasil TIN8143). Karena tidak ada ketentuan eksplisit, diterapkan **ekstrapolasi proporsional**: pita 2–4 Sub-CPMK (kira-kira separuh pita 2 SKS), dan dipilih **3 Sub-CPMK** untuk kedua MK tersebut (kegiatan seminar terfokus, tidak memerlukan rincian sebanyak MK reguler). Ini didokumentasikan secara eksplisit agar dapat divalidasi ulang oleh Tim Kurikulum, bukan diam-diam disamakan dengan pita 2 SKS.

### 2.2 Klasifikasi Mata Kuliah — Dasar vs. Terapan/Industri

Untuk menjalankan aturan "pertimbangkan kebutuhan industri, kecuali teori dasar", seluruh 65 MK diklasifikasikan sebagai berikut:

**(A) Teori Dasar / Fondasi (16 MK)** — Sub-CPMK tetap disusun dengan KKO ranah HOTS (analisis/evaluasi/kreasi, lihat §2.3), tanpa embel-embel tren industri karena kontennya bersifat fondasional dan relatif stabil:

Logika Informatika (TIN1101), Algoritma dan Pemrograman (TIN1102), Aljabar Linier dan Matriks (TIN1105), Komunikasi Data (TIN1104), Pengantar Teknologi Informasi (TIN1103), Struktur Data (TIN2108), Sistem Operasi (TIN2107), Kalkulus (TIN2110), Sistem Basis Data (TIN2111), Dasar Dasar Perangkat Lunak (TIN2112), Komputer Grafis (TIN2106), Hardware/Software (TIN306), Organisasi & Arsitektur Komputer (TIN307), Rekayasa Perangkat Lunak/RPL (TIN308), Statistik (TIN4125), Metodologi Penelitian (TIN5121).

**(B) Wajib Umum/Karakter — Non-Teknis (10 MK)** — Sub-CPMK murni berbasis internalisasi sikap/nilai (ranah afektif) sesuai CPL07/CPL08 dan kompetensi bahasa/kewirausahaan; "tren industri TI" tidak relevan secara substansi:

AIK I (INS1101), AIK II (INS2102), Kemuhammadiyahan dan Ke'Aisyiyahan (INS301), AIK IV (INS4104), Pancasila (NAS1101), Bahasa Indonesia (NAS1102), Kewarganegaraan (NAS2103), Bahasa Inggris (INS1106), Bahasa Inggris Sains (TIN2109), Kewirausahaan (INS2105) *(memuat prinsip technopreneurship, disinggung ringan)*.

**(C) Terapan/Spesialisasi — Berorientasi Tren Industri (39 MK)** — Sub-CPMK memuat sekurangnya satu butir yang eksplisit mengaitkan capaian dengan praktik/tren industri TI terkini:

Jaringan Komputer 1 & 2, PBO, Pemrograman Web Dasar & Lanjut, Manajemen Sistem Informasi, Pengantar Kecerdasan Buatan, Embedded Sistem, Data Mining, Sistem Informasi Kesehatan, Interaksi Manusia dan Komputer, Data Science, Manajemen Informasi, Paradigma Sistem, Perancangan dan Integrasi Sistem, Analitik Data, Sistem Basis Data Lanjut, Kecerdasan Buatan, Multimedia, Infomatika Medis, Teknologi Sistem Terintegrasi, Teknologi Platform, Praktek Professional Global, Prinsip Keamanan Siber, Capstone Project 1 & 2, Business Problem & DS Solution, Riset Operasi, Internet of Things, Sistem dan Layanan Virtual, Aplikasi Seluler, Sistem Web dan Seluler, Design User Experience, E-Health, Magang/Praktik Kerja, KKN, Seminar Proposal, Seminar Hasil, Skripsi.

### 2.3 Standar KKO Sub-CPMK untuk Jenjang S1 (KKNI Level 6) — HOTS

Mengikuti pedoman penyusunan kurikulum OBE untuk jenjang Sarjana (KKNI Level 6/SN-Dikti), seluruh Sub-CPMK pada dokumen ini disusun dengan formula **Sub-CPMK = [Kata Kerja Operasional] + [Materi Kajian/Objek] + [Kondisi/Bentuk Evaluasi]**, dengan KKO wajib diambil dari ranah *Higher Order Thinking Skills* (HOTS) Taksonomi Bloom — **Menganalisis (C4)**, **Mengevaluasi (C5)**, dan **Mencipta (C6)** — dan **tidak** menggunakan kata "memahami" atau "mengerti" sebagai KKO. Daftar KKO yang dipakai:

- **C4 — Menganalisis:** menganalisis, menguraikan, mendiagnosis, mengkritisi, membandingkan.
- **C5 — Mengevaluasi:** menilai, mengevaluasi, menyimpulkan, menguji, mengadministrasikan (dalam konteks evaluasi berkelanjutan).
- **C6 — Mencipta:** merancang, menyusun, membuat, mengembangkan, memformulasikan, menghasilkan, mengintegrasikan, menulis.

Ketentuan ini berlaku **ketat untuk seluruh 65 MK** tanpa pengecualian kategori (Teori Dasar, Wajib Umum/Karakter, maupun Terapan) — sesuai arahan Tim Kurikulum bahwa jenjang S1 harus konsisten menuntut penalaran tingkat tinggi, bukan sekadar hafalan/pemahaman (C1/C2), bahkan untuk mata kuliah fondasional. Pengecualian hanya berlaku untuk **Sub-CPMK ranah afektif** (ditandai A3/A4, terutama pada MK Wajib Umum/Karakter seperti AIK, Pancasila, Kewarganegaraan) karena taksonomi HOTS Bloom adalah kerangka kognitif dan tidak secara langsung berlaku pada ranah sikap/nilai (Taksonomi Krathwohl) — Sub-CPMK afektif tetap mengacu pada level A2–A5 sebagaimana telah diaudit pada revisi sebelumnya.

**Metodologi konversi** (dari draf awal yang sebagian masih C2/C3): setiap Sub-CPMK berverba LOTS/MOTS dikonversi dengan salah satu dari tiga pola, dipilih sesuai konteks kalimat agar tetap wajar secara bahasa dan tidak mengubah cakupan materi: (a) **penggantian KKO langsung** ke sinonim HOTS yang levelnya setara (mis. "Mengimplementasikan" → "Mengembangkan"; "Menyusun"/"Menulis" dipertahankan karena sudah termasuk KKO C6 baku); (b) **penambahan verba analitis di depan** KKO asli (mis. "Menerapkan X" → "Menganalisis dan menerapkan X") bila tindakan penerapannya memang mensyaratkan analisis kebutuhan/konteks terlebih dahulu; (c) **relabel level saja** tanpa mengubah redaksi, untuk KKO yang secara definisi taksonomi memang sudah HOTS meski sebelumnya salah ditandai (mis. "Mengintegrasikan" = mensintesis elemen terpisah menjadi satu kesatuan = C6).

---

## 3. Pemetaan Sub-CPMK per Semester

### Navigasi Cepat

| Semester | Jumlah MK | Tautan |
|:--:|:--:|---|
| 1 | 9 | [Lihat Semester 1](#semester-1) |
| 2 | 10 | [Lihat Semester 2](#semester-2) |
| 3 | 8 | [Lihat Semester 3](#semester-3) |
| 4 | 8 | [Lihat Semester 4](#semester-4) |
| 5 | 11 | [Lihat Semester 5](#semester-5) |
| 6 | 9 | [Lihat Semester 6](#semester-6) |
| 7 | 8 | [Lihat Semester 7](#semester-7) |
| 8 | 2 | [Lihat Semester 8](#semester-8) |

---

### SEMESTER 1

**Ringkasan mata kuliah semester ini:**

| Kode | Mata Kuliah | SKS | Kategori | CPMK | Sub-CPMK |
|------|-------------|:--:|----------|:--:|:--:|
| INS1101 | AIK I (Keimanan, Kemanusiaan dan Akhlak) | 2 | (B) | 3 | 6 |
| INS1106 | Bahasa Inggris | 2 | (B) | 2 | 6 |
| NAS1101 | Pancasila | 2 | (B) | 3 | 6 |
| NAS1102 | Bahasa Indonesia | 2 | (B) | 3 | 6 |
| TIN1101 | Logika Informatika | 2 | (A) | 1 | 4 |
| TIN1102 | Algoritma dan Pemrograman | 4 | (A) | 3 | 9 |
| TIN1103 | Pengantar Teknologi Informasi | 2 | (A) | 2 | 6 |
| TIN1104 | Komunikasi Data | 2 | (A) | 1 | 4 |
| TIN1105 | Aljabar Linier dan Matriks | 2 | (A) | 1 | 4 |

#### `INS1101` — AIK I (Keimanan, Kemanusiaan dan Akhlak)

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (B) Wajib Umum/Karakter &nbsp;·&nbsp; **Bahan Kajian:** BK29 (Al-Islam dan Kemuhammadiyahan)

**CPMK071 — Menginternalisasi nilai keimanan dan akhlak sesuai paham Al-Islam** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK071.1 | Menganalisis konsep keimanan (rukun iman) dan implikasinya pada akhlak pribadi | C4 |
| 2 | Sub-CPMK071.2 | Menunjukkan perilaku akhlak mulia (jujur, amanah) dalam interaksi akademik sehari-hari | A3 |

**CPMK072 — Menginternalisasi nilai ibadah dan muamalah sesuai paham Kemuhammadiyahan/'Aisyiyah** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK072.1 | Menganalisis tata cara ibadah mahdah dan ghairu mahdah sesuai tuntunan Al-Islam | C4 |
| 2 | Sub-CPMK072.2 | Mempraktikkan nilai muamalah (interaksi sosial-ekonomi) sesuai prinsip syariah dalam kehidupan kampus | A3 |

**CPMK073 — Mengintegrasikan nilai Al-Islam Kemuhammadiyahan dalam kehidupan akademik dan profesi TI** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK073.1 | Mengaitkan nilai keislaman dasar dengan tanggung jawab sebagai mahasiswa Teknologi Informasi | A3 |
| 2 | Sub-CPMK073.2 | Menunjukkan komitmen mengintegrasikan nilai Islam dalam rencana pengembangan karier TI | A4 |

---

#### `INS1106` — Bahasa Inggris

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (B) Wajib Umum/Karakter &nbsp;·&nbsp; **Bahan Kajian:** BK08 (Praktek Profesional Global)

**CPMK023 — Mendefinisikan permasalahan computing kompleks berdasarkan pengetahuan domain yang relevan** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK023.1 | Menganalisis istilah dan struktur kalimat teknis Bahasa Inggris pada dokumen TI | C4 |
| 2 | Sub-CPMK023.2 | Menganalisis dan merangkum permasalahan computing dari teks berbahasa Inggris menjadi rumusan masalah yang jelas | C4 |
| 3 | Sub-CPMK023.3 | Mendefinisikan kebutuhan/permasalahan domain TI berdasarkan artikel/dokumentasi berbahasa Inggris | C4 |

**CPMK042 — Mengkonfigurasi infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK042.1 | Menganalisis isi manual/dokumentasi konfigurasi perangkat TI berbahasa Inggris | C4 |
| 2 | Sub-CPMK042.2 | Menyusun instruksi/laporan konfigurasi teknis sederhana dalam Bahasa Inggris | C6 |
| 3 | Sub-CPMK042.3 | Menganalisis dan mempresentasikan langkah konfigurasi teknis dalam Bahasa Inggris lisan dan tulisan | C4 |

---

#### `NAS1101` — Pancasila

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (B) Wajib Umum/Karakter &nbsp;·&nbsp; **Bahan Kajian:** BK28 (Wawasan Kebangsaan)

**CPMK081 — Menunjukkan sikap kebangsaan dan nasionalisme sebagai warga negara Indonesia** *(CPL08)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK081.1 | Menganalisis nilai-nilai dasar Pancasila sebagai dasar negara dan pandangan hidup bangsa | C4 |
| 2 | Sub-CPMK081.2 | Menunjukkan sikap nasionalisme dalam aktivitas akademik dan kemahasiswaan | A3 |

**CPMK082 — Menunjukkan kepekaan sosial dan ketaatan hukum dalam kehidupan bermasyarakat dan bernegara** *(CPL08)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK082.1 | Menganalisis isu kepekaan sosial dan ketaatan hukum di lingkungan kampus dan masyarakat | C4 |
| 2 | Sub-CPMK082.2 | Menunjukkan perilaku taat hukum dan peduli lingkungan sosial sebagai warga negara | A3 |

**CPMK083 — Berkontribusi pada peningkatan mutu kehidupan bermasyarakat berdasarkan Pancasila** *(CPL08)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK083.1 | Merumuskan gagasan kontribusi pribadi terhadap peningkatan mutu kehidupan bermasyarakat | A3 |
| 2 | Sub-CPMK083.2 | Menyusun rencana aksi sederhana penerapan nilai Pancasila dalam profesi TI ke depan | A4 |

---

#### `NAS1102` — Bahasa Indonesia

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (B) Wajib Umum/Karakter &nbsp;·&nbsp; **Bahan Kajian:** BK28 (Wawasan Kebangsaan)

**CPMK081 — Menunjukkan sikap kebangsaan dan nasionalisme sebagai warga negara Indonesia** *(CPL08)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK081.1 | Menganalisis kaidah Bahasa Indonesia baku dalam konteks akademik dan kebangsaan | C4 |
| 2 | Sub-CPMK081.2 | Menunjukkan penggunaan Bahasa Indonesia yang baik dan benar sebagai wujud identitas kebangsaan | A3 |

**CPMK082 — Menunjukkan kepekaan sosial dan ketaatan hukum dalam kehidupan bermasyarakat dan bernegara** *(CPL08)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK082.1 | Menyusun karya tulis (esai/laporan) yang mencerminkan kepekaan sosial sesuai kaidah bahasa baku | C6 |
| 2 | Sub-CPMK082.2 | Menunjukkan sikap disiplin berbahasa sesuai etika akademik dalam penulisan ilmiah | A3 |

**CPMK083 — Berkontribusi pada peningkatan mutu kehidupan bermasyarakat berdasarkan Pancasila** *(CPL08)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK083.1 | Menulis artikel/opini yang berkontribusi pada wacana mutu kehidupan bermasyarakat | C6 |
| 2 | Sub-CPMK083.2 | Mempresentasikan gagasan tertulis secara lisan dengan Bahasa Indonesia yang baik dan benar | A4 |

---

#### `TIN1101` — Logika Informatika

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK14 (Logika dan Matematika Diskrit)

**CPMK012 — Menguasai konsep dasar sains komputasi meliputi logika, algoritma, dan struktur data** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK012.1 | Menganalisis logika proposisional dan predikat sebagai dasar berpikir komputasional | C4 |
| 2 | Sub-CPMK012.2 | Menganalisis teori himpunan dan relasinya dengan struktur data | C4 |
| 3 | Sub-CPMK012.3 | Menganalisis dan menerapkan tabel kebenaran dan aturan inferensi untuk membuktikan validitas argumen | C4 |
| 4 | Sub-CPMK012.4 | Menganalisis dan menerapkan konsep graf dan kombinatorik dasar untuk memodelkan persoalan sederhana | C4 |

---

#### `TIN1102` — Algoritma dan Pemrograman

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK10 (Fundamental Pemrograman dan PL)

**CPMK011 — Menguasai konsep matematika yang relevan untuk komputasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK011.1 | Menganalisis notasi matematis dasar (variabel, ekspresi, kompleksitas Big-O) yang mendasari algoritma | C4 |
| 2 | Sub-CPMK011.2 | Menganalisis dan menerapkan penalaran logis-matematis untuk menyusun alur algoritma pemrograman | C4 |
| 3 | Sub-CPMK011.3 | Menganalisis dan menghitung kompleksitas waktu algoritma sederhana menggunakan notasi matematis | C4 |

**CPMK014 — Menganalisis dan memecahkan permasalahan computing kompleks** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK014.1 | Menganalisis permasalahan komputasi sederhana yang dapat diselesaikan dengan algoritma | C4 |
| 2 | Sub-CPMK014.2 | Menganalisis alternatif algoritma (percabangan, perulangan) untuk memecahkan suatu persoalan | C4 |
| 3 | Sub-CPMK014.3 | Memecahkan studi kasus computing sederhana dengan menyusun algoritma dan flowchart yang tepat | C4 |

**CPMK032 — Mengimplementasikan solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK032.1 | Menganalisis dan menerapkan struktur kontrol (sequence, selection, iteration) dalam bahasa pemrograman | C4 |
| 2 | Sub-CPMK032.2 | Mengembangkan fungsi/prosedur modular untuk menyelesaikan sub-masalah program | C6 |
| 3 | Sub-CPMK032.3 | Mengembangkan program lengkap dari rancangan algoritma menjadi kode yang dapat dieksekusi dan diuji | C6 |

---

#### `TIN1103` — Pengantar Teknologi Informasi

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK10, BK16 (Fundamental Pemrograman & PL; Arsitektur dan Organisasi Komputer)

**CPMK023 — Mendefinisikan permasalahan computing kompleks berdasarkan pengetahuan domain yang relevan** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK023.1 | Menganalisis ruang lingkup bidang computing (ilmu komputer, sistem informasi, teknologi informasi) | C4 |
| 2 | Sub-CPMK023.2 | Menganalisis permasalahan/kebutuhan TI pada berbagai domain (bisnis, kesehatan, pendidikan) | C4 |
| 3 | Sub-CPMK023.3 | Mendefinisikan profil masalah computing sederhana berdasarkan studi kasus suatu domain | C4 |

**CPMK043 — Mengadministrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK043.1 | Menganalisis komponen dasar infrastruktur TI (perangkat keras, jaringan, perangkat lunak) | C4 |
| 2 | Sub-CPMK043.2 | Menganalisis peran administrasi TI dalam mendukung operasional organisasi | C4 |
| 3 | Sub-CPMK043.3 | Menganalisis praktik pengelolaan infrastruktur TI sederhana pada organisasi | C4 |

---

#### `TIN1104` — Komunikasi Data

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK26 (Komunikasi Data)

**CPMK043 — Mengadministrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK043.1 | Menganalisis konsep transmisi data dan sinyal analog/digital | C4 |
| 2 | Sub-CPMK043.2 | Menganalisis teknik modulasi, encoding, dan multiplexing dalam komunikasi data | C4 |
| 3 | Sub-CPMK043.3 | Menganalisis dan menerapkan teknik deteksi dan koreksi kesalahan (error detection/correction) pada transmisi data | C4 |
| 4 | Sub-CPMK043.4 | Mengevaluasi dan mengadministrasikan skema komunikasi data sederhana antar-perangkat menggunakan protokol dasar | C5 |

---

#### `TIN1105` — Aljabar Linier dan Matriks

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK23 (Matematika Terapan)

**CPMK063 — Menghasilkan wawasan berbasis data yang mendukung pengambilan keputusan** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK063.1 | Menganalisis konsep vektor, matriks, dan operasi dasarnya | C4 |
| 2 | Sub-CPMK063.2 | Menganalisis dan menerapkan operasi matriks (determinan, invers, eliminasi Gauss) untuk menyelesaikan sistem persamaan linier | C4 |
| 3 | Sub-CPMK063.3 | Menganalisis dan menerapkan konsep nilai eigen dan vektor eigen pada persoalan komputasi sederhana | C4 |
| 4 | Sub-CPMK063.4 | Menghasilkan interpretasi numerik dari operasi aljabar linier sebagai dasar pemodelan data lanjutan | C6 |

---

### SEMESTER 2

**Ringkasan mata kuliah semester ini:**

| Kode | Mata Kuliah | SKS | Kategori | CPMK | Sub-CPMK |
|------|-------------|:--:|----------|:--:|:--:|
| INS2102 | AIK II (Ibadah dan Muamalah) | 2 | (B) | 3 | 6 |
| INS2105 | Kewirausahaan | 2 | (B) | 2 | 6 |
| NAS2103 | Kewarganegaraan | 2 | (B) | 3 | 6 |
| TIN2106 | Komputer Grafis | 2 | (A) | 1 | 4 |
| TIN2107 | Sistem Operasi | 2 | (A) | 2 | 6 |
| TIN2108 | Struktur Data | 4 | (A) | 3 | 9 |
| TIN2109 | Bahasa Inggris Sains | 2 | (B) | 1 | 4 |
| TIN2110 | Kalkulus | 2 | (A) | 1 | 4 |
| TIN2111 | Sistem Basis Data | 4 | (A) | 2 | 8 |
| TIN2112 | Dasar Dasar Perangkat Lunak | 2 | (A) | 1 | 4 |

#### `INS2102` — AIK II (Ibadah dan Muamalah)

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (B) Wajib Umum/Karakter &nbsp;·&nbsp; **Bahan Kajian:** BK29 (Al-Islam dan Kemuhammadiyahan)

**CPMK071 — Menginternalisasi nilai keimanan dan akhlak sesuai paham Al-Islam** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK071.1 | Menganalisis konsep ibadah mahdah lanjutan dan hikmahnya bagi pembentukan akhlak | C4 |
| 2 | Sub-CPMK071.2 | Menunjukkan konsistensi praktik ibadah dalam rutinitas perkuliahan | A3 |

**CPMK072 — Menginternalisasi nilai ibadah dan muamalah sesuai paham Kemuhammadiyahan/'Aisyiyah** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK072.1 | Menganalisis prinsip muamalah (ekonomi syariah, interaksi sosial) sesuai paham Muhammadiyah | C4 |
| 2 | Sub-CPMK072.2 | Mempraktikkan prinsip muamalah dalam transaksi/interaksi sosial sehari-hari | A3 |

**CPMK073 — Mengintegrasikan nilai Al-Islam Kemuhammadiyahan dalam kehidupan akademik dan profesi TI** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK073.1 | Menghubungkan nilai ibadah-muamalah dengan etika kerja profesional bidang TI | A3 |
| 2 | Sub-CPMK073.2 | Menunjukkan sikap integritas berbasis nilai Islam dalam kerja kelompok akademik | A4 |

---

#### `INS2105` — Kewirausahaan

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (B) Wajib Umum/Karakter (bersinggungan dengan technopreneurship) &nbsp;·&nbsp; **Bahan Kajian:** BK13 (Manajemen Proyek TI)

**CPMK023 — Mendefinisikan permasalahan computing kompleks berdasarkan pengetahuan domain yang relevan** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK023.1 | Menganalisis konsep kewirausahaan dan peluang bisnis berbasis teknologi (technopreneurship) | C4 |
| 2 | Sub-CPMK023.2 | Menganalisis permasalahan/kebutuhan pasar yang dapat dijawab dengan solusi digital | C4 |
| 3 | Sub-CPMK023.3 | Mendefinisikan proposisi nilai (value proposition) produk/jasa digital berdasarkan kebutuhan pasar | C4 |

**CPMK031 — Merancang solusi berbasis computing yang memenuhi kebutuhan tertentu** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK031.1 | Menganalisis prinsip perencanaan bisnis (business model canvas) untuk usaha rintisan digital | C4 |
| 2 | Sub-CPMK031.2 | Merancang model bisnis sederhana untuk produk/jasa berbasis TI | C6 |
| 3 | Sub-CPMK031.3 | Merancang rencana pemasaran digital (digital marketing) mengikuti tren e-commerce terkini | C6 |

---

#### `NAS2103` — Kewarganegaraan

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (B) Wajib Umum/Karakter &nbsp;·&nbsp; **Bahan Kajian:** BK28 (Wawasan Kebangsaan)

**CPMK081 — Menunjukkan sikap kebangsaan dan nasionalisme sebagai warga negara Indonesia** *(CPL08)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK081.1 | Menganalisis wawasan kebangsaan dan hak/kewajiban warga negara Indonesia | C4 |
| 2 | Sub-CPMK081.2 | Menunjukkan sikap bela negara dan cinta tanah air dalam konteks kehidupan kampus | A3 |

**CPMK082 — Menunjukkan kepekaan sosial dan ketaatan hukum dalam kehidupan bermasyarakat dan bernegara** *(CPL08)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK082.1 | Menganalisis permasalahan hukum dan ketatanegaraan yang relevan dengan kehidupan bermasyarakat | C4 |
| 2 | Sub-CPMK082.2 | Menunjukkan ketaatan hukum dan kepekaan sosial dalam kasus-kasus kewarganegaraan aktual | A3 |

**CPMK083 — Berkontribusi pada peningkatan mutu kehidupan bermasyarakat berdasarkan Pancasila** *(CPL08)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK083.1 | Merumuskan gagasan solusi kewarganegaraan untuk isu sosial-digital (hoaks, etika bermedia sosial) | A3 |
| 2 | Sub-CPMK083.2 | Menunjukkan kontribusi nyata (kampanye/edukasi) untuk peningkatan mutu kehidupan bermasyarakat | A4 |

---

#### `TIN2106` — Komputer Grafis

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK20 (Komputasi Grafis dan Multimedia)

**CPMK063 — Menghasilkan wawasan berbasis data yang mendukung pengambilan keputusan** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK063.1 | Menganalisis prinsip dasar grafika komputer 2D (koordinat, transformasi geometri) | C4 |
| 2 | Sub-CPMK063.2 | Menganalisis dan menerapkan algoritma dasar rendering garis dan bidang pada grafika 2D | C4 |
| 3 | Sub-CPMK063.3 | Menganalisis dan menerapkan konsep dasar grafika 3D (proyeksi, pencahayaan sederhana) | C4 |
| 4 | Sub-CPMK063.4 | Menghasilkan visualisasi grafis sederhana yang merepresentasikan data/objek | C6 |

---

#### `TIN2107` — Sistem Operasi

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK15, BK01 (Sistem Operasi; Virtual Systems and Services)

**CPMK042 — Mengkonfigurasi infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK042.1 | Menganalisis manajemen proses, penjadwalan CPU, dan sinkronisasi pada sistem operasi | C4 |
| 2 | Sub-CPMK042.2 | Menganalisis dan menerapkan manajemen memori dan sistem berkas pada sistem operasi modern | C4 |
| 3 | Sub-CPMK042.3 | Menganalisis kebutuhan dan mengkonfigurasi lingkungan virtualisasi dasar (virtual machine) tingkat sistem operasi | C4 |

**CPMK051 — Menerapkan prinsip-prinsip keamanan siber dalam merancang dan mengelola sistem informasi** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK051.1 | Menganalisis mekanisme kontrol akses dan izin (permission) pada sistem operasi | C4 |
| 2 | Sub-CPMK051.2 | Menganalisis dan menerapkan praktik pengamanan dasar sistem operasi (hardening, update patch) | C4 |
| 3 | Sub-CPMK051.3 | Menganalisis dan menerapkan kebijakan keamanan akun dan proses untuk mencegah akses tidak sah | C4 |

---

#### `TIN2108` — Struktur Data

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK10, BK14 (Fundamental Pemrograman & PL; Logika dan Matematika Diskrit)

**CPMK011 — Menguasai konsep matematika yang relevan untuk komputasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK011.1 | Menganalisis representasi matematis struktur data (array, list) dan kompleksitas ruang/waktu | C4 |
| 2 | Sub-CPMK011.2 | Menganalisis kompleksitas algoritma pada operasi struktur data | C4 |
| 3 | Sub-CPMK011.3 | Menganalisis dan menerapkan konsep graf dan pohon (tree) sebagai struktur data lanjutan | C4 |

**CPMK014 — Menganalisis dan memecahkan permasalahan computing kompleks** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK014.1 | Menganalisis struktur data yang tepat untuk suatu permasalahan (stack, queue, linked list) | C4 |
| 2 | Sub-CPMK014.2 | Menganalisis efisiensi berbagai struktur data untuk kasus pencarian dan pengurutan | C4 |
| 3 | Sub-CPMK014.3 | Memecahkan studi kasus pengolahan data menggunakan kombinasi struktur data yang sesuai | C4 |

**CPMK032 — Mengimplementasikan solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK032.1 | Mengembangkan struktur data linear (array, linked list, stack, queue) dalam program | C6 |
| 2 | Sub-CPMK032.2 | Mengembangkan struktur data non-linear (tree, graph) dan operasi dasarnya | C6 |
| 3 | Sub-CPMK032.3 | Mengembangkan algoritma pencarian dan pengurutan (sorting/searching) menggunakan struktur data yang tepat | C6 |

---

#### `TIN2109` — Bahasa Inggris Sains

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (B) Wajib Umum/Karakter &nbsp;·&nbsp; **Bahan Kajian:** BK08 (Praktek Profesional Global)

**CPMK043 — Mengadministrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK043.1 | Menganalisis kosakata dan tata bahasa ilmiah (scientific English) bidang TI | C4 |
| 2 | Sub-CPMK043.2 | Menganalisis isi jurnal/paper ilmiah berbahasa Inggris bidang teknologi informasi | C4 |
| 3 | Sub-CPMK043.3 | Menyusun ringkasan (abstract) teknis berbahasa Inggris dari suatu topik TI | C6 |
| 4 | Sub-CPMK043.4 | Menganalisis dan mempresentasikan topik TI sederhana dalam Bahasa Inggris ilmiah secara lisan | C4 |

---

#### `TIN2110` — Kalkulus

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK23 (Matematika Terapan)

**CPMK063 — Menghasilkan wawasan berbasis data yang mendukung pengambilan keputusan** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK063.1 | Menganalisis konsep limit, turunan, dan integral fungsi satu variabel | C4 |
| 2 | Sub-CPMK063.2 | Menganalisis laju perubahan pada persoalan komputasi menggunakan turunan | C4 |
| 3 | Sub-CPMK063.3 | Menganalisis dan menerapkan integral untuk menghitung luas/akumulasi pada persoalan numerik sederhana | C4 |
| 4 | Sub-CPMK063.4 | Menghasilkan interpretasi kuantitatif dari model kalkulus sederhana untuk mendukung analisis data | C6 |

---

#### `TIN2111` — Sistem Basis Data

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK09 (Manajemen Data dan Informasi)

**CPMK053 — Menerapkan tata kelola informasi untuk sistem informasi yang aman dan andal** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK053.1 | Menganalisis konsep basis data relasional dan model Entity-Relationship (ER) | C4 |
| 2 | Sub-CPMK053.2 | Merancang skema basis data ternormalisasi (1NF–3NF) untuk studi kasus sederhana | C6 |
| 3 | Sub-CPMK053.3 | Menganalisis dan menerapkan tata kelola data (integritas, constraint) pada perancangan basis data | C4 |
| 4 | Sub-CPMK053.4 | Menganalisis dan menerapkan bahasa query (SQL DDL/DML) untuk mengelola basis data secara aman | C4 |

**CPMK061 — Menerapkan teknik analitik data (deskriptif, prediktif, preskriptif)** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK061.1 | Menganalisis teknik dasar manipulasi dan agregasi data menggunakan SQL | C4 |
| 2 | Sub-CPMK061.2 | Menganalisis dan menerapkan query analitik deskriptif (agregasi, join, subquery) pada basis data | C4 |
| 3 | Sub-CPMK061.3 | Menganalisis dan menerapkan indexing dan optimasi query dasar untuk performa basis data | C4 |
| 4 | Sub-CPMK061.4 | Menghasilkan laporan data sederhana dari hasil query basis data untuk mendukung analisis | C6 |

---

#### `TIN2112` — Dasar Dasar Perangkat Lunak

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK10 (Fundamental Pemrograman dan PL)

**CPMK012 — Menguasai konsep dasar sains komputasi meliputi logika, algoritma, dan struktur data** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK012.1 | Menganalisis siklus hidup pengembangan perangkat lunak (SDLC) | C4 |
| 2 | Sub-CPMK012.2 | Menganalisis paradigma pemrograman (prosedural, berorientasi objek) secara konseptual | C4 |
| 3 | Sub-CPMK012.3 | Menganalisis dan menerapkan tahap requirement dan desain sederhana untuk perangkat lunak skala kecil | C4 |
| 4 | Sub-CPMK012.4 | Menganalisis dan menerapkan praktik pengujian dasar (unit testing) pada modul perangkat lunak sederhana | C4 |

---

### SEMESTER 3

**Ringkasan mata kuliah semester ini:**

| Kode | Mata Kuliah | SKS | Kategori | CPMK | Sub-CPMK |
|------|-------------|:--:|----------|:--:|:--:|
| INS301 | Kemuhammadiyahan dan Ke'Aisyiyahan | 2 | (B) | 3 | 6 |
| TIN302 | Jaringan Komputer 1 | 4 | (C) | 3 | 9 |
| TIN303 | Pemrograman Berorientasi Objek (PBO) | 4 | (C) | 2 | 8 |
| TIN304 | Pemrograman Web Dasar | 4 | (C) | 2 | 8 |
| TIN305 | Manajemen Sistem Informasi | 2 | (C) | 1 | 4 |
| TIN306 | Hardware/Software | 2 | (A) | 2 | 6 |
| TIN307 | Organisasi & Arsitektur Komputer | 2 | (A) | 2 | 6 |
| TIN308 | Rekayasa Perangkat Lunak (RPL) | 2 | (A) | 2 | 6 |

#### `INS301` — Kemuhammadiyahan dan Ke'Aisyiyahan

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (B) Wajib Umum/Karakter &nbsp;·&nbsp; **Bahan Kajian:** BK29 (Al-Islam dan Kemuhammadiyahan)

**CPMK071 — Menginternalisasi nilai keimanan dan akhlak sesuai paham Al-Islam** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK071.1 | Menganalisis sejarah dan ideologi gerakan Muhammadiyah/'Aisyiyah serta relevansinya dengan penguatan keimanan | C4 |
| 2 | Sub-CPMK071.2 | Menunjukkan keteladanan akhlak tokoh Muhammadiyah dalam kehidupan kampus | A3 |

**CPMK072 — Menginternalisasi nilai ibadah dan muamalah sesuai paham Kemuhammadiyahan/'Aisyiyah** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK072.1 | Menganalisis praktik ibadah dan muamalah dalam konteks amal usaha Muhammadiyah/'Aisyiyah | C4 |
| 2 | Sub-CPMK072.2 | Berpartisipasi dalam kegiatan sosial-keagamaan organisasi Muhammadiyah/'Aisyiyah | A3 |

**CPMK073 — Mengintegrasikan nilai Al-Islam Kemuhammadiyahan dalam kehidupan akademik dan profesi TI** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK073.1 | Menghubungkan semangat pembaruan (tajdid) Muhammadiyah dengan pengembangan profesi TI | A3 |
| 2 | Sub-CPMK073.2 | Menunjukkan kontribusi memadukan dakwah dan teknologi dalam proyek akademik | A4 |

---

#### `TIN302` — Jaringan Komputer 1

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK03, BK26 (Jaringan Komputer; Komunikasi Data)

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis arsitektur jaringan komputer, model OSI dan TCP/IP | C4 |
| 2 | Sub-CPMK041.2 | Menganalisis dan menerapkan teknik routing dan switching dasar untuk menghubungkan jaringan lokal | C4 |
| 3 | Sub-CPMK041.3 | Mengintegrasikan jaringan kabel dan nirkabel mengikuti tren konektivitas Wi-Fi 6/5G pada infrastruktur kampus | C6 |

**CPMK051 — Menerapkan prinsip-prinsip keamanan siber** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK051.1 | Menganalisis ancaman keamanan jaringan (sniffing, spoofing, DoS) | C4 |
| 2 | Sub-CPMK051.2 | Menganalisis dan menerapkan mekanisme firewall dan ACL dasar untuk mengamankan lalu lintas jaringan | C4 |
| 3 | Sub-CPMK051.3 | Menganalisis dan menerapkan prinsip keamanan jaringan berbasis zero-trust pada rancangan jaringan sederhana | C4 |

**CPMK053 — Menerapkan tata kelola informasi** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK053.1 | Menganalisis skema pengalamatan IP (IPv4/IPv6) dan subnetting | C4 |
| 2 | Sub-CPMK053.2 | Menganalisis dan menerapkan tata kelola alamat dan dokumentasi jaringan (IP addressing plan) | C4 |
| 3 | Sub-CPMK053.3 | Menganalisis dan menerapkan monitoring dasar jaringan untuk memastikan keandalan layanan | C4 |

---

#### `TIN303` — Pemrograman Berorientasi Objek (PBO)

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK10 (Fundamental Pemrograman dan PL)

**CPMK011 — Menguasai konsep matematika yang relevan untuk komputasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK011.1 | Menganalisis konsep matematis relasi antar-objek (himpunan, pemetaan) dalam pemrograman berorientasi objek | C4 |
| 2 | Sub-CPMK011.2 | Menganalisis dan menerapkan konsep enkapsulasi dan abstraksi berbasis pemodelan logis kelas dan objek | C4 |
| 3 | Sub-CPMK011.3 | Menganalisis dan menerapkan pewarisan (inheritance) dan polimorfisme dalam merancang struktur kelas | C4 |
| 4 | Sub-CPMK011.4 | Menganalisis dan menerapkan pola desain (design pattern) sederhana untuk menyusun program modular | C4 |

**CPMK033 — Mengevaluasi solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK033.1 | Menganalisis kriteria keandalan dan efisiensi kode berorientasi objek | C4 |
| 2 | Sub-CPMK033.2 | Menganalisis dan menerapkan unit testing pada kelas dan objek program | C4 |
| 3 | Sub-CPMK033.3 | Mengevaluasi kualitas rancangan program OOP menggunakan prinsip SOLID | C5 |
| 4 | Sub-CPMK033.4 | Mengevaluasi performa aplikasi OOP dan mengusulkan refactoring mengikuti praktik clean code industri | C5 |

---

#### `TIN304` — Pemrograman Web Dasar

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK06 (Pengembangan Aplikasi Berbasis Platform)

**CPMK033 — Mengevaluasi solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK033.1 | Menganalisis struktur dasar halaman web (HTML, CSS) dan prinsip aksesibilitas | C4 |
| 2 | Sub-CPMK033.2 | Menganalisis dan menerapkan interaktivitas sisi klien menggunakan JavaScript dasar | C4 |
| 3 | Sub-CPMK033.3 | Mengevaluasi kualitas antarmuka web (responsif, usability) menggunakan checklist standar | C5 |
| 4 | Sub-CPMK033.4 | Mengevaluasi keandalan dan kecepatan (performance) halaman web sesuai praktik web modern (Core Web Vitals) | C5 |

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis arsitektur client-server pada aplikasi web | C4 |
| 2 | Sub-CPMK041.2 | Menganalisis dan menerapkan pemrograman sisi server dasar untuk memproses formulir/data web | C4 |
| 3 | Sub-CPMK041.3 | Mengintegrasikan halaman web dengan basis data sederhana | C6 |
| 4 | Sub-CPMK041.4 | Mengintegrasikan aplikasi web dengan layanan hosting mengikuti praktik deployment modern | C6 |

---

#### `TIN305` — Manajemen Sistem Informasi

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK18 (Manajemen Sistem Informasi)

**CPMK051 — Menerapkan prinsip-prinsip keamanan siber** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK051.1 | Menganalisis strategi sistem informasi dan keselarasannya dengan tujuan organisasi | C4 |
| 2 | Sub-CPMK051.2 | Menganalisis dan menerapkan kerangka kerja ITIL/tata kelola TI dalam pengelolaan layanan sistem informasi | C4 |
| 3 | Sub-CPMK051.3 | Menganalisis dan menerapkan prinsip keamanan informasi dalam kebijakan manajemen sistem informasi | C4 |
| 4 | Sub-CPMK051.4 | Menganalisis dan menerapkan praktik tata kelola TI mengikuti tren digital transformation pada studi kasus organisasi | C4 |

---

#### `TIN306` — Hardware/Software

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK16, BK12 (Arsitektur & Organisasi Komputer; Sistem Embedded)

**CPMK013 — Menguasai fondasi teknologi informasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK013.1 | Menganalisis komponen utama perangkat keras komputer (CPU, memori, I/O) | C4 |
| 2 | Sub-CPMK013.2 | Menganalisis hubungan perangkat keras dan perangkat lunak (firmware, driver, sistem operasi) | C4 |
| 3 | Sub-CPMK013.3 | Menganalisis dan menerapkan prosedur perakitan dan troubleshooting perangkat keras dasar | C4 |

**CPMK043 — Mengadministrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK043.1 | Menganalisis prosedur instalasi dan administrasi perangkat lunak sistem | C4 |
| 2 | Sub-CPMK043.2 | Menganalisis dan menerapkan pemeliharaan (maintenance) perangkat keras/lunak secara berkala | C4 |
| 3 | Sub-CPMK043.3 | Menganalisis dan menerapkan dokumentasi aset TI (hardware/software inventory) sederhana | C4 |

---

#### `TIN307` — Organisasi & Arsitektur Komputer

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK16, BK15 (Arsitektur & Organisasi Komputer; Sistem Operasi)

**CPMK012 — Menguasai konsep dasar sains komputasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK012.1 | Menganalisis arsitektur CPU dan siklus instruksi (fetch-decode-execute) | C4 |
| 2 | Sub-CPMK012.2 | Menganalisis hierarki memori (register, cache, RAM, storage) | C4 |
| 3 | Sub-CPMK012.3 | Menganalisis dan menerapkan konsep dasar komputasi paralel dan pipelining pada arsitektur modern | C4 |

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis arsitektur sistem I/O dan bus komunikasi antar-komponen | C4 |
| 2 | Sub-CPMK041.2 | Menganalisis dan menerapkan konsep integrasi antara arsitektur perangkat keras dan sistem operasi | C4 |
| 3 | Sub-CPMK041.3 | Menganalisis kebutuhan spesifikasi perangkat keras untuk suatu sistem komputasi | C4 |

---

#### `TIN308` — Rekayasa Perangkat Lunak (RPL)

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK10, BK13 (Fundamental Pemrograman & PL; Manajemen Proyek TI)

**CPMK012 — Menguasai konsep dasar sains komputasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK012.1 | Menganalisis model proses perangkat lunak (Waterfall, Agile/Scrum) | C4 |
| 2 | Sub-CPMK012.2 | Menganalisis prinsip rekayasa kebutuhan (requirement engineering) perangkat lunak | C4 |
| 3 | Sub-CPMK012.3 | Menganalisis dan menerapkan pemodelan perangkat lunak menggunakan UML (use case, class diagram) | C4 |

**CPMK022 — Menganalisis permasalahan computing kompleks** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK022.1 | Menganalisis kebutuhan fungsional dan non-fungsional dari suatu studi kasus | C4 |
| 2 | Sub-CPMK022.2 | Menganalisis kelayakan teknis dan risiko proyek perangkat lunak | C4 |
| 3 | Sub-CPMK022.3 | Menganalisis dan menyusun spesifikasi kebutuhan perangkat lunak (SRS) mengikuti praktik Agile terkini | C4 |

---

### SEMESTER 4

**Ringkasan mata kuliah semester ini:**

| Kode | Mata Kuliah | SKS | Kategori | CPMK | Sub-CPMK |
|------|-------------|:--:|----------|:--:|:--:|
| INS4104 | AIK IV (Islam dan IPTEK) | 2 | (B) | 3 | 6 |
| TIN4120 | Pemrograman Web Lanjut | 4 | (C) | 2 | 8 |
| TIN4121 | Pengantar Kecerdasan Buatan | 2 | (C) | 1 | 4 |
| TIN4122 | Embedded Sistem | 2 | (C) | 2 | 6 |
| TIN4123 | Data Mining | 4 | (C) | 2 | 8 |
| TIN4124 | Sistem Informasi Kesehatan | 2 | (C) | 2 | 6 |
| TIN4125 | Statistik | 2 | (A) | 1 | 4 |
| TIN4126 | Interaksi Manusia dan Komputer | 2 | (C) | 1 | 4 |

#### `INS4104` — AIK IV (Islam dan IPTEK)

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (B) Wajib Umum/Karakter &nbsp;·&nbsp; **Bahan Kajian:** BK29 (Al-Islam dan Kemuhammadiyahan)

**CPMK071 — Menginternalisasi nilai keimanan dan akhlak sesuai paham Al-Islam** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK071.1 | Menganalisis integrasi nilai keimanan dengan perkembangan ilmu pengetahuan dan teknologi | C4 |
| 2 | Sub-CPMK071.2 | Menunjukkan sikap kritis-reflektif terhadap isu iptek kontemporer berdasarkan nilai keislaman | A3 |

**CPMK072 — Menginternalisasi nilai ibadah dan muamalah sesuai paham Kemuhammadiyahan/'Aisyiyah** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK072.1 | Menganalisis pandangan fikih kontemporer terkait pemanfaatan teknologi (muamalah digital) | C4 |
| 2 | Sub-CPMK072.2 | Menunjukkan penerapan etika muamalah digital (transaksi daring, media sosial) sesuai nilai Islam | A3 |

**CPMK073 — Mengintegrasikan nilai Al-Islam Kemuhammadiyahan dalam kehidupan akademik dan profesi TI** *(CPL07)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK073.1 | Merumuskan gagasan pemanfaatan teknologi informasi untuk dakwah dan kemaslahatan umat | A3 |
| 2 | Sub-CPMK073.2 | Menunjukkan komitmen mengintegrasikan nilai Islam-IPTEK dalam rencana studi akhir/karier TI | A4 |

---

#### `TIN4120` — Pemrograman Web Lanjut

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK06, BK05 (Aplikasi Berbasis Platform; Teknologi Platform)

**CPMK033 — Mengevaluasi solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK033.1 | Menganalisis arsitektur aplikasi web modern (SPA, komponen, state management) | C4 |
| 2 | Sub-CPMK033.2 | Menganalisis dan menerapkan framework front-end modern (React/Vue atau sejenis) untuk membangun antarmuka dinamis | C4 |
| 3 | Sub-CPMK033.3 | Mengevaluasi keamanan aplikasi web (XSS, CSRF, injection) menggunakan praktik OWASP terkini | C5 |
| 4 | Sub-CPMK033.4 | Mengevaluasi skalabilitas dan performa aplikasi web sebelum dan sesudah optimasi | C5 |

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis arsitektur RESTful API dan pertukaran data (JSON) | C4 |
| 2 | Sub-CPMK041.2 | Menganalisis dan menerapkan pengembangan API back-end untuk mendukung aplikasi web | C4 |
| 3 | Sub-CPMK041.3 | Mengintegrasikan front-end dan back-end melalui API mengikuti pola arsitektur modern (mis. JAMstack) | C6 |
| 4 | Sub-CPMK041.4 | Mengintegrasikan aplikasi web dengan platform cloud (PaaS) untuk deployment berkelanjutan (CI/CD) | C6 |

---

#### `TIN4121` — Pengantar Kecerdasan Buatan

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan (pengantar konsep, disinggung tren) &nbsp;·&nbsp; **Bahan Kajian:** BK21 (Kecerdasan Buatan)

**CPMK064 — Menjunjung etika data dalam praktik analitik dan AI** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK064.1 | Menganalisis konsep dasar dan sejarah perkembangan kecerdasan buatan, termasuk gelombang generative AI terkini | C4 |
| 2 | Sub-CPMK064.2 | Menganalisis isu etika data (bias, privasi) dalam pengembangan sistem AI | C4 |
| 3 | Sub-CPMK064.3 | Menganalisis kasus penerapan AI pada berbagai domain industri | C4 |
| 4 | Sub-CPMK064.4 | Menjunjung prinsip AI yang bertanggung jawab (responsible AI) dalam diskusi studi kasus | A3 |

---

#### `TIN4122` — Embedded Sistem

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK12, BK02 (Sistem Embedded; Internet of Things)

**CPMK013 — Menguasai fondasi teknologi informasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK013.1 | Menganalisis arsitektur mikrokontroler dan antarmuka hardware-software | C4 |
| 2 | Sub-CPMK013.2 | Menganalisis dan menerapkan pemrograman firmware dasar untuk mengendalikan sensor dan aktuator | C4 |
| 3 | Sub-CPMK013.3 | Menganalisis dan menerapkan sistem operasi real-time (RTOS) sederhana pada mikrokontroler | C4 |

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis protokol komunikasi machine-to-machine (MQTT, CoAP) untuk IoT | C4 |
| 2 | Sub-CPMK041.2 | Mengintegrasikan perangkat embedded dengan jaringan IoT mengikuti tren edge computing | C6 |
| 3 | Sub-CPMK041.3 | Mengintegrasikan sistem embedded dengan platform cloud IoT untuk pemantauan jarak jauh | C6 |

---

#### `TIN4123` — Data Mining

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK22, BK21 (Skalabilitas & Analitik Data; Kecerdasan Buatan)

**CPMK021 — Mengidentifikasi permasalahan computing yang kompleks** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK021.1 | Menganalisis proses knowledge discovery in databases (KDD) dan tahapan data mining | C4 |
| 2 | Sub-CPMK021.2 | Menganalisis kualitas dan kelengkapan data mentah untuk keperluan mining | C4 |
| 3 | Sub-CPMK021.3 | Menganalisis permasalahan bisnis yang dapat diselesaikan dengan teknik data mining (klasifikasi, klastering, asosiasi) | C4 |
| 4 | Sub-CPMK021.4 | Menganalisis peluang penerapan big data pipeline mengikuti tren data engineering modern | C4 |

**CPMK061 — Menerapkan teknik analitik data** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK061.1 | Menganalisis dan menerapkan teknik pra-pemrosesan data (cleaning, transformasi, normalisasi) | C4 |
| 2 | Sub-CPMK061.2 | Menganalisis dan menerapkan algoritma klasifikasi/klastering dasar (decision tree, k-means) pada dataset nyata | C4 |
| 3 | Sub-CPMK061.3 | Menganalisis dan menerapkan algoritma association rule mining (mis. Apriori) untuk menemukan pola data | C4 |
| 4 | Sub-CPMK061.4 | Menganalisis dan menerapkan visualisasi hasil data mining menggunakan tools BI modern untuk mendukung keputusan bisnis | C4 |

---

#### `TIN4124` — Sistem Informasi Kesehatan

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK25, BK09 (Informatika Kesehatan; Manajemen Data dan Informasi)

**CPMK033 — Mengevaluasi solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK033.1 | Menganalisis arsitektur sistem informasi kesehatan dan standar interoperabilitas (HL7/FHIR) | C4 |
| 2 | Sub-CPMK033.2 | Menganalisis dan menerapkan perancangan modul rekam medis elektronik sederhana | C4 |
| 3 | Sub-CPMK033.3 | Mengevaluasi keandalan dan keamanan sistem informasi kesehatan mengikuti standar integrasi SATUSEHAT | C5 |

**CPMK064 — Menjunjung etika data** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK064.1 | Menganalisis isu privasi dan kerahasiaan data pasien dalam sistem informasi kesehatan | C4 |
| 2 | Sub-CPMK064.2 | Menjunjung etika perlindungan data kesehatan sesuai regulasi (UU PDP) dalam perancangan sistem | A3 |
| 3 | Sub-CPMK064.3 | Menjunjung prinsip keadilan akses layanan kesehatan digital (telemedicine) bagi masyarakat | A4 |

---

#### `TIN4125` — Statistik

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK19 (Statistika dan Probabilitas)

**CPMK064 — Menjunjung etika data** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK064.1 | Menganalisis statistika deskriptif (ukuran pemusatan dan penyebaran data) | C4 |
| 2 | Sub-CPMK064.2 | Menganalisis dan menerapkan distribusi probabilitas dan uji hipotesis pada data sampel | C4 |
| 3 | Sub-CPMK064.3 | Menganalisis hubungan antar-variabel menggunakan regresi sederhana | C4 |
| 4 | Sub-CPMK064.4 | Menjunjung kejujuran dan objektivitas interpretasi statistik dalam pelaporan data | A3 |

---

#### `TIN4126` — Interaksi Manusia dan Komputer

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK11 (Desain User Experience)

**CPMK031 — Merancang solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK031.1 | Menganalisis prinsip interaksi manusia-komputer (HCI) dan heuristik usability | C4 |
| 2 | Sub-CPMK031.2 | Menganalisis dan menerapkan riset pengguna (user research) untuk menggali kebutuhan antarmuka | C4 |
| 3 | Sub-CPMK031.3 | Merancang prototipe antarmuka (wireframe/mockup) menggunakan tools desain modern (mis. Figma) | C6 |
| 4 | Sub-CPMK031.4 | Merancang antarmuka inklusif mengikuti tren design system pada aplikasi digital | C6 |

---

### SEMESTER 5

**Ringkasan mata kuliah semester ini:**

| Kode | Mata Kuliah | SKS | Kategori | CPMK | Sub-CPMK |
|------|-------------|:--:|----------|:--:|:--:|
| TIN5117 | Data Science | 4 | (C) | 2 | 8 |
| TIN5118 | Manajemen Informasi | 2 | (C) | 2 | 6 |
| TIN5119 | Paradigma Sistem | 2 | (C) | 1 | 4 |
| TIN5120 | Perancangan dan Integrasi Sistem | 2 | (C) | 2 | 6 |
| TIN5121 | Metodologi Penelitian | 2 | (A) | 1 | 4 |
| TIN5123 | Analitik Data | 2 | (C) | 1 | 4 |
| TIN5245 | Sistem Basis Data Lanjut | 4 | (C) | 2 | 8 |
| TIN5246 | Kecerdasan Buatan | 4 | (C) | 2 | 8 |
| TIN5247 | Multimedia | 4 | (C) | 2 | 8 |
| TIN5248 | Jaringan Komputer 2 | 4 | (C) | 3 | 9 |
| TIN5249 | Infomatika Medis | 2 | (C) | 1 | 4 |

#### `TIN5117` — Data Science

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK22, BK21 (Skalabilitas & Analitik Data; Kecerdasan Buatan)

**CPMK021 — Mengidentifikasi permasalahan computing yang kompleks** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK021.1 | Menganalisis siklus hidup proyek data science (CRISP-DM) | C4 |
| 2 | Sub-CPMK021.2 | Menganalisis sumber dan kualitas data untuk proyek data science | C4 |
| 3 | Sub-CPMK021.3 | Menganalisis permasalahan bisnis yang dapat dipecahkan dengan pendekatan data science | C4 |
| 4 | Sub-CPMK021.4 | Menganalisis kebutuhan infrastruktur big data (data lake/warehouse cloud) mengikuti tren industri | C4 |

**CPMK061 — Menerapkan teknik analitik data** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK061.1 | Menganalisis pola data melalui eksplorasi (EDA) dan visualisasi | C4 |
| 2 | Sub-CPMK061.2 | Menganalisis dan menerapkan teknik feature engineering untuk mempersiapkan data model prediktif | C4 |
| 3 | Sub-CPMK061.3 | Menganalisis dan menerapkan model prediktif dasar (regresi/klasifikasi) menggunakan pustaka data science modern | C4 |
| 4 | Sub-CPMK061.4 | Menganalisis dan menerapkan evaluasi model dan komunikasi hasil data science kepada pemangku kepentingan | C4 |

---

#### `TIN5118` — Manajemen Informasi

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK09, BK18 (Manajemen Data dan Informasi; Manajemen Sistem Informasi)

**CPMK053 — Menerapkan tata kelola informasi** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK053.1 | Menganalisis konsep manajemen informasi sebagai aset strategis organisasi | C4 |
| 2 | Sub-CPMK053.2 | Menganalisis dan menerapkan tata kelola informasi (data governance) mengikuti standar dan regulasi (UU PDP) terkini | C4 |
| 3 | Sub-CPMK053.3 | Menganalisis dan menerapkan arsitektur data warehouse sederhana untuk mendukung pelaporan organisasi | C4 |

**CPMK064 — Menjunjung etika data** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK064.1 | Menganalisis prinsip etika dan kepatuhan (compliance) dalam pengelolaan informasi | C4 |
| 2 | Sub-CPMK064.2 | Menjunjung prinsip transparansi dan akuntabilitas dalam pengelolaan informasi organisasi | A3 |
| 3 | Sub-CPMK064.3 | Menjunjung praktik keamanan informasi mengikuti tren cloud data governance | A4 |

---

#### `TIN5119` — Paradigma Sistem

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK17 (Analisis dan Pemodelan Sistem)

**CPMK031 — Merancang solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK031.1 | Menganalisis paradigma pengembangan sistem (terstruktur, berorientasi objek, agile) | C4 |
| 2 | Sub-CPMK031.2 | Menganalisis dan menerapkan pemodelan proses bisnis (BPMN) untuk suatu organisasi | C4 |
| 3 | Sub-CPMK031.3 | Merancang arsitektur sistem informasi sesuai kebutuhan organisasi | C6 |
| 4 | Sub-CPMK031.4 | Merancang solusi sistem mengikuti paradigma arsitektur modern (microservices, event-driven) | C6 |

---

#### `TIN5120` — Perancangan dan Integrasi Sistem

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK04, BK17 (Teknologi Sistem Terintegrasi; Analisis dan Pemodelan Sistem)

**CPMK031 — Merancang solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK031.1 | Menganalisis prinsip requirements engineering dan pemodelan UML untuk perancangan sistem | C4 |
| 2 | Sub-CPMK031.2 | Merancang arsitektur sistem informasi terintegrasi untuk studi kasus organisasi | C6 |
| 3 | Sub-CPMK031.3 | Merancang antarmuka integrasi (API/middleware) mengikuti pola arsitektur berorientasi layanan (SOA) | C6 |

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis konsep middleware dan microservices dalam integrasi sistem heterogen | C4 |
| 2 | Sub-CPMK041.2 | Mengintegrasikan beberapa sistem/modul aplikasi menggunakan API | C6 |
| 3 | Sub-CPMK041.3 | Mengintegrasikan sistem terdistribusi mengikuti tren container orchestration (Docker/Kubernetes) | C6 |

---

#### `TIN5121` — Metodologi Penelitian

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (A) Teori Dasar &nbsp;·&nbsp; **Bahan Kajian:** BK24 (Metodologi Penelitian TI)

**CPMK032 — Mengimplementasikan solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK032.1 | Menganalisis jenis dan desain penelitian (kuantitatif, kualitatif, R&D) bidang TI | C4 |
| 2 | Sub-CPMK032.2 | Menganalisis dan menerapkan teknik kajian literatur dan perumusan masalah penelitian | C4 |
| 3 | Sub-CPMK032.3 | Menganalisis data penelitian menggunakan metode pengumpulan yang sesuai | C4 |
| 4 | Sub-CPMK032.4 | Mengembangkan penulisan proposal penelitian sesuai kaidah ilmiah | C6 |

---

#### `TIN5123` — Analitik Data

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK22 (Skalabilitas dan Analitik Data)

**CPMK013 — Menguasai fondasi teknologi informasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK013.1 | Menganalisis fondasi teknis platform analitik data (arsitektur data pipeline) | C4 |
| 2 | Sub-CPMK013.2 | Menganalisis komponen infrastruktur big data (batch vs streaming processing) | C4 |
| 3 | Sub-CPMK013.3 | Menganalisis dan menerapkan tools analitik data modern (dashboard BI) untuk mengolah dataset skala menengah | C4 |
| 4 | Sub-CPMK013.4 | Menganalisis dan menerapkan praktik analitik data real-time mengikuti tren streaming analytics industri | C4 |

---

#### `TIN5245` — Sistem Basis Data Lanjut

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK09 (Manajemen Data dan Informasi)

**CPMK053 — Menerapkan tata kelola informasi** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK053.1 | Menganalisis konsep basis data lanjut (NoSQL, basis data terdistribusi) | C4 |
| 2 | Sub-CPMK053.2 | Menganalisis dan menerapkan tata kelola data pada basis data terdistribusi/cloud (replikasi, sharding) | C4 |
| 3 | Sub-CPMK053.3 | Menganalisis dan menerapkan transaksi dan concurrency control untuk menjaga konsistensi data | C4 |
| 4 | Sub-CPMK053.4 | Menganalisis dan menerapkan strategi backup dan recovery basis data mengikuti praktik cloud database terkini | C4 |

**CPMK061 — Menerapkan teknik analitik data** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK061.1 | Menganalisis dan menerapkan query lanjut (stored procedure, trigger, view) untuk analitik data | C4 |
| 2 | Sub-CPMK061.2 | Menganalisis dan menerapkan optimasi performa basis data skala besar (indexing lanjut, partitioning) | C4 |
| 3 | Sub-CPMK061.3 | Menganalisis dan menerapkan integrasi basis data dengan data warehouse/BI tools | C4 |
| 4 | Sub-CPMK061.4 | Menganalisis dan menerapkan basis data NoSQL (dokumen/key-value) untuk kasus big data mengikuti tren industri | C4 |

---

#### `TIN5246` — Kecerdasan Buatan

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK21 (Kecerdasan Buatan)

**CPMK021 — Mengidentifikasi permasalahan computing yang kompleks** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK021.1 | Menganalisis taksonomi teknik AI (machine learning, deep learning, NLP, computer vision) | C4 |
| 2 | Sub-CPMK021.2 | Menganalisis permasalahan yang cocok diselesaikan dengan pendekatan supervised/unsupervised learning | C4 |
| 3 | Sub-CPMK021.3 | Menganalisis kebutuhan data dan komputasi untuk melatih model AI | C4 |
| 4 | Sub-CPMK021.4 | Menganalisis peluang penerapan generative AI/LLM pada studi kasus industri terkini | C4 |

**CPMK062 — Menerapkan machine learning dan kecerdasan buatan untuk membangun model** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK062.1 | Menganalisis dan menerapkan algoritma machine learning dasar (regresi, klasifikasi, klastering) | C4 |
| 2 | Sub-CPMK062.2 | Menganalisis dan menerapkan jaringan syaraf tiruan (neural network) dasar untuk membangun model prediktif | C4 |
| 3 | Sub-CPMK062.3 | Menganalisis dan menerapkan evaluasi dan tuning model AI (hyperparameter, cross-validation) | C4 |
| 4 | Sub-CPMK062.4 | Menganalisis dan menerapkan praktik MLOps dasar untuk deployment model AI mengikuti tren industri | C4 |

---

#### `TIN5247` — Multimedia

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK20 (Komputasi Grafis dan Multimedia)

**CPMK033 — Mengevaluasi solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK033.1 | Menganalisis prinsip pengolahan citra, audio, dan video digital | C4 |
| 2 | Sub-CPMK033.2 | Menganalisis dan menerapkan teknik kompresi dan format multimedia standar industri | C4 |
| 3 | Sub-CPMK033.3 | Mengevaluasi kualitas produk multimedia (resolusi, ukuran berkas, pengalaman pengguna) | C5 |
| 4 | Sub-CPMK033.4 | Mengevaluasi efektivitas konten multimedia interaktif mengikuti tren AR/VR dan konten immersive | C5 |

**CPMK062 — Menerapkan machine learning dan kecerdasan buatan untuk membangun model** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK062.1 | Menganalisis penerapan kecerdasan buatan pada pengolahan multimedia (computer vision dasar) | C4 |
| 2 | Sub-CPMK062.2 | Menganalisis dan menerapkan teknik pengenalan pola sederhana pada citra/audio | C4 |
| 3 | Sub-CPMK062.3 | Menganalisis dan menerapkan tools generative AI untuk produksi konten multimedia mengikuti tren industri kreatif | C4 |
| 4 | Sub-CPMK062.4 | Menganalisis dan menerapkan integrasi elemen multimedia interaktif ke dalam aplikasi/website | C4 |

---

#### `TIN5248` — Jaringan Komputer 2

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK03 (Jaringan Komputer)

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis teknologi jaringan lanjut (VLAN, routing dinamis, WAN) | C4 |
| 2 | Sub-CPMK041.2 | Menganalisis dan menerapkan konfigurasi routing dinamis dan VLAN pada jaringan skala menengah | C4 |
| 3 | Sub-CPMK041.3 | Mengintegrasikan jaringan enterprise dengan teknologi SD-WAN mengikuti tren jaringan modern | C6 |

**CPMK051 — Menerapkan prinsip-prinsip keamanan siber** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK051.1 | Menganalisis arsitektur keamanan jaringan lanjut (IDS/IPS, VPN) | C4 |
| 2 | Sub-CPMK051.2 | Menganalisis dan menerapkan konfigurasi VPN dan segmentasi jaringan untuk keamanan berlapis | C4 |
| 3 | Sub-CPMK051.3 | Menganalisis dan menerapkan prinsip zero-trust network access (ZTNA) pada rancangan jaringan enterprise | C4 |

**CPMK053 — Menerapkan tata kelola informasi** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK053.1 | Menganalisis praktik monitoring dan manajemen kinerja jaringan skala besar | C4 |
| 2 | Sub-CPMK053.2 | Menganalisis dan menerapkan dokumentasi dan tata kelola infrastruktur jaringan sesuai standar | C4 |
| 3 | Sub-CPMK053.3 | Menganalisis dan menerapkan automasi konfigurasi jaringan (network automation) mengikuti tren infrastructure-as-code | C4 |

---

#### `TIN5249` — Infomatika Medis

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK25 (Informatika Kesehatan)

**CPMK052 — Menerapkan manajemen risiko dalam sistem informasi terdistribusi** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK052.1 | Menganalisis konsep manajemen risiko pada sistem informasi kesehatan | C4 |
| 2 | Sub-CPMK052.2 | Menganalisis dan menerapkan identifikasi risiko keamanan data medis (kebocoran, akses ilegal) | C4 |
| 3 | Sub-CPMK052.3 | Menganalisis dan menerapkan strategi mitigasi risiko sistem informasi kesehatan terdistribusi | C4 |
| 4 | Sub-CPMK052.4 | Menganalisis dan menerapkan praktik manajemen risiko mengikuti standar interoperabilitas kesehatan digital nasional (SATUSEHAT) | C4 |

---

### SEMESTER 6

**Ringkasan mata kuliah semester ini:**

| Kode | Mata Kuliah | SKS | Kategori | CPMK | Sub-CPMK |
|------|-------------|:--:|----------|:--:|:--:|
| TIN6130 | Teknologi Sistem Terintegrasi | 2 | (C) | 1 | 4 |
| TIN6131 | Teknologi Platform | 2 | (C) | 2 | 6 |
| TIN6132 | Praktek Professional Global | 2 | (C) | 1 | 4 |
| TIN6133 | Prinsip Keamanan Siber | 2 | (C) | 1 | 4 |
| TIN6134 | Capstone Project 1 | 2 | (C) | 2 | 6 |
| TIN6250 | Business Problem & DS Solution | 4 | (C) | 2 | 8 |
| TIN6251 | Riset Operasi | 4 | (C) | 2 | 8 |
| TIN6252 | Internet of Things | 4 | (C) | 2 | 8 |
| TIN6254 | Sistem dan Layanan Virtual | 2 | (C) | 2 | 6 |

#### `TIN6130` — Teknologi Sistem Terintegrasi

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK04 (Teknologi Sistem Terintegrasi)

**CPMK032 — Mengimplementasikan solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK032.1 | Menganalisis konsep middleware dan integrasi sistem heterogen | C4 |
| 2 | Sub-CPMK032.2 | Mengembangkan integrasi antar-aplikasi menggunakan API/message broker | C6 |
| 3 | Sub-CPMK032.3 | Mengembangkan arsitektur microservices sederhana untuk sistem terintegrasi | C6 |
| 4 | Sub-CPMK032.4 | Mengembangkan orkestrasi layanan mengikuti tren cloud-native integration | C6 |

---

#### `TIN6131` — Teknologi Platform

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK05, BK01 (Teknologi Platform; Virtual Systems and Services)

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis jenis-jenis platform komputasi (cloud, mobile, PaaS, SaaS) | C4 |
| 2 | Sub-CPMK041.2 | Mengintegrasikan aplikasi dengan layanan platform cloud (IaaS/PaaS) | C6 |
| 3 | Sub-CPMK041.3 | Mengintegrasikan platform containerization (Docker) mengikuti tren cloud-native | C6 |

**CPMK052 — Menerapkan manajemen risiko dalam sistem informasi terdistribusi** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK052.1 | Menganalisis risiko keamanan dan ketergantungan (vendor lock-in) pada platform cloud | C4 |
| 2 | Sub-CPMK052.2 | Menganalisis dan menerapkan strategi manajemen risiko pemilihan dan migrasi platform | C4 |
| 3 | Sub-CPMK052.3 | Menganalisis dan menerapkan praktik manajemen biaya dan skalabilitas platform (cost optimization) mengikuti tren FinOps | C4 |

---

#### `TIN6132` — Praktek Professional Global

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK08 (Praktek Profesional Global)

**CPMK032 — Mengimplementasikan solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK032.1 | Menganalisis etika profesi dan standar sertifikasi TI internasional | C4 |
| 2 | Sub-CPMK032.2 | Mengembangkan praktik kerja tim lintas budaya dalam proyek TI global | C6 |
| 3 | Sub-CPMK032.3 | Mengembangkan komunikasi teknis profesional (laporan, presentasi) sesuai standar internasional | C6 |
| 4 | Sub-CPMK032.4 | Mengembangkan praktik kerja remote/kolaborasi global mengikuti tren distributed team industri TI | C6 |

---

#### `TIN6133` — Prinsip Keamanan Siber

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK07 (Prinsip-prinsip Keamanan Siber)

**CPMK052 — Menerapkan manajemen risiko dalam sistem informasi terdistribusi** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK052.1 | Menganalisis prinsip dasar kriptografi dan keamanan jaringan | C4 |
| 2 | Sub-CPMK052.2 | Menganalisis dan menerapkan penilaian kerentanan (vulnerability assessment) pada sistem sederhana | C4 |
| 3 | Sub-CPMK052.3 | Menganalisis dan menerapkan teknik ethical hacking dasar untuk menguji celah keamanan | C4 |
| 4 | Sub-CPMK052.4 | Menganalisis dan menerapkan manajemen risiko keamanan siber mengikuti tren ancaman ransomware dan AI-driven attack | C4 |

---

#### `TIN6134` — Capstone Project 1

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK27, BK13 (Metode Penelitian & Pengembangan; Manajemen Proyek TI)

**CPMK013 — Menguasai fondasi teknologi informasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK013.1 | Menganalisis fondasi teknis yang relevan untuk topik proyek capstone yang dipilih | C4 |
| 2 | Sub-CPMK013.2 | Menganalisis dan menerapkan studi kelayakan teknis (feasibility study) terhadap ide proyek capstone | C4 |
| 3 | Sub-CPMK013.3 | Menganalisis dan menerapkan identifikasi kebutuhan dan lingkup proyek sesuai kaidah manajemen proyek Agile | C4 |

**CPMK031 — Merancang solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK031.1 | Merancang proposal solusi/produk capstone berdasarkan kebutuhan pengguna/industri | C6 |
| 2 | Sub-CPMK031.2 | Merancang arsitektur teknis dan rencana kerja proyek capstone | C6 |
| 3 | Sub-CPMK031.3 | Merancang purwarupa (prototype) awal proyek capstone mengikuti tren rapid prototyping | C6 |

---

#### `TIN6250` — Business Problem & DS Solution

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK22, BK13 (Skalabilitas & Analitik Data; Manajemen Proyek TI)

**CPMK021 — Mengidentifikasi permasalahan computing yang kompleks** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK021.1 | Menganalisis kerangka kerja penyelarasan masalah bisnis dengan solusi data science | C4 |
| 2 | Sub-CPMK021.2 | Menganalisis permasalahan bisnis strategis yang berpotensi diselesaikan dengan data science | C4 |
| 3 | Sub-CPMK021.3 | Menganalisis metrik keberhasilan (KPI) solusi data science bagi organisasi | C4 |
| 4 | Sub-CPMK021.4 | Menganalisis peluang penerapan AI generatif untuk otomasi proses bisnis mengikuti tren industri | C4 |

**CPMK062 — Menerapkan machine learning dan kecerdasan buatan untuk membangun model** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK062.1 | Menganalisis dan menerapkan pemodelan prediktif untuk menjawab permasalahan bisnis nyata | C4 |
| 2 | Sub-CPMK062.2 | Menganalisis cost-benefit solusi data science bagi organisasi | C4 |
| 3 | Sub-CPMK062.3 | Menganalisis dan menerapkan komunikasi hasil model AI kepada pengambil keputusan bisnis (storytelling data) | C4 |
| 4 | Sub-CPMK062.4 | Menganalisis dan menerapkan strategi implementasi solusi data science skala organisasi mengikuti tren MLOps/AI governance | C4 |

---

#### `TIN6251` — Riset Operasi

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK19, BK23 (Statistika & Probabilitas; Matematika Terapan)

**CPMK022 — Menganalisis permasalahan computing kompleks** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK022.1 | Menganalisis konsep dasar pemodelan matematis untuk optimasi (linear programming) | C4 |
| 2 | Sub-CPMK022.2 | Menganalisis permasalahan optimasi sumber daya menggunakan model matematis | C4 |
| 3 | Sub-CPMK022.3 | Menganalisis permasalahan transportasi dan penugasan menggunakan metode riset operasi | C4 |
| 4 | Sub-CPMK022.4 | Menganalisis permasalahan antrian dan simulasi sistem menggunakan pendekatan kuantitatif | C4 |

**CPMK062 — Menerapkan machine learning dan kecerdasan buatan untuk membangun model** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK062.1 | Menganalisis dan menerapkan algoritma optimasi (simpleks, heuristik) untuk memecahkan model riset operasi | C4 |
| 2 | Sub-CPMK062.2 | Menganalisis dan menerapkan tools perangkat lunak optimasi/solver untuk menyelesaikan studi kasus | C4 |
| 3 | Sub-CPMK062.3 | Menganalisis dan menerapkan pendekatan machine learning untuk mendukung pengambilan keputusan optimasi (prescriptive analytics) | C4 |
| 4 | Sub-CPMK062.4 | Menganalisis dan menerapkan interpretasi hasil optimasi untuk rekomendasi keputusan bisnis mengikuti praktik decision intelligence industri | C4 |

---

#### `TIN6252` — Internet of Things

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK02, BK12 (Internet of Things; Sistem Embedded)

**CPMK032 — Mengimplementasikan solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK032.1 | Menganalisis arsitektur sistem IoT (perception, network, application layer) | C4 |
| 2 | Sub-CPMK032.2 | Mengembangkan program firmware untuk sensor dan aktuator IoT | C6 |
| 3 | Sub-CPMK032.3 | Mengembangkan komunikasi protokol M2M (MQTT/CoAP) pada perangkat IoT | C6 |
| 4 | Sub-CPMK032.4 | Mengembangkan aplikasi dashboard monitoring IoT berbasis cloud | C6 |

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis integrasi infrastruktur jaringan untuk mendukung skala besar perangkat IoT | C4 |
| 2 | Sub-CPMK041.2 | Mengintegrasikan perangkat IoT dengan platform edge computing | C6 |
| 3 | Sub-CPMK041.3 | Mengintegrasikan sistem IoT dengan layanan cloud/analitik data untuk pengambilan keputusan | C6 |
| 4 | Sub-CPMK041.4 | Mengintegrasikan solusi IoT mengikuti tren Industry 4.0/smart city terkini | C6 |

---

#### `TIN6254` — Sistem dan Layanan Virtual

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK01, BK07 (Virtual Systems and Services; Prinsip Keamanan Siber)

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis konsep virtualisasi server, jaringan, dan komputasi awan | C4 |
| 2 | Sub-CPMK041.2 | Mengintegrasikan layanan virtual (virtual machine/container) ke dalam infrastruktur organisasi | C6 |
| 3 | Sub-CPMK041.3 | Mengintegrasikan layanan cloud-native (containerization Docker/Kubernetes) mengikuti tren industri | C6 |

**CPMK052 — Menerapkan manajemen risiko dalam sistem informasi terdistribusi** *(CPL05)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK052.1 | Menganalisis risiko keamanan pada layanan virtual dan cloud | C4 |
| 2 | Sub-CPMK052.2 | Menganalisis dan menerapkan manajemen risiko keamanan layanan cloud (kontrol akses, enkripsi data) | C4 |
| 3 | Sub-CPMK052.3 | Menganalisis dan menerapkan strategi mitigasi risiko cloud mengikuti prinsip shared responsibility model penyedia cloud terkini | C4 |

---

### SEMESTER 7

**Ringkasan mata kuliah semester ini:**

| Kode | Mata Kuliah | SKS | Kategori | CPMK | Sub-CPMK |
|------|-------------|:--:|----------|:--:|:--:|
| TIN6253 | Aplikasi Seluler (Mobile) | 4 | (C) | 2 | 8 |
| TIN7138 | Sistem Web dan Seluler (Mobile) | 4 | (C) | 2 | 8 |
| TIN7140 | Design User Experience | 2 | (C) | 1 | 4 |
| TIN7141 | Capstone Project 2 | 2 | (C) | 2 | 6 |
| TIN7257 | E-Health | 4 | (C) | 2 | 8 |
| TIN7260 | Magang/Praktik Kerja | 4 | (C) | 3 | 9 |
| TIN7261 | Kuliah Kerja Nyata (KKN) | 4 | (C) | 2 | 8 |
| TIN8142 | Seminar Proposal | 1 | (C) | 1 | 3 |

#### `TIN6253` — Aplikasi Seluler (Mobile)

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK06, BK05 (Aplikasi Berbasis Platform; Teknologi Platform)

**CPMK032 — Mengimplementasikan solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK032.1 | Menganalisis arsitektur pengembangan aplikasi mobile (native vs cross-platform) | C4 |
| 2 | Sub-CPMK032.2 | Mengembangkan antarmuka aplikasi mobile menggunakan framework cross-platform (Flutter/React Native) | C6 |
| 3 | Sub-CPMK032.3 | Mengembangkan fitur penyimpanan data lokal dan sinkronisasi pada aplikasi mobile | C6 |
| 4 | Sub-CPMK032.4 | Mengembangkan fitur notifikasi push dan integrasi sensor perangkat mobile | C6 |

**CPMK041 — Mengintegrasikan infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK041.1 | Menganalisis arsitektur backend-as-a-service untuk aplikasi mobile | C4 |
| 2 | Sub-CPMK041.2 | Mengintegrasikan aplikasi mobile dengan RESTful API/backend cloud | C6 |
| 3 | Sub-CPMK041.3 | Mengintegrasikan aplikasi mobile dengan layanan autentikasi dan pembayaran digital | C6 |
| 4 | Sub-CPMK041.4 | Mengintegrasikan proses rilis aplikasi mobile ke app store mengikuti praktik CI/CD mobile modern | C6 |

---

#### `TIN7138` — Sistem Web dan Seluler (Mobile)

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK06, BK05 (Aplikasi Berbasis Platform; Teknologi Platform)

**CPMK032 — Mengimplementasikan solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK032.1 | Menganalisis arsitektur sistem terpadu web dan mobile (shared backend) | C4 |
| 2 | Sub-CPMK032.2 | Mengembangkan progressive web app (PWA) yang responsif lintas perangkat | C6 |
| 3 | Sub-CPMK032.3 | Mengembangkan sinkronisasi data real-time antara aplikasi web dan mobile | C6 |
| 4 | Sub-CPMK032.4 | Mengembangkan fitur keamanan autentikasi terpadu (SSO) pada sistem web-mobile | C6 |

**CPMK042 — Mengkonfigurasi infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK042.1 | Menganalisis konfigurasi server dan environment untuk sistem web-mobile terpadu | C4 |
| 2 | Sub-CPMK042.2 | Menganalisis kebutuhan dan mengkonfigurasi deployment container (Docker) untuk sistem web dan mobile backend | C4 |
| 3 | Sub-CPMK042.3 | Menganalisis kebutuhan dan mengkonfigurasi monitoring dan logging sistem mengikuti praktik observability modern | C4 |
| 4 | Sub-CPMK042.4 | Menganalisis kebutuhan dan mengkonfigurasi pipeline CI/CD untuk rilis berkelanjutan sistem web-mobile | C4 |

---

#### `TIN7140` — Design User Experience

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK11 (Desain User Experience)

**CPMK032 — Mengimplementasikan solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK032.1 | Menganalisis proses design thinking lanjutan (empathize–define–ideate–prototype–test) | C4 |
| 2 | Sub-CPMK032.2 | Mengembangkan wireframe menjadi purwarupa interaktif (high-fidelity prototype) | C6 |
| 3 | Sub-CPMK032.3 | Mengembangkan pengujian usability dengan pengguna nyata dan mengolah umpan balik | C6 |
| 4 | Sub-CPMK032.4 | Mengembangkan design system yang konsisten mengikuti tren UX industri terkini | C6 |

---

#### `TIN7141` — Capstone Project 2

**SKS:** 2 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK27, BK13 (Metode Penelitian & Pengembangan; Manajemen Proyek TI)

**CPMK013 — Menguasai fondasi teknologi informasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK013.1 | Menganalisis penyempurnaan fondasi teknis lanjutan berdasarkan hasil Capstone Project 1 | C4 |
| 2 | Sub-CPMK013.2 | Menganalisis dan menerapkan pengembangan lanjutan solusi capstone sesuai rencana kerja proyek | C4 |
| 3 | Sub-CPMK013.3 | Menganalisis dan menerapkan integrasi seluruh modul proyek capstone menjadi produk yang utuh | C4 |

**CPMK033 — Mengevaluasi solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK033.1 | Mengevaluasi keandalan dan keamanan produk capstone melalui pengujian sistem | C5 |
| 2 | Sub-CPMK033.2 | Mengevaluasi efisiensi dan performa produk capstone dibanding target awal proyek | C5 |
| 3 | Sub-CPMK033.3 | Mengevaluasi kesiapan produk capstone untuk dipublikasikan/dipresentasikan mengikuti standar industri | C5 |

---

#### `TIN7257` — E-Health

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK25, BK09 (Informatika Kesehatan; Manajemen Data dan Informasi)

**CPMK022 — Menganalisis permasalahan computing kompleks** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK022.1 | Menganalisis ekosistem layanan kesehatan digital (telemedicine, mHealth) | C4 |
| 2 | Sub-CPMK022.2 | Menganalisis kebutuhan sistem e-health untuk fasilitas pelayanan kesehatan | C4 |
| 3 | Sub-CPMK022.3 | Menganalisis interoperabilitas data kesehatan lintas sistem mengikuti standar SATUSEHAT/HL7-FHIR | C4 |
| 4 | Sub-CPMK022.4 | Menganalisis risiko privasi dan keamanan pada layanan e-health mengikuti regulasi terkini | C4 |

**CPMK063 — Menghasilkan wawasan berbasis data yang mendukung pengambilan keputusan** *(CPL06)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK063.1 | Menganalisis dan menerapkan analitik data kesehatan untuk mendukung pengambilan keputusan klinis | C4 |
| 2 | Sub-CPMK063.2 | Menganalisis dan menerapkan visualisasi dashboard data kesehatan bagi tenaga medis/manajemen | C4 |
| 3 | Sub-CPMK063.3 | Menghasilkan rekomendasi berbasis data untuk peningkatan layanan e-health | C6 |
| 4 | Sub-CPMK063.4 | Menghasilkan prototipe solusi e-health mengikuti tren AI-assisted diagnosis/telemedicine | C6 |

---

#### `TIN7260` — Magang/Praktik Kerja

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK08, BK13 (Praktek Profesional Global; Manajemen Proyek TI)

**CPMK022 — Menganalisis permasalahan computing kompleks** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK022.1 | Menganalisis permasalahan nyata di tempat magang yang relevan dengan bidang TI | C4 |
| 2 | Sub-CPMK022.2 | Menganalisis proses bisnis/teknis di lingkungan kerja industri mitra | C4 |
| 3 | Sub-CPMK022.3 | Menganalisis kebutuhan solusi TI berdasarkan permasalahan nyata di industri | C4 |

**CPMK032 — Mengimplementasikan solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK032.1 | Mengembangkan tugas/proyek teknis sesuai penugasan di tempat magang | C6 |
| 2 | Sub-CPMK032.2 | Mengembangkan praktik kerja profesional (etika kerja, kolaborasi tim industri) | C6 |
| 3 | Sub-CPMK032.3 | Mengembangkan solusi/produk kerja mengikuti standar dan tools industri terkini | C6 |

**CPMK042 — Mengkonfigurasi infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK042.1 | Menganalisis kebutuhan dan mengkonfigurasi lingkungan kerja teknis (development environment) sesuai standar perusahaan mitra | C4 |
| 2 | Sub-CPMK042.2 | Menganalisis kebutuhan, mengkonfigurasi, dan mengoperasikan sistem/infrastruktur TI di tempat magang | C4 |
| 3 | Sub-CPMK042.3 | Menyusun laporan hasil magang yang mendokumentasikan capaian teknis dan profesional | C6 |

---

#### `TIN7261` — Kuliah Kerja Nyata (KKN)

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK08 (Praktek Profesional Global)

**CPMK022 — Menganalisis permasalahan computing kompleks** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK022.1 | Menganalisis permasalahan digitalisasi/TI di lingkungan masyarakat lokasi KKN | C4 |
| 2 | Sub-CPMK022.2 | Menganalisis kebutuhan pemberdayaan masyarakat berbasis teknologi tepat guna | C4 |
| 3 | Sub-CPMK022.3 | Menganalisis potensi solusi digital untuk UMKM/desa mengikuti tren digitalisasi desa | C4 |
| 4 | Sub-CPMK022.4 | Menganalisis dampak sosial dari solusi TI yang diusulkan bagi masyarakat | C4 |

**CPMK042 — Mengkonfigurasi infrastruktur teknologi informasi** *(CPL04)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK042.1 | Menganalisis kebutuhan dan mengkonfigurasi/menerapkan solusi TI sederhana (website desa, sistem pencatatan digital) bagi masyarakat | C4 |
| 2 | Sub-CPMK042.2 | Mengevaluasi dan mengadministrasikan pelatihan literasi digital bagi masyarakat sasaran | C5 |
| 3 | Sub-CPMK042.3 | Menganalisis kebutuhan dan mengkonfigurasi pendampingan pemanfaatan platform digital UMKM (e-commerce, media sosial bisnis) | C4 |
| 4 | Sub-CPMK042.4 | Menyusun laporan pengabdian yang mendokumentasikan hasil dan dampak program KKN | C6 |

---

#### `TIN8142` — Seminar Proposal

**SKS:** 1 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK24, BK27 (Metodologi Penelitian TI; Metode Penelitian & Pengembangan)

**CPMK014 — Menganalisis dan memecahkan permasalahan computing kompleks** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK014.1 | Menganalisis permasalahan penelitian/skripsi bidang TI yang layak dan relevan dengan tren industri | C4 |
| 2 | Sub-CPMK014.2 | Menganalisis kesesuaian metodologi penelitian dengan rumusan masalah yang diajukan | C4 |
| 3 | Sub-CPMK014.3 | Mengevaluasi dan mempertahankan proposal penelitian di hadapan tim penguji | C5 |

---

### SEMESTER 8

**Ringkasan mata kuliah semester ini:**

| Kode | Mata Kuliah | SKS | Kategori | CPMK | Sub-CPMK |
|------|-------------|:--:|----------|:--:|:--:|
| TIN8143 | Seminar Hasil | 1 | (C) | 1 | 3 |
| TIN8144 | Skripsi | 4 | (C) | 3 | 9 |

#### `TIN8143` — Seminar Hasil

**SKS:** 1 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK27 (Metode Penelitian dan Pengembangan)

**CPMK014 — Menganalisis dan memecahkan permasalahan computing kompleks** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK014.1 | Menganalisis kesesuaian hasil penelitian/skripsi dengan tujuan dan metodologi yang direncanakan | C4 |
| 2 | Sub-CPMK014.2 | Memecahkan kendala/temuan tak terduga selama pelaksanaan penelitian dengan solusi yang tepat | C4 |
| 3 | Sub-CPMK014.3 | Mengevaluasi dan mempertahankan hasil penelitian/skripsi di hadapan tim penguji | C5 |

---

#### `TIN8144` — Skripsi

**SKS:** 4 &nbsp;·&nbsp; **Kategori:** (C) Terapan &nbsp;·&nbsp; **Bahan Kajian:** BK27 (Metode Penelitian dan Pengembangan)

**CPMK011 — Menguasai konsep matematika yang relevan untuk komputasi** *(CPL01)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK011.1 | Menganalisis data penelitian skripsi menggunakan penalaran matematis/kuantitatif yang relevan | C4 |
| 2 | Sub-CPMK011.2 | Menganalisis dan menerapkan model/perhitungan yang menjadi dasar teknis pemecahan masalah pada skripsi | C4 |
| 3 | Sub-CPMK011.3 | Menganalisis dan menerapkan validasi kuantitatif terhadap hasil rancangan/model skripsi | C4 |

**CPMK023 — Mendefinisikan permasalahan computing kompleks berdasarkan pengetahuan domain yang relevan** *(CPL02)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK023.1 | Mendefinisikan rumusan masalah penelitian skripsi berdasarkan domain TI yang dipilih | C4 |
| 2 | Sub-CPMK023.2 | Mendefinisikan batasan dan ruang lingkup penelitian skripsi secara jelas dan terukur | C4 |
| 3 | Sub-CPMK023.3 | Mendefinisikan kontribusi keilmuan/praktis penelitian skripsi sesuai kebutuhan/tren industri terkini | C4 |

**CPMK033 — Mengevaluasi solusi berbasis computing** *(CPL03)*

| No | Kode Sub-CPMK | Deskripsi | Level |
|:--:|---------------|-----------|:--:|
| 1 | Sub-CPMK033.1 | Mengevaluasi keandalan solusi/sistem yang dikembangkan dalam skripsi | C5 |
| 2 | Sub-CPMK033.2 | Mengevaluasi keamanan dan efisiensi solusi yang dikembangkan dalam skripsi | C5 |
| 3 | Sub-CPMK033.3 | Mengevaluasi kontribusi hasil skripsi terhadap penyelesaian masalah computing yang diangkat | C5 |

---

## 4. Ringkasan Statistik

| Metrik | Nilai |
|--------|-------|
| Total mata kuliah dipetakan | 65 dari 65 ✅ |
| Total Sub-CPMK dihasilkan | **396** |
| MK 1 SKS (3 Sub-CPMK/MK, ekstrapolasi §2.1) | 2 MK (Seminar Proposal, Seminar Hasil) — 6 Sub-CPMK |
| MK 2 SKS (rentang 4–8 Sub-CPMK) | 33 MK — 174 Sub-CPMK |
| MK 4 SKS (rentang 6–10 Sub-CPMK) | 30 MK — 216 Sub-CPMK |
| Rata-rata Sub-CPMK per MK | 6,1 |
| MK Kategori (A) Teori Dasar | 16 MK |
| MK Kategori (B) Wajib Umum/Karakter | 10 MK |
| MK Kategori (C) Terapan/Industri | 39 MK |
| Pelanggaran pita jumlah Sub-CPMK (di luar rentang aturan §2) | 0 ✅ |
| MK tanpa Sub-CPMK | 0 ✅ |
| Sub-CPMK yang tidak tertaut ke CPMK sah pada MK-nya | 0 ✅ |
| Sub-CPMK ranah kognitif ber-KKO HOTS (C4 Menganalisis/C5 Mengevaluasi/C6 Mencipta) | 363 dari 363 (100%) ✅ |
| — rincian: C4 (Menganalisis) | 273 |
| — rincian: C5 (Mengevaluasi) | 19 |
| — rincian: C6 (Mencipta) | 71 |
| Sub-CPMK ranah afektif (A3/A4, tidak tunduk aturan HOTS — lihat §2.3) | 33 |
| Kemunculan kata "memahami"/"mengerti" sebagai KKO | 0 ✅ |

---

## 5. Catatan Verifikasi dan Validasi Prodi

1. **Keterlacakan penuh terverifikasi**: setiap Sub-CPMK pada dokumen ini tertaut ke satu CPMK yang memang telah dialokasikan ke mata kuliah tersebut menurut `Pemetaan-CPMK-Alokasi-MK.md` §4 — tidak ada Sub-CPMK yang "keluar jalur" ke CPMK yang tidak dialokasikan pada MK bersangkutan.
2. **Jumlah Sub-CPMK mengikuti proporsi jumlah CPMK per MK**: MK dengan lebih banyak CPMK (karena SKS besar atau pengecualian AIK/Wajib Nasional) mendapat pembagian Sub-CPMK yang merata per CPMK, bukan dipukul rata secara sembarangan — lihat kolom "No" dan jumlah baris pada tiap tabel Sub-CPMK per CPMK di §3.
3. **Ekstrapolasi pita 1 SKS (§2.1)** merupakan satu-satunya penyimpangan dari aturan eksplisit Tim Kurikulum (yang hanya menyebut pita 2 dan 4 SKS) — didokumentasikan secara terbuka agar dapat divalidasi atau direvisi.
4. **Klasifikasi dasar vs. terapan (§2.2)** bersifat interpretatif tim penyusun berdasarkan posisi MK dalam struktur kurikulum (semester awal/lanjutan) dan sifat kontennya (fondasional vs. spesialisasi/proyek/lapangan) — Tim Kurikulum dapat menyesuaikan klasifikasi ini bila ada pertimbangan pedagogis lain, tanpa memengaruhi jumlah/pita Sub-CPMK yang sudah sesuai aturan SKS.
5. **Sub-CPMK bersifat draf operasional tingkat Program Studi**, menunjukkan **kerangka minimum** yang harus dicapai per CPMK pada tiap MK. Dosen pengampu tetap berwenang memperkaya redaksi, menambah indikator penilaian, dan menyesuaikan dengan RPS masing-masing selama tidak mengurangi cakupan CPMK induknya maupun keluar dari pita jumlah pada §2.
6. Dokumen ini **melengkapi** `Pemetaan-CPMK.md`, `Pemetaan-CPMK-Alokasi-MK.md`, `Pemetaan-Detail-Bahan-Kajian.md`, dan BAB VIII — bukan menggantikannya. Kode Sub-CPMK, deskripsi CPMK induk, dan BK rujukan pada dokumen ini konsisten dengan ketiga dokumen tersebut per tanggal penyusunan.
7. **Audit kesesuaian KKO (kata kerja operasional) terhadap tag level Bloom/Gagne** telah dilakukan terhadap seluruh 396 Sub-CPMK (dicocokkan kata kerja awal tiap deskripsi terhadap tabel KKO standar C1–C6/A1–A5). Ditemukan dan diperbaiki 18 ketidaksesuaian: (a) 12 Sub-CPMK berverba kognitif murni ("Menjelaskan", "Mengidentifikasi") pada MK Wajib Umum/Karakter (AIK, Pancasila, Kewarganegaraan) yang semula ditandai level afektif (A2) — dikoreksi menjadi C2/C3 karena tidak mengandung unsur penghayatan nilai, hanya pemahaman kognitif sebagai prasyarat sebelum Sub-CPMK berikutnya (bertanda A3/A4) yang memang afektif; (b) 5 Sub-CPMK berverba "Menghasilkan"/"Merancang" (create/C6 menurut KKO standar) yang semula ditandai C3/C4 — dikoreksi menjadi C6 agar konsisten dengan penandaan verba yang sama di bagian lain dokumen. Verba lain yang tampak bervariasi level (mis. "Menunjukkan", "Menjunjung", "Mempresentasikan") dipertahankan apa adanya karena levelnya memang bergantung konteks (mis. sekadar menyatakan sikap vs. mengorganisasikan nilai menjadi rencana tindakan) dan bukan kesalahan penandaan.
8. **Konversi menyeluruh ke KKO HOTS (§2.3)**: revisi lanjutan menindaklanjuti temuan bahwa 83,2% Sub-CPMK ranah kognitif (302 dari 363) masih berverba LOTS/MOTS (C2 "Menjelaskan", C3 "Menerapkan"/"Mengidentifikasi"/"Mengimplementasikan", dsb.), bertentangan dengan ketentuan KKNI Level 6 bahwa Sub-CPMK S1 wajib berfokus pada Menganalisis/Mengevaluasi/Mencipta. Seluruh 303 Sub-CPMK kognitif yang belum HOTS telah dikonversi (lihat metodologi konversi di §2.3), termasuk menghapus 3 kemunculan kata "memahami" yang eksplisit dilarang panduan KKO. Hasil akhir: **100% Sub-CPMK ranah kognitif (363/363) kini berlevel C4–C6**. Sub-CPMK ranah afektif (33 item, A3/A4) tidak diubah karena berada di luar cakupan taksonomi Bloom kognitif — lihat penjelasan cakupan di §2.3. Konversi diterapkan **ketat dan seragam ke seluruh 65 MK tanpa pengecualian kategori**, sesuai arahan eksplisit Tim Kurikulum.

---

*Dokumen ini disusun sebagai pelengkap BAB VIII — CPMK dan Sub-CPMK, Dokumen Kurikulum OBE Program Studi S1 Teknologi Informasi 2027, Institut Sains Teknologi dan Kesehatan Aisyiyah Kendari.*
