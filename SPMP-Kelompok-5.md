SPMP Bab 1. Pendahuluan

1.1 Gambaran Proyek

Proyek ini adalah untuk membuat Aplikasi JAHAT (Aplikasi Jalan Sehat berbasis Mobile). Didalam proyek ini menggunakan bahasa Pemrograman Java. Aplikasi ini dibuat dengan menggunakan software Android Studio. Dibuatnya aplikasi ini bertujuan untuk masyarakat umum yang memang gemar berolahraga dan membantu seberapa jauh dia berjalan dan berapa jauhnya yang diperlukan untuk berolahraga yang bermanfaat untuk kesehatannya dengan dibantu adanya Aplikasi Jalan Sehat ini. Kami juga mengharapkan dengan adanya aplikasi ini bisa berguna bagi kami sendiri khususnya ataupun bagi masyarakat luas pada umumnya.

1.2 Dokumen-dokumen dalam proyek

SPMP

SPMP ( Software Project Management Plan ) adalah software yang dibuat untuk mengatur manajemen tugas, waktu pengerjaan dan kerjasama dalam sebuah tim.

SRS

SRS ( Software Requirements Specification ) adalah dokumen yang menjelaskan tentang berbagai kebutuhan yang harus dipenuhi oleh suatu software. _Dokumen _ini dibuat oleh developer (pembuat software) setelah menggali informasi dari calon pemakai software.

1.3 Evolusi SPMP

Dokumen ini akan selalu diperbarui seiring dengan kemajuan proyek. Pembaruan harus diharapkan pada bagian berikut :

Referensi diperbarui seperlunya Definisi, akronim, dan singkatan-singkatan seperlunya Proses teknis - bagian ini akan direvisi dengan tepat karena persyaratan dan keputusan disain menjadi lebih jelas Jadwal - saat proyek berjalan, jadwal akan diperbarui sesuai dengan itu 1.4 Material acuan

Dokumen ini adalah dokumen yang digunakan pada tahap perencanaan awal pengerjaan proyek dalam pembuatan kami memakai standar IEEE.

1.5 Definisi dan Akronim (singkatan)

IEEE	Institute of Electrical and Electronics Engineer Bab 2. Organisasi Proyek

2.1 Model proses

Dalam proyek yang kami buat kita menggunakan model proses Overlap

2.2 Struktur organisasi

-Project Manager

-Programmer

-Database engineer

-Design

-Analysis

2.3 Batasan dan antarmuka organisasi

FROM	TO	KAITAN Project Manager

Programmer

Database Engineer

Design

Analysis

2.4 Lingkup tanggung jawab

Bab 3. Proses Manajerial

3.1 Tujuan dan prioritas manajemen
Tujuan dari proyek ini adalah untuk membuat sistem kesahatan tubuh dengan dengan metode lari/joging menggunakan sistem GIS. Proyek ini sangat diprioritaskan karena memberi manfaat tinggi bagi masyarakat atau orang yang jarang berolahraga.

3.2 Asumsi-asumsi, ketergantungan/keterkaitan, dan batasan-batasan
Asumsi proyek adalah sebagai berikut :
i. Tim 4 sumber
ii. Ketersediaan peralatan dan perangkat lunak
iii. Persetujuan pendanaan
Substansi proyek adalah sebagai berikut :


3.3 Manajemen resiko

3.4 Mekanisme monitoring dan kontroling

3.5 Perencanaan staff

Bab 4. Proses Teknis

4.1 Metode, tool, dan teknik

4.1.1. Metoda
Dalam sebuah perancangan Jalan Sehat berbasis mobile, diperlukan perhatian khusus pada karakteristik penggunan dan keterbatasan device-nya. Jalan Sehat berbasis mobile yang ada tidak begitu saja diaplikasikan. Beberapa aspek yang menjadi perhatian dalam perancangan aplikasi Jalan Sehat berbasis berbasis mobile adalah sebagai berikut:
1) Keterbatasan Resource
Dibanding dengan perangkat desktop yang didukung oleh hardware yang lebih powerfull, perangkat mobile sangat terbatas dalam hal resource. Hal ini menyebabkan penggunaan resource pada proses komputasi mobile harus dilakukan secara efisien dan seefektif mungkin. Keterbatasan resource disini adalah keterbatasan proses komputasi.

2) Keterbatasan Hardware
Keterbatasan hardware yaitu pada pemakaian baterai dan keterbatasan memori. Penghematan baterai pada penggunaan smartphone android dilakukan dengan meminimasi gambar dan animasi. Tampilan lebih banyak menggunakan teks dan button. Tampilan gambar hanya ditampilkan secara sederhana dan seperlunya saja.
Untuk menghemat memori maka aplikasi mengalokasikan memori seoptimal dan seefisien mungkin, sedangkan untuk mengatasi keterbatasan proses komputasi maka perangkat lunak akan melakukan komputasi dan menggunakan thread seminimum mungkin.

3) Keterbatasan Jaringan
Untuk mengurangi penggunaan internet secara terus menerus, maka aplikasi ini harus mampu memberi dukungan opererasi secara offline sehingga tidak harus terhubung secara terus menerus dengan server.

4) Device yang pervasif
Perangkat bergerak memiliki bentuk kecil, mudah dibawa kemana- mana, dan dapat
berpindah tangan sehingga dibutuhkan solusi untuk persoalan sosial maupun pesoalan teknis ini. Diperlukan adanya mekanisme proteksi on-device untuk melindungi data sensitive.

5) Skema integrasi
Banyak aplikasi nirkabel bergerak yang membutuhkan integrasi dengan banyak sistem backend atau middleware berbeda. Saat ini terdapat beberapa teknologi yang dapat digunakan, diantaranya adalah protokol biner proprietary, Framework RPC, messaging serta xml web sercive. Masing - masing teknologi ini memiliki kekurangan dan kelebihan.

6) Kenyamanan pengguna
Merancang aplikasi yang mudah digunakan adalah tantangan besar bagi pengembang.
Beberapa hal yang perlu diperhatikan. Tampilan yang menarik, tidak membosankan, tidak terlalu padat, dan pemanfaatan thread untuk proses yang lama, prefensi pengguna dan penyediaan deployment descriptor untuk kemudahan instalasi.

4.1.2 Tool
1. Laptop
Dalam hal ini keberadaan Laptop digunakan untuk membuat Aplikasi Jalan Sehat, melalui aplikasi Android Studio.

2. Handphone Android
Dalam hal ini keberadaan Handphone Android digunakan untuk menguji coba aplikasi apakah sudah bisa digunakan atau tidaknya dari aplikasi Jalan Sehat tersebut.

3. Buku Referensi
Buku Referensi digunakan sebagai sumber untuk mencari Sourcode yang diperlukan dalam membuat aplikasi Jalan Sehat, dan sebagai Sumber data dari Proposal yang dibuat.

4.1.3 Teknik

4.1.3.1 Teknik Pengumpulan data
Teknik pengumpulan data dalam membuat aplikasi Jalan Sehat berbasis Mobile menggunakan dua macam metode penelitian. Kedua macam metode tersebut meliputi :
1.	Metode Observasi
Metode observasi dilakukan untuk kegiatan analisis kebutuhan pada penelitian pendahuluan. Metode ini digunakan untuk mengetahui kebutuhan masyarakat akan aplikasi yang kami buat.

2.	Metode Tes
Metode tes digunakan untuk mengetahui tingkat efektivitas produk yang dihasilkan berupa media Jalan Sehat berbasis Mobile, apabila nanti sudah ada aplikasinya akan digunakan atau tidaknya.

4.1.3.2 Teknik Analisis data
Data hasil penelitian diperoleh dari diskusi bersama satu kelompok, dengan cara mengetahui terlebih dahulu apa yang saat ini masyarakat butuhkan. Dengan cara itu maka diambil kesepakatan untuk membuat aplikasi Jalan Sehat berbasis Mobile.

4.2 Dokumentasi perangkat lunak
1. Sistem Operasi
Sistem operasi yang digunakan adalah Linux, dan windows.

2. Bahasa Pemrograman
Bahasa Pemrograman yang digunakan untuk membuat aplikasi Jalan sehat berbasis Mobile ini menggunakan bahasa pemrograman Java.

3. Program Aplikasi
Aplikasi yang digunakan untuk membuat aplikasi ini yaitu menggunakan Android Studio.

4.3 Fungsi-fungsi pendukung proyek
1. Fungsi Rutin
Yaitu fungsi adaministrasi yang membutuhkan banyak pemikiran mencakup pembuatan proposal, serta pembuatan Logbook dll.

2. Fungsi Teknis
Yaitu fungsi yang membutuhkan pendapat, dan keputusan bersama agar pembuatan aplikasi berjalan dengan baik.

3. Fungsi Analisis
Yaitu fungsi yang membutuhkan pemikiran yang kritis dan kreatif disertai kemampuan untuk mengambil keputusan, seperti menganalisis Proposal, Laporan, maupun membuat keputusan.

4. Fungi Interpersonal
Yaitu fungsi yang membutuhkan penilaian dan analisis sebagai dasar pengambilan keputusan serta keterampilan yang berhubungan dengan orang lain, sebagai contohnya dia tahu tugasnya sebagai apa dan bisa menempatkan dirinya dengan tugasnya tersebut.

5. Fungsi Leader-Manajerial
Yaitu fungsi yang dimiliki oleh seorang Manajer Proyek, dalam hal ini diperlukan adanya ketegasan dari seorang pemimpin tersebut dalam memimpin kelompoknya. Hal ini dimaksudkan agar adanya kerjasama dalam  membuat aplikasi Jalan Sehat berbasis Mobile.

Bab 5. Paket pekerjaan, jadwal, dan budget

5.1 Paket pekerjaan

5.2 Ketergantungan/keterkaitan

5.3 Kebutuhan-kebutuhan sumber daya

5.4 Alokasi budget dan sumber daya

5.5 Jadwal
