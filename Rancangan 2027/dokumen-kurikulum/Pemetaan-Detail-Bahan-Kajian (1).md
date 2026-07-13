# PEMETAAN DETAIL BAHAN KAJIAN — CPL — MATA KULIAH — DOKUMEN RUJUKAN

**Dokumen Pelengkap BAB V — Program Studi S1 Teknologi Informasi, Universitas Muhammadiyah, Kurikulum 2027**

> Dokumen ini memperluas BAB V (Bahan Kajian) dengan rantai keterlacakan empat tingkat: **Bahan Kajian (BK) → CPL Prodi → Mata Kuliah Pengampu → Dokumen Rujukan**, dilengkapi **Deskripsi** untuk setiap BK. Disusun berdasarkan BAB IV (CPL), BAB V (Bahan Kajian), BAB VI (Struktur Kurikulum — khususnya matriks MK–CPL §6.4 dan MK–BK §6.8), dan BAB VII (Deskripsi Mata Kuliah).

---

## 1. Kaidah Penyusunan Pemetaan

| Aturan | Ketentuan |
|--------|-----------|
| **BK → Deskripsi** | Setiap Bahan Kajian dilengkapi deskripsi ringkas yang menjelaskan cakupan materi/konsep yang dipelajari. |
| **BK → CPL** | Setiap Bahan Kajian dipetakan ke **2–3 CPL Prodi** (1 CPL utama + 1–2 CPL pendukung), diturunkan dari kontribusi CPL riil mata kuliah pengampunya (matriks MK–CPL BAB VI §6.4). |
| **BK → Mata Kuliah** | Setiap Bahan Kajian diampu oleh **lebih dari 1 hingga maksimal 7 mata kuliah** (1 MK utama/pengampu inti + MK pendukung yang memuat sebagian materi BK tersebut). |
| **Mata Kuliah → BK** | Seluruh **65 mata kuliah wajib memiliki minimal 1 BK**; satu mata kuliah dapat memiliki **lebih dari 2 Bahan Kajian** apabila cakupan materinya lintas-domain (mis. mata kuliah proyek/capstone, mata kuliah pengantar). |
| **BK → Dokumen Rujukan** | Setiap Bahan Kajian merujuk **lebih dari 1 dokumen/standar** (kombinasi dari APTIKOM 2023, IT2017/CC2020 ACM-IEEE, SKKNI Bidang TI, dan — untuk BK karakter — regulasi nasional/Pedoman AIK PTMA). |

**Perubahan terhadap BAB V asli:**
1. Ditambahkan **2 Bahan Kajian baru** — **BK28 (Wawasan Kebangsaan)** dan **BK29 (Al-Islam dan Kemuhammadiyahan)** — agar 7 mata kuliah Wajib Nasional/Institusi (Pancasila, Bahasa Indonesia, Kewarganegaraan, AIK I, AIK II, Kemuhammadiyahan, AIK IV) yang sebelumnya tidak memiliki BK kini tercakup. Total BK menjadi **29** (13 Penciri Utama + 14 Penciri Pendukung + 2 Penciri Nasional/Institusi).
2. Sejumlah BK yang sebelumnya hanya diampu 1 mata kuliah (BK01, BK07, BK12, BK14, BK15) diperluas dengan MK pendukung agar memenuhi kaidah ">1 MK".
3. Sejumlah BK yang sebelumnya hanya memiliki 1 CPL Utama diperluas menjadi 2–3 CPL berdasarkan kontribusi riil MK pengampunya.
4. **Deskripsi setiap BK ditulis ulang/diperluas** dari "Deskripsi Singkat" pada BAB V Tabel 5.2/5.3 menjadi kalimat deskriptif yang lebih lengkap, dan ditambahkan deskripsi baru untuk BK28 & BK29.

> ⚠️ **Status: Draf untuk validasi Prodi.** Perluasan CPL sekunder, MK pendukung, deskripsi, dan kode SKKNI yang tidak eksplisit di BAB V asli bersifat inferensi berbasis data kurikulum — mengikuti catatan validasi yang sama seperti BAB V §5.3 (BK12–21, BK23–26). Tim Kurikulum wajib memverifikasi terhadap dokumen APTIKOM/SKKNI resmi sebelum disahkan.

---

## 2. Pemetaan Detail per Bahan Kajian

### Kelompok A — Penciri Utama (BK01–BK13)

#### BK01 — Virtual Systems and Services
- **Deskripsi:** Bahan kajian yang mencakup virtualisasi server dan jaringan, komputasi awan (cloud computing), containerisasi (Docker/Kubernetes), serta pengelolaan dan penyediaan layanan berbasis infrastruktur virtual bagi organisasi.
- **CPL Prodi:** CPL04 (utama — Integrasi & Administrasi Infrastruktur TI), CPL03 (pendukung — Perancangan Solusi), CPL05 (pendukung — keamanan layanan virtual/cloud)
- **Mata Kuliah Pengampu (3):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN6254 | Sistem dan Layanan Virtual | 6 | Utama |
  | TIN6131 | Teknologi Platform | 6 | Pendukung (cloud platform, containerization) |
  | TIN2107 | Sistem Operasi | 2 | Pendukung (dasar virtualisasi tingkat OS) |
- **Dokumen Rujukan:** APTIKOM 2023 (Bahan Kajian Virtual Systems); IT2017 ACM/IEEE — KA Platform Technologies; SKKNI Bidang TI TIK.CS01.

#### BK02 — Internet of Things (IoT)
- **Deskripsi:** Mencakup arsitektur sistem IoT, protokol komunikasi machine-to-machine (MQTT, CoAP), integrasi sensor dan aktuator, serta embedded computing untuk menghubungkan perangkat fisik ke jaringan digital.
- **CPL Prodi:** CPL04 (utama), CPL03 (pendukung — perancangan solusi IoT end-to-end)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN6252 | Internet of Things *(Pil)* | 6 | Utama |
  | TIN4122 | Embedded Sistem | 4 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA IoT/Embedded Systems; CC2020 (Computing Curricula 2020).

#### BK03 — Jaringan Komputer
- **Deskripsi:** Membahas arsitektur jaringan komputer, model OSI/TCP-IP, teknik routing dan switching, pengalamatan IP, serta konfigurasi jaringan kabel dan nirkabel sebagai fondasi konektivitas sistem TI.
- **CPL Prodi:** CPL04 (utama), CPL05 (pendukung — keamanan jaringan)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN302 | Jaringan Komputer 1 | 3 | Utama |
  | TIN5248 | Jaringan Komputer 2 *(Pil)* | 5 | Utama (lanjutan) |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Networking; SKKNI Bidang TI TIK.JK01.

#### BK04 — Teknologi Sistem Terintegrasi
- **Deskripsi:** Mencakup prinsip integrasi sistem heterogen melalui middleware, application programming interface (API), arsitektur berorientasi layanan (SOA), dan microservices untuk menyatukan komponen TI yang berbeda menjadi satu ekosistem yang kohesif.
- **CPL Prodi:** CPL03 (utama), CPL04 (utama), CPL02 (pendukung — analisis kebutuhan integrasi)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN6130 | Teknologi Sistem Terintegrasi | 6 | Utama |
  | TIN5120 | Perancangan dan Integrasi Sistem | 5 | Utama |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Systems Integration & Architecture; CC2020.

#### BK05 — Teknologi Platform
- **Deskripsi:** Membahas pengembangan dan pemanfaatan platform komputasi — termasuk platform awan, platform mobile, Platform-as-a-Service (PaaS), dan Software-as-a-Service (SaaS) — sebagai fondasi pembangunan aplikasi modern.
- **CPL Prodi:** CPL03 (utama), CPL04 (utama)
- **Mata Kuliah Pengampu (4):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN6131 | Teknologi Platform | 6 | Utama |
  | TIN4120 | Pemrograman Web Lanjut | 4 | Pendukung |
  | TIN6253 | Aplikasi Seluler *(Pil)* | 7 | Pendukung |
  | TIN7138 | Sistem Web dan Seluler | 7 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Platform Technologies; SKKNI Bidang TI TIK.PL05 *(indikatif, perlu validasi)*.

#### BK06 — Pengembangan Aplikasi Berbasis Platform
- **Deskripsi:** Mencakup pengembangan aplikasi web dan mobile lintas-platform, termasuk progressive web app (PWA), dengan penekanan pada praktik pengembangan aplikasi yang dapat berjalan di berbagai lingkungan platform.
- **CPL Prodi:** CPL03 (utama), CPL04 (pendukung)
- **Mata Kuliah Pengampu (4):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN304 | Pemrograman Web Dasar | 3 | Utama |
  | TIN4120 | Pemrograman Web Lanjut | 4 | Utama |
  | TIN6253 | Aplikasi Seluler *(Pil)* | 7 | Utama |
  | TIN7138 | Sistem Web dan Seluler | 7 | Utama |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Web & Mobile Systems; CC2020.

#### BK07 — Prinsip-prinsip Keamanan Siber
- **Deskripsi:** Membahas dasar-dasar kriptografi, keamanan jaringan, penilaian kerentanan (vulnerability assessment), dan teknik ethical hacking untuk melindungi sistem, data, dan infrastruktur TI dari ancaman siber.
- **CPL Prodi:** CPL05 (utama), CPL04 (pendukung)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN6133 | Prinsip Keamanan Siber | 6 | Utama |
  | TIN6254 | Sistem dan Layanan Virtual *(Pil)* | 6 | Pendukung (keamanan layanan cloud) |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Cybersecurity Pervasive Themes; SKKNI Bidang TI TIK.CS02.

#### BK08 — Praktek Profesional Global
- **Deskripsi:** Mencakup etika profesi TI, komunikasi teknis lintas budaya, kerja sama tim dalam konteks global, serta pemahaman terhadap standar dan sertifikasi profesi TI internasional.
- **CPL Prodi:** CPL02 (utama), CPL03 (pendukung), CPL04 (pendukung — dari Magang)
- **Mata Kuliah Pengampu (5):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN6132 | Praktek Profesional Global | 6 | Utama |
  | INS1106 | Bahasa Inggris | 1 | Pendukung |
  | TIN2109 | Bahasa Inggris Sains | 2 | Pendukung |
  | TIN7260 | Magang/Praktik Kerja *(MBKM)* | 7 | Pendukung |
  | TIN7261 | Kuliah Kerja Nyata *(MBKM)* | 7 | Utama (pengabdian & etika profesional) |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Social & Professional Issues; Panduan MBKM Kemendikbudristek.

#### BK09 — Manajemen Data dan Informasi
- **Deskripsi:** Membahas perancangan basis data, data warehouse, tata kelola data (data governance), dan manajemen informasi sebagai aset organisasi untuk mendukung pengambilan keputusan yang akurat dan andal.
- **CPL Prodi:** CPL05 (utama), CPL02 (utama), CPL06 (pendukung — data untuk analitik)
- **Mata Kuliah Pengampu (5):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN2111 | Sistem Basis Data | 2 | Utama |
  | TIN5245 | Sistem Basis Data Lanjut *(Pil)* | 5 | Utama |
  | TIN5118 | Manajemen Informasi | 5 | Utama |
  | TIN4124 | Sistem Informasi Kesehatan | 4 | Pendukung |
  | TIN7257 | E-Health *(Pil)* | 7 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Data Management; SKKNI Bidang TI TIK.DB01.

#### BK10 — Fundamental Pemrograman dan PL
- **Deskripsi:** Mencakup konsep algoritma, struktur data, berbagai paradigma pemrograman, serta prinsip rekayasa perangkat lunak (SDLC, requirement, desain, pengujian) sebagai fondasi pengembangan solusi berbasis computing.
- **CPL Prodi:** CPL01 (utama), CPL03 (utama), CPL02 (pendukung — RPL)
- **Mata Kuliah Pengampu (6):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN1102 | Algoritma dan Pemrograman | 1 | Utama |
  | TIN2108 | Struktur Data | 2 | Utama |
  | TIN2112 | Dasar-Dasar Perangkat Lunak | 2 | Utama |
  | TIN303 | Pemrograman Berorientasi Objek | 3 | Utama |
  | TIN308 | Rekayasa Perangkat Lunak | 3 | Utama |
  | TIN1103 | Pengantar Teknologi Informasi | 1 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Programming Fundamentals; SKKNI Bidang TI TIK.SD01.

#### BK11 — Desain User Experience
- **Deskripsi:** Membahas prinsip interaksi manusia-komputer (HCI), riset pengguna, prototyping, pengujian usability, dan aksesibilitas untuk menghasilkan antarmuka dan pengalaman pengguna yang efektif serta inklusif.
- **CPL Prodi:** CPL03 (utama), CPL02 (pendukung)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN4126 | Interaksi Manusia dan Komputer | 4 | Utama |
  | TIN7140 | Design User Experience | 7 | Utama (lanjutan) |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA User Experience & HCI; CC2020.

#### BK12 — Sistem Embedded
- **Deskripsi:** Mencakup arsitektur mikrokontroler, sistem operasi real-time (RTOS), pemrograman firmware, dan antarmuka hardware-software untuk pengembangan sistem tertanam pada perangkat fisik.
- **CPL Prodi:** CPL04 (utama), CPL01 (pendukung — dasar arsitektur), CPL03 (pendukung)
- **Mata Kuliah Pengampu (3):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN4122 | Embedded Sistem | 4 | Utama |
  | TIN6252 | Internet of Things *(Pil)* | 6 | Pendukung |
  | TIN306 | Hardware/Software | 3 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA IoT/Embedded; SKKNI Bidang TI TIK.EMB01 *(indikatif, perlu validasi)*.

#### BK13 — Manajemen Proyek TI
- **Deskripsi:** Membahas metodologi manajemen proyek (Agile/Scrum/Waterfall), estimasi sumber daya, penjadwalan, dan manajemen risiko dalam merencanakan dan mengeksekusi proyek pengembangan TI.
- **CPL Prodi:** CPL02 (utama), CPL03 (utama)
- **Mata Kuliah Pengampu (6):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | INS2105 | Kewirausahaan | 2 | Utama |
  | TIN308 | Rekayasa Perangkat Lunak | 3 | Pendukung |
  | TIN6134 | Capstone Project 1 | 6 | Pendukung |
  | TIN7141 | Capstone Project 2 | 7 | Pendukung |
  | TIN6250 | Business Problem & DS Solution *(Pil)* | 6 | Pendukung |
  | TIN7260 | Magang/Praktik Kerja *(MBKM)* | 7 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Project Management; PMBOK/Agile Practice Guide (PMI).

---

### Kelompok B — Penciri Pendukung (BK14–BK27)

#### BK14 — Logika dan Matematika Diskrit
- **Deskripsi:** Mencakup logika proposisional dan predikat, teori himpunan, teori graf, dan kombinatorik sebagai fondasi berpikir komputasional untuk perancangan algoritma dan sistem digital.
- **CPL Prodi:** CPL01 (utama), CPL03 (pendukung — struktur diskrit untuk algoritma)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN1101 | Logika Informatika | 1 | Utama |
  | TIN2108 | Struktur Data | 2 | Pendukung (graf, pohon, kombinatorik) |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Computing & Computation Foundations; CC2020.

#### BK15 — Sistem Operasi
- **Deskripsi:** Membahas manajemen proses, penjadwalan CPU, sinkronisasi, manajemen memori, sistem berkas, dan mekanisme internal sistem operasi modern.
- **CPL Prodi:** CPL04 (utama), CPL01 (pendukung)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN2107 | Sistem Operasi | 2 | Utama |
  | TIN307 | Organisasi dan Arsitektur Komputer | 3 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Systems Administration & Maintenance; CC2020.

#### BK16 — Arsitektur dan Organisasi Komputer
- **Deskripsi:** Mencakup arsitektur CPU, hierarki memori, sistem input/output, dan dasar-dasar komputasi paralel yang mendasari cara kerja perangkat keras komputer.
- **CPL Prodi:** CPL01 (utama), CPL04 (utama), CPL02 (pendukung)
- **Mata Kuliah Pengampu (3):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN306 | Hardware/Software | 3 | Utama |
  | TIN307 | Organisasi dan Arsitektur Komputer | 3 | Utama |
  | TIN1103 | Pengantar Teknologi Informasi | 1 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Computing & Computation Foundations; CC2020.

#### BK17 — Analisis dan Pemodelan Sistem
- **Deskripsi:** Membahas rekayasa kebutuhan (requirements engineering), pemodelan sistem menggunakan UML, serta perancangan arsitektur dan proses bisnis suatu sistem informasi.
- **CPL Prodi:** CPL02 (utama), CPL03 (utama)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN5119 | Paradigma Sistem | 5 | Utama |
  | TIN5120 | Perancangan dan Integrasi Sistem | 5 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Requirements Analysis; SKKNI Bidang TI TIK.AN01 *(indikatif, perlu validasi)*.

#### BK18 — Manajemen Sistem Informasi
- **Deskripsi:** Mencakup strategi sistem informasi, kerangka kerja ITIL, tata kelola TI (IT governance), dan arsitektur enterprise untuk menyelaraskan TI dengan tujuan organisasi.
- **CPL Prodi:** CPL02 (utama), CPL05 (utama)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN305 | Manajemen Sistem Informasi | 3 | Utama |
  | TIN5118 | Manajemen Informasi | 5 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA IT Management; ITIL v4 Framework.

#### BK19 — Statistika dan Probabilitas
- **Deskripsi:** Membahas statistika deskriptif dan inferensial, distribusi probabilitas, uji hipotesis, dan analisis regresi sebagai dasar kuantitatif untuk analisis dan pengambilan keputusan berbasis data.
- **CPL Prodi:** CPL06 (utama), CPL01 (utama), CPL02 (pendukung)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN4125 | Statistik | 4 | Utama |
  | TIN6251 | Riset Operasi *(Pil)* | 6 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Data Science & Analytics; CC2020.

#### BK20 — Komputasi Grafis dan Multimedia
- **Deskripsi:** Mencakup grafika komputer 2D/3D, pengolahan citra, video, dan audio, serta pengembangan sistem multimedia interaktif.
- **CPL Prodi:** CPL03 (utama), CPL06 (pendukung — pengolahan citra/visual untuk analitik)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN2106 | Komputer Grafis | 2 | Utama |
  | TIN5247 | Multimedia *(Pil)* | 5 | Utama |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Graphics & Visualization; CC2020.

#### BK21 — Kecerdasan Buatan
- **Deskripsi:** Membahas machine learning, deep learning, natural language processing (NLP), computer vision, serta prinsip etika dalam pengembangan dan penerapan kecerdasan buatan.
- **CPL Prodi:** CPL06 (utama), CPL01 (utama), CPL02 (pendukung)
- **Mata Kuliah Pengampu (4):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN4121 | Pengantar Kecerdasan Buatan | 4 | Utama |
  | TIN5246 | Kecerdasan Buatan *(Pil)* | 5 | Utama |
  | TIN4123 | Data Mining | 4 | Pendukung |
  | TIN5117 | Data Science | 5 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Intelligent Systems (AI/ML); SKKNI Bidang TI TIK.AI01.

#### BK22 — Skalabilitas dan Analitik Data
- **Deskripsi:** Mencakup pengelolaan big data, pipeline data, teknik data mining, business intelligence, dan visualisasi data untuk menghasilkan wawasan yang mendukung pengambilan keputusan berskala besar.
- **CPL Prodi:** CPL06 (utama), CPL02 (utama), CPL01 (pendukung)
- **Mata Kuliah Pengampu (4):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN4123 | Data Mining | 4 | Utama |
  | TIN5117 | Data Science | 5 | Utama |
  | TIN5123 | Analitik Data | 5 | Utama |
  | TIN6250 | Business Problem & DS Solution *(Pil)* | 6 | Utama |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Data Science & Analytics; SKKNI Bidang TI TIK.DA01.

#### BK23 — Matematika Terapan
- **Deskripsi:** Membahas kalkulus, aljabar linier, persamaan diferensial, transformasi, dan metode numerik sebagai alat kuantitatif untuk pemodelan dan komputasi.
- **CPL Prodi:** CPL01 (utama), CPL06 (pendukung — dasar model kuantitatif untuk analitik)
- **Mata Kuliah Pengampu (3):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN1105 | Aljabar Linier dan Matriks | 1 | Utama |
  | TIN2110 | Kalkulus | 2 | Utama |
  | TIN6251 | Riset Operasi *(Pil)* | 6 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Mathematical & Statistical Foundations; CC2020.

#### BK24 — Metodologi Penelitian TI
- **Deskripsi:** Mencakup perancangan penelitian (research design), kajian literatur, teknik pengumpulan dan analisis data, serta penulisan karya ilmiah di bidang teknologi informasi.
- **CPL Prodi:** CPL02 (utama), CPL03 (pendukung)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN5121 | Metodologi Penelitian | 5 | Utama |
  | TIN8142 | Seminar Proposal | 7 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; Pedoman Penulisan Karya Ilmiah Prodi; IT2017 ACM/IEEE — KA Social & Professional Issues.

#### BK25 — Informatika Kesehatan
- **Deskripsi:** Membahas sistem informasi kesehatan, standar interoperabilitas data kesehatan (HL7/FHIR), rekam medis elektronik, dan telemedicine sebagai penerapan TI di sektor kesehatan.
- **CPL Prodi:** CPL03 (utama), CPL05 (utama), CPL02 (pendukung)
- **Mata Kuliah Pengampu (3):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN4124 | Sistem Informasi Kesehatan | 4 | Utama |
  | TIN5249 | Informatika Medis *(Pil)* | 5 | Utama |
  | TIN7257 | E-Health *(Pil)* | 7 | Utama (lanjutan) |
- **Dokumen Rujukan:** APTIKOM 2023; Standar HL7/FHIR (interoperabilitas kesehatan); IT2017 ACM/IEEE — KA Data Management.

#### BK26 — Komunikasi Data
- **Deskripsi:** Mencakup konsep transmisi data, teknik modulasi dan encoding, multiplexing, deteksi/koreksi error, serta protokol komunikasi dasar sebagai pengantar jaringan komputer.
- **CPL Prodi:** CPL04 (utama), CPL03 (pendukung)
- **Mata Kuliah Pengampu (2):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN1104 | Komunikasi Data | 1 | Utama |
  | TIN302 | Jaringan Komputer 1 | 3 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; IT2017 ACM/IEEE — KA Networking; CC2020.

#### BK27 — Metode Penelitian dan Pengembangan
- **Deskripsi:** Membahas perancangan proyek akhir (capstone design), penyusunan skripsi, pengembangan proyek inovatif, dan penulisan karya ilmiah sebagai puncak integrasi kompetensi mahasiswa.
- **CPL Prodi:** CPL02 (utama), CPL03 (utama), CPL01 (pendukung — Skripsi)
- **Mata Kuliah Pengampu (5):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | TIN6134 | Capstone Project 1 | 6 | Utama |
  | TIN7141 | Capstone Project 2 | 7 | Utama |
  | TIN8143 | Seminar Hasil | 8 | Utama |
  | TIN8144 | Skripsi | 8 | Utama |
  | TIN8142 | Seminar Proposal | 7 | Pendukung |
- **Dokumen Rujukan:** APTIKOM 2023; Pedoman Tugas Akhir/Skripsi Prodi; IT2017 ACM/IEEE — KA Systems Development.

---

### Kelompok C — Penciri Nasional/Institusi (BK28–BK29) *(BARU)*

#### BK28 — Wawasan Kebangsaan
- **Deskripsi:** Membentuk pemahaman mahasiswa mengenai dasar negara Pancasila, kaidah berbahasa Indonesia yang baik dan benar, serta hak dan kewajiban warga negara — sebagai fondasi sikap kebangsaan dan nasionalisme lulusan. Tidak dipetakan sebagai kontribusi teknis langsung ke CPL01–CPL06, melainkan kontribusi tidak langsung ke ranah **Sikap** (SN-Dikti Pasal 6) yang menopang CPL, sesuai catatan BAB IV §4.7.1 dan matriks Sikap SN-Dikti (Tabel 4.3).
- **CPL Prodi (kontribusi sikap, tidak langsung):** CPL02 (pendukung — butir sikap c/d: kontribusi mutu kehidupan bermasyarakat, kepekaan sosial), CPL05 (pendukung — butir sikap e: taat hukum dan disiplin)
- **Mata Kuliah Pengampu (3):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | NAS1101 | Pancasila | 1 | Utama |
  | NAS1102 | Bahasa Indonesia | 1 | Utama |
  | NAS2103 | Kewarganegaraan | 2 | Utama |
- **Dokumen Rujukan:** UU No. 12 Tahun 2012 tentang Pendidikan Tinggi; SK Dirjen Belmawa tentang Kurikulum Inti MK Wajib Umum (Pancasila, Bahasa Indonesia, Kewarganegaraan); Permendikbudristek No. 3 Tahun 2020 (SN-Dikti).

#### BK29 — Al-Islam dan Kemuhammadiyahan (AIK)
- **Deskripsi:** Menanamkan pemahaman keimanan, ibadah, muamalah, sejarah dan ideologi gerakan Muhammadiyah/Aisyiyah, serta integrasi nilai-nilai Islam dengan perkembangan ilmu pengetahuan dan teknologi — sebagai penciri khas lulusan Universitas Muhammadiyah. Kontribusi tidak langsung ke ranah **Sikap**, khususnya butir a/b/f/h (Tabel 4.3) yang mendasari etika profesi, kemandirian, dan kewirausahaan lulusan.
- **CPL Prodi (kontribusi sikap, tidak langsung):** CPL02 (pendukung — butir sikap h: kemandirian & kewirausahaan, relevan dengan AIK II/Muamalah), CPL05 (pendukung — butir sikap f: internalisasi nilai, norma, dan etika akademik)
- **Mata Kuliah Pengampu (4):**
  | Kode | Mata Kuliah | Semester | Peran |
  |------|-------------|:--:|-------|
  | INS1101 | AIK I (Keimanan, Kemanusiaan dan Akhlak) | 1 | Utama |
  | INS2102 | AIK II (Ibadah dan Muamalah) | 2 | Utama |
  | INS301 | Kemuhammadiyahan dan Ke'Aisyiyahan (setara AIK III) | 3 | Utama |
  | INS4104 | AIK IV (Islam dan IPTEK) | 4 | Utama |
- **Dokumen Rujukan:** Pedoman Pengembangan Al-Islam dan Kemuhammadiyahan PTMA (Majelis Diktilitbang PP Muhammadiyah); Himpunan Putusan Tarjih Muhammadiyah; Permendikbudristek No. 3 Tahun 2020 (SN-Dikti — muatan wajib institusi).

---

## 3. Ringkasan Kardinalitas (Verifikasi Kaidah §1)

| BK | Nama Singkat | Jml CPL | Jml MK | Jml Dok. Rujukan | Status |
|----|--------------|:---:|:---:|:---:|:---:|
| BK01 | Virtual Systems | 3 | 3 | 3 | ✅ |
| BK02 | IoT | 2 | 2 | 3 | ✅ |
| BK03 | Jaringan Komputer | 2 | 2 | 3 | ✅ |
| BK04 | Teknologi Sistem Terintegrasi | 3 | 2 | 3 | ✅ |
| BK05 | Teknologi Platform | 2 | 4 | 3 | ✅ |
| BK06 | Aplikasi Berbasis Platform | 2 | 4 | 3 | ✅ |
| BK07 | Prinsip Keamanan Siber | 2 | 2 | 3 | ✅ |
| BK08 | Praktek Profesional Global | 3 | 5 | 3 | ✅ |
| BK09 | Manajemen Data dan Informasi | 3 | 5 | 3 | ✅ |
| BK10 | Fundamental Pemrograman dan PL | 3 | 6 | 3 | ✅ |
| BK11 | Desain UX | 2 | 2 | 3 | ✅ |
| BK12 | Sistem Embedded | 3 | 3 | 3 | ✅ |
| BK13 | Manajemen Proyek TI | 2 | 6 | 3 | ✅ |
| BK14 | Logika & Matematika Diskrit | 2 | 2 | 3 | ✅ |
| BK15 | Sistem Operasi | 2 | 2 | 3 | ✅ |
| BK16 | Arsitektur & Organisasi Komputer | 3 | 3 | 3 | ✅ |
| BK17 | Analisis & Pemodelan Sistem | 2 | 2 | 3 | ✅ |
| BK18 | Manajemen Sistem Informasi | 2 | 2 | 3 | ✅ |
| BK19 | Statistika & Probabilitas | 3 | 2 | 3 | ✅ |
| BK20 | Komputasi Grafis & Multimedia | 2 | 2 | 3 | ✅ |
| BK21 | Kecerdasan Buatan | 3 | 4 | 3 | ✅ |
| BK22 | Skalabilitas & Analitik Data | 3 | 4 | 3 | ✅ |
| BK23 | Matematika Terapan | 2 | 3 | 3 | ✅ |
| BK24 | Metodologi Penelitian TI | 2 | 2 | 3 | ✅ |
| BK25 | Informatika Kesehatan | 3 | 3 | 3 | ✅ |
| BK26 | Komunikasi Data | 2 | 2 | 3 | ✅ |
| BK27 | Metode Penelitian & Pengembangan | 3 | 5 | 3 | ✅ |
| BK28 | Wawasan Kebangsaan *(baru)* | 2 | 3 | 3 | ✅ |
| BK29 | Al-Islam dan Kemuhammadiyahan *(baru)* | 2 | 4 | 3 | ✅ |

**Hasil verifikasi:** Seluruh 29 BK memenuhi kaidah 2–3 CPL, >1–7 Mata Kuliah, dan ≥2 (di sini seragam 3) Dokumen Rujukan, serta memiliki deskripsi.

---

## 4. Lampiran — Cross-Check Mata Kuliah → Bahan Kajian (Seluruh 65 MK)

Tabel berikut memverifikasi bahwa **setiap mata kuliah memiliki minimal 1 BK**; beberapa MK lintas-domain (Pengantar TI, Jaringan Komputer 1, Pemrograman Web Lanjut, Embedded Sistem, Data Mining, Sistem Informasi Kesehatan, Data Science, Perancangan & Integrasi Sistem, Capstone 1 & 2, Aplikasi Seluler, Sistem Web dan Seluler, Magang, Seminar Proposal, dll.) memiliki **lebih dari 1 BK**.

| Sem | Kode | Mata Kuliah | Bahan Kajian |
|:---:|------|-------------|---------------|
| 1 | INS1101 | AIK I | BK29 |
| 1 | INS1106 | Bahasa Inggris | BK08 |
| 1 | NAS1101 | Pancasila | BK28 |
| 1 | NAS1102 | Bahasa Indonesia | BK28 |
| 1 | TIN1101 | Logika Informatika | BK14 |
| 1 | TIN1102 | Algoritma dan Pemrograman | BK10 |
| 1 | TIN1103 | Pengantar Teknologi Informasi | BK10, BK16 |
| 1 | TIN1104 | Komunikasi Data | BK26 |
| 1 | TIN1105 | Aljabar Linier dan Matriks | BK23 |
| 2 | INS2102 | AIK II | BK29 |
| 2 | INS2105 | Kewirausahaan | BK13 |
| 2 | NAS2103 | Kewarganegaraan | BK28 |
| 2 | TIN2106 | Komputer Grafis | BK20 |
| 2 | TIN2107 | Sistem Operasi | BK15, BK01 |
| 2 | TIN2108 | Struktur Data | BK10, BK14 |
| 2 | TIN2109 | Bahasa Inggris Sains | BK08 |
| 2 | TIN2110 | Kalkulus | BK23 |
| 2 | TIN2111 | Sistem Basis Data | BK09 |
| 2 | TIN2112 | Dasar-Dasar Perangkat Lunak | BK10 |
| 3 | INS301 | Kemuhammadiyahan dan Ke'Aisyiyahan | BK29 |
| 3 | TIN302 | Jaringan Komputer 1 | BK03, BK26 |
| 3 | TIN303 | Pemrograman Berorientasi Objek | BK10 |
| 3 | TIN304 | Pemrograman Web Dasar | BK06 |
| 3 | TIN305 | Manajemen Sistem Informasi | BK18 |
| 3 | TIN306 | Hardware/Software | BK16, BK12 |
| 3 | TIN307 | Organisasi dan Arsitektur Komputer | BK16, BK15 |
| 3 | TIN308 | Rekayasa Perangkat Lunak | BK10, BK13 |
| 4 | INS4104 | AIK IV | BK29 |
| 4 | TIN4120 | Pemrograman Web Lanjut | BK06, BK05 |
| 4 | TIN4121 | Pengantar Kecerdasan Buatan | BK21 |
| 4 | TIN4122 | Embedded Sistem | BK12, BK02 |
| 4 | TIN4123 | Data Mining | BK22, BK21 |
| 4 | TIN4124 | Sistem Informasi Kesehatan | BK25, BK09 |
| 4 | TIN4125 | Statistik | BK19 |
| 4 | TIN4126 | Interaksi Manusia dan Komputer | BK11 |
| 5 | TIN5117 | Data Science | BK22, BK21 |
| 5 | TIN5118 | Manajemen Informasi | BK09, BK18 |
| 5 | TIN5119 | Paradigma Sistem | BK17 |
| 5 | TIN5120 | Perancangan dan Integrasi Sistem | BK04, BK17 |
| 5 | TIN5121 | Metodologi Penelitian | BK24 |
| 5 | TIN5123 | Analitik Data | BK22 |
| 5 | TIN5245 | Sistem Basis Data Lanjut *(Pil)* | BK09 |
| 5 | TIN5246 | Kecerdasan Buatan *(Pil)* | BK21 |
| 5 | TIN5247 | Multimedia *(Pil)* | BK20 |
| 5 | TIN5248 | Jaringan Komputer 2 *(Pil)* | BK03 |
| 5 | TIN5249 | Informatika Medis *(Pil)* | BK25 |
| 6 | TIN6130 | Teknologi Sistem Terintegrasi | BK04 |
| 6 | TIN6131 | Teknologi Platform | BK05, BK01 |
| 6 | TIN6132 | Praktek Profesional Global | BK08 |
| 6 | TIN6133 | Prinsip Keamanan Siber | BK07 |
| 6 | TIN6134 | Capstone Project 1 | BK27, BK13 |
| 6 | TIN6250 | Business Problem & DS Solution *(Pil)* | BK22, BK13 |
| 6 | TIN6251 | Riset Operasi *(Pil)* | BK19, BK23 |
| 6 | TIN6252 | Internet of Things *(Pil)* | BK02, BK12 |
| 6 | TIN6254 | Sistem dan Layanan Virtual *(Pil)* | BK01, BK07 |
| 7 | TIN6253 | Aplikasi Seluler *(Pil)* | BK06, BK05 |
| 7 | TIN7138 | Sistem Web dan Seluler | BK06, BK05 |
| 7 | TIN7140 | Design User Experience | BK11 |
| 7 | TIN7141 | Capstone Project 2 | BK27, BK13 |
| 7 | TIN7257 | E-Health *(Pil)* | BK25, BK09 |
| 7 | TIN7260 | Magang/Praktik Kerja *(MBKM)* | BK08, BK13 |
| 7 | TIN7261 | Kuliah Kerja Nyata *(MBKM)* | BK08 |
| 7 | TIN8142 | Seminar Proposal | BK24, BK27 |
| 8 | TIN8143 | Seminar Hasil | BK27 |
| 8 | TIN8144 | Skripsi | BK27 |

> ✅ **Verifikasi:** 65/65 mata kuliah memiliki minimal 1 Bahan Kajian. 25 mata kuliah memiliki lebih dari 1 Bahan Kajian.

---

## 5. Catatan Penting untuk Validasi Prodi

1. **BK28 dan BK29 bersifat usulan baru** untuk memenuhi syarat "seluruh MK harus punya BK" — Prodi perlu memutuskan apakah pendekatan ini diterima, atau MK Wajib Nasional/Institusi tetap dikecualikan dari matriks BK (karena secara konsep BK biasanya khusus kompetensi teknis TI, bukan MK Wajib Umum/Karakter).
2. **CPL sekunder/pendukung** pada tiap BK adalah hasil inferensi dari matriks MK–CPL (BAB VI §6.4), bukan dari dokumen APTIKOM resmi — perlu verifikasi oleh Tim Kurikulum.
3. **Deskripsi setiap BK** merupakan pengembangan naratif dari "Deskripsi Singkat" BAB V Tabel 5.2/5.3, ditulis ulang menjadi kalimat deskriptif lengkap; deskripsi BK28/BK29 sepenuhnya baru dan perlu diselaraskan dengan silabus resmi MK Wajib Umum/AIK di tingkat universitas.
4. **MK pendukung tambahan** (mis. Sistem Operasi & Teknologi Platform sebagai pendukung BK01; Hardware/Software sebagai pendukung BK12/BK15) mencerminkan tumpang-tindih materi yang wajar dalam kurikulum terintegrasi, namun sebaiknya dikonfirmasi ke dosen pengampu RPS masing-masing.
5. **Kode SKKNI yang ditandai "indikatif, perlu validasi"** (BK05, BK12, BK17) mengikuti pola penomoran dokumen asli namun belum terverifikasi terhadap SKKNI resmi Bidang TI.
6. Dokumen ini **melengkapi, bukan menggantikan**, BAB V (Bahan Kajian) dan BAB VI §6.8 (Matriks MK–BK) — setelah divalidasi, disarankan hasil pemetaan ini diintegrasikan kembali ke BAB V/VI agar dokumen kurikulum tetap satu sumber kebenaran (single source of truth).

---

*Dokumen ini disusun sebagai pelengkap BAB V — Bahan Kajian, Dokumen Kurikulum OBE Program Studi S1 Teknologi Informasi 2027, Universitas Muhammadiyah.*
