1). perbedaan IaaS, SaaS, dan PaaS?.
IaaS - Infrastructure-as-a-Service - Layanan cloud yang memungkinkan pengguna 
mendapatkan akses ke infrastruktur mereka sendiri - komputer, sumber daya 
jaringan, penyimpanan. Perlu dicatat bahwa ini biasanya sumber daya virtual, 
tetapi bisa jadi sumber daya nyata, fisik.

PaaS - Platform-as-a-Service - Layanan cloud yang mengabstraksi infrastruktur 
(pengguna tidak bisa melihat komputer, loadbalancers, dll.) Melainkan menyediakan 
platform pengembangan perangkat lunak. Dimungkinkan untuk membuat kode dan 
menjalankan aplikasi pada PaaS dan sistem memastikan bahwa aplikasi memiliki 
infrastruktur yang diperlukan untuk membuatnya berjalan dan skala.

SaaS - Software-as-a-Service - Layanan cloud yang memberikan pengguna akses ke 
perangkat lunak dengan layanan mandiri, sesuai permintaan. Ini bisa berupa 
aplikasi tunggal atau memberikan katalog perangkat lunak yang dapat dipilih 
pengguna.

2). SaaS Platform Architecture.

SaaS adalah model lisensi dan pengiriman perangkat lunak di mana perangkat lunak dilisensikan berdasarkan berlangganan dan di-host secara terpusat. Pengguna dapat mengaksesnya dengan bantuan browser web.

SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan pesan, perangkat lunak manajemen, virtualisasi dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan infrastruktur sebagai layanan (IaaS), platform sebagai layanan (PaaS) , desktop sebagai layanan (DaaS).

Ini terkait dengan penyedia layanan aplikasi (ASP) yang menyediakan aplikasi "shrink-wrap" untuk pengguna bisnis melalui Internet. Perangkat lunak yang dikirimkan melalui Internet lebih awal memiliki fitur yang mirip dengan aplikasi di tempat dibandingkan dengan aplikasi SaaS. Karena ini awalnya dibangun sebagai aplikasi penyewa tunggal, kemampuan mereka untuk berbagi data terbatas. Aplikasi SaaS adalah instance tunggal, arsitektur multi-tenant yang memberikan pengalaman kaya fitur yang kompetitif dengan aplikasi on-premise. Aggregator menggabungkan penawaran SaaS dari vendor yang berbeda dan menawarkannya sebagai bagian dari platform aplikasi terpadu.

Penyedia SaaS menyimpan aplikasi dan data secara terpusat - tambalan penyebaran. Mereka meningkatkan ke aplikasi secara transparan, memberikan akses ke pengguna akhir melalui Internet. Banyak vendor menyediakan API yang digunakan pengembang untuk membuat aplikasi komposit. Ini berisi berbagai mekanisme keamanan untuk keamanan data selama transmisi dan penyimpanan.


Arsitektur SAAS:
![](https://github.com/mayamonika998/tekn-cloud-computing/blob/master/minggu-02/SAAS%20Arsitektur.png)


Dengan model ini, satu versi aplikasi, dengan satu konfigurasi digunakan untuk semua pelanggan. Aplikasi ini diinstal pada banyak mesin untuk mendukung skalabilitas (disebut penskalaan horizontal). Dalam beberapa kasus, versi kedua aplikasi diatur untuk menawarkan kelompok pelanggan tertentu dengan akses ke versi pra-rilis aplikasi untuk tujuan pengujian. Dalam model tradisional ini, setiap versi aplikasi didasarkan pada kode unik. Meskipun pengecualian, beberapa solusi SaaS tidak menggunakan multitenancy, untuk mengelola secara efektif sejumlah besar pelanggan di tempat. Apakah multitenancy merupakan komponen yang diperlukan untuk perangkat lunak-sebagai-layanan adalah topik kontroversi.

Ada dua varietas utama SaaS:
![](https://github.com/mayamonika998/tekn-cloud-computing/blob/master/minggu-02/SAAS%20Vertikal%20dan%20Horisontal.png)


1. SaaS Vertikal
Perangkat Lunak yang menjawab kebutuhan industri tertentu (mis. Perangkat lunak untuk kesehatan, pertanian, real estat, industri keuangan)
2. SaaS Horisontal
Produk-produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.

Manfaat SAAS:

Ini menawarkan peluang besar bagi organisasi dari semua ukuran untuk mengalihkan risiko akuisisi perangkat lunak, dan untuk memindahkan TI dari pusat biaya reaktif menjadi bagian perusahaan yang proaktif dan bernilai tambah. Secara tradisional, menyebarkan sistem perangkat lunak skala besar telah menjadi tugas utama. Menyebarkan sistem ini di perusahaan besar membutuhkan biaya lebih besar. Waktu, staf, dan persyaratan anggaran untuk penyebaran sebesar ini mewakili risiko yang signifikan bagi organisasi dalam ukuran berapa pun, dan sering kali menempatkan perangkat lunak seperti itu di luar jangkauan organisasi yang lebih kecil yang jika tidak dapat diturunkan darinya banyak utilitas. Model pengiriman berdasarkan permintaan mengubah beberapa hal ini. Aplikasi SaaS tidak memerlukan penyebaran infrastruktur besar di lokasi klien.

Integrasi dapat direncanakan dan dilaksanakan dengan upaya minimal, menciptakan salah satu interval waktu-ke-nilai sesingkat mungkin untuk investasi TI utama. Ini juga memungkinkan sejumlah vendor SaaS untuk menawarkan "test drive" bebas risiko (dan seringkali secara harfiah gratis) dari perangkat lunak mereka untuk periode terbatas, seperti 30 hari. Memberi pelanggan kesempatan untuk mencoba perangkat lunak sebelum mereka membelinya membantu menghilangkan banyak risiko seputar pembelian perangkat lunak.

Bagaimana SaaS Mempengaruhi IT?

Setelah Anda membuat keputusan untuk mengejar SaaS, langkah selanjutnya adalah mempersiapkan transisi dengan menilai bagaimana penyebaran akan mempengaruhi aset TI yang ada. Melakukan uji tuntas adalah bagian rutin dari setiap proyek penyebaran infrastruktur TI yang sukses. Beberapa area yang harus ditangani dalam daftar periksa uji tuntas meliputi, Standar keamanan data: Memindahkan data bisnis penting "di luar tembok" menimbulkan risiko kehilangan data atau paparan informasi sensitif yang tidak disengaja. Nilai kebutuhan keamanan data Anda, dan pastikan bahwa penyedia memiliki langkah-langkah untuk memenuhi standar yang Anda tetapkan. Layanan pelaporan: Karena SaaS melibatkan pemberian kontrol langsung atas beberapa data Anda, pelaporan yang akurat dan bermanfaat sangat penting. Tentukan layanan pelaporan apa yang ditawarkan penyedia, dan apakah mereka kompatibel dengan persyaratan intelijen bisnis Anda.

Dampak pada Peran dan Tanggung Jawab TI

Menambahkan SaaS dapat menyebabkan perubahan mendasar dalam peran departemen TI sebagai penyedia layanan informasi. Di masa lalu, sifat penyebaran perangkat lunak telah menempatkan petugas informasi kepala dalam peran penjaga gerbang. Mereka dapat melakukan veto dengan menyatakan bahwa mereka tidak akan meng-host-nya di pusat data. Dengan SaaS, kontrol pusat data tidak harus sama dengan kontrol atas seluruh lingkungan komputasi perusahaan. Ini dapat menyebabkan penjaga gerbang takut kehilangan kendali.

3). Cara membangun Aplikasi SaaS berbasis cloud.