**1.	Pendahuluan**<br>

1.1	Gambaran proyek<br>
&emsp;Usaha laundry merupakan salah satu bentuk usaha yang cukup menjanjikan, karena semakin banyak peminat jasa laundry. Disini kita akan mengembangkan usaha laundry yang awalnya transaksi masih manual dan untuk mengetahui biaya laundry si client harus mendatangi langsung toko laundry, dan yang mungkin juga ada yang sudah datang ke toko laundry ternyata toko nya tutup karena si client tidak tahu Hari/jam kerja dari toko laundry nya tersebut.
Aplikasi ini dibuat agar lebih efisien waktu dan tenaga, Kenapa lebih efisien?<br>
Karena Aplikasi ini menjadikan client mengetahui informasi jasa laundry satuan dan kiloan tanpa harus datang ke toko laundry nya.<br>
Client juga dapat mengetahui jam buka toko laundry, Client dapat tracking pakaian yang sedang di laundry apakah status nya masih di cuci atau sudah selesai dan siap dijemput. Disediakan juga jasa antar-jemput laundry untuk client yang tidak memiliki waktu untuk mengantar atau menjemput pakaian yang akan di laundry ke toko laundry nya secara langsung.

1.2	Dokumen-dokumen dalam proyek<br>
&emsp;Saat mengerjakan projek ini, pencatatan kegiatan yang telah dilakukan akan ditulis dalam log book kelompok, anggota yang telah mengerjakan tugas sesuai proyek kegiatannya dicatat dalam log book, selain log book dokumen yang berkaitan dengan projek ini meliputi penjadwalan,pembagian tugas,dan referensi-referensi yang berkaitan dengan pembuatan projek ini.<br>
1.3	Evolusi SPMP<br>
&emsp;Dokumen ini bersifat freeware, jadi siapa saja boleh untuk memanfaatkan dokumen ini untuk hal yang positif. Tentu ada hal-hal yang tidak boleh dilakukan dalam pemanfaatan dokumen ini, seperti menjualbelikan dokumen ini secara illegal, ataupun mengubah dokumen tanpa dasar yang jelas.<br>
1.4	Material acuan/referensi<br>
&emsp;Materi yang menjadi acuan dalam pembuatan projek ini menggunakan standar IEEE.
1.5	Definisi dan akronomi<br>
&emsp;IEEE adalah standar yang mendefinisikan lapisan fisik dan sublapisan media akses dari lapisan data-link.

**2.	Organisasi proyek**<br>

**2.1	Model proses**<br>
&emsp;Kami menggunakan Model proses dengan model Spiral dalam membangun sistem ini.<br>
&emsp;&emsp;a.	Definisi Model spiral (spiral model) adalah model proses software yang evolusioner yang merangkai sifat iteratif dari prototipe dengan cara kontrol dan aspek sistematis dari model sekuensial linier. I.2.1.2 Kelebihan Model spiral ini adalah pendekatan yang paling realistik untuk sistem skala besar. Metode ini menggunakan pendekatan evolusioner, sehingga pelanggan dan pengembang dapat mengerti dan bereaksi terhadap suatu resiko yang mungkin terjadi.Model ini membutuhkan konsiderasi langsung terhadap resiko teknis, sehingga diharapkan dapat mengurangi terjadinya resiko yang lebih besar.<br>

**2.2	Struktur organisasi**<br>
&emsp;a.	Projek sponsor <br>
&emsp;b.	Manager<br>
&emsp;c.	Administrator<br>
&emsp;d.	Programming<br>
&emsp;e.	Analisis<br>
&emsp;f.	Tester<br>
**2.3	Batasan dan antarmuka organisasi**<br>
&emsp;a.	Ketua dimana harus mejadi pengawas dari anggota – anggotanya bilamana saat anggota lalai dengan tugas – tugasnya, Ketua berhak menegur dan bagi anggota tidak berhak melawan jika ditegur, dan untuk Ketua sendiri tidak berhak semena-mena /dengan jabatanya.<br> 
&emsp;b.	Tester dimana saat programmer melakukan kesalahan dalam mengkoding tester memiliki tanggung jawab untuk mengecek kesalahan koding – koding yang dilakukan programmer.<br> 
&emsp;c.	Sekertaris dimana bertanggung jawab untuk menyimpan dokumen – dokumen yang diperlukan untuk penggarapan dan ahsil akhir project. <br>
&emsp;d.	Programmer dimana dia bertanggung jawab untuk membuat dan menyempurnakan suatu program.<br> 
&emsp;e.	Analis dimana dia bertugas memberikan gambaran project dan alur pengkoding pada programmer.<br>
**2.4	Lingkup dan tanggungjawab**<br>
&emsp;2.4.1	Penjelasan<br>
Lingkup dan tanggung jawab ini berisi tugas dari setiap elemen anggota dalam pembuatan proyek RPL ini :
&emsp;&emsp;2.4.1.1 Project Sponsor Project Sponsor adalah seorang manajemen puncak (beserta anggota tim jika perlu), yang diserahkan tugas khusus oleh perusahaan sebagai penanggung jawab proyek sistem informasi. Secara prinsip, Direktur Utama atau Presiden Direktur-lah yang harus menjadi Project Sponsor.<br> 
&emsp;&emsp;2.4.1.2 Manager Manager adalah seseorang mempunyai tanggung jawab dan tugas yang besar dalam sebuah tim, tidak hanya terfokus pada hal-hal yang teknis sifatnya. Manager juga harus mampu memajemen tim dengan baik, agar target projek dapat tercapai. Selain itu memberi pengarahan, memonitoring kinerja tim, serta serta membagi tugas juga bagian tanggung jawab dari seorang manager. <br>
&emsp;&emsp;2.4.1.3 Administrator Administrator adalah seseorang yang bertanggung jawab terhadap pengaturan, pembuatan, dan rekam jejak segala jenis dokumen yang terlibat dalam proyek. Mulai dari proposal dan kontrak proyek, sampai dengan hasil sampling atau percobaan dalam proses pembangunan proyek. Disamping dokumen, hal-hal yang berkaitan dengan komunikasi antara anggota proyek dengan perusahaan dan vendors juga harus dikelola oleh Administrator. Agar segalanya berjalan dengan lancar, biasanya Administrator sudah memiliki standar dokumen dan prosedur yang harus diikuti oleh seluruh tim proyek, agar proses administrasi berjalan dengan efektif dan secara efisien.<br>
&emsp;&emsp;2.4.1.4 Sistem Analis Banyak hal yang harus dilakukan oleh seorang sistem analis, terutama yang berkaitan dengan pemecahan masalah. Seorang sistem analis harus mampu menganalisa segala kemungkinan dari pemasalahan yang ada, dan dapat mengasilkan solusi yang tepat dari permasalahan tersebut. Menentukan sistem yang tepat merupakan bagian dari tugas seorang sistem analis, sehingga kinerja tim dapat berjalasan secara efesien. <br>
&emsp;&emsp;2.4.1.5 Programmer Dalam hal ini, seorang programer bertugas untuk mengimplementasikan dari sistem yang sudah dirancang didesain. Programmer dituntut dapat menuliskan code program dengan baik, dan efesien. Hal ini dimaksudakan untuk menghindari terjadinya banyak error dalam proses implementasinya.<br> 
&emsp;&emsp;2.4.1.6 Tester Dalam proyek ini, tester bertugas untuk melakukan pengecekan terhadap sebuah software/aplikasi. Apakah ada error data bug didalamnya, seorang tester harus teliti dalam melakukan tugasnya, apabila ada error yang dilewatkan, maka konsumen akan dirugikan<br>



**3. Proses Manajerial**<br>  
&emsp;&emsp;**3.1 Tujuan dan prioritas manajemen**<br>
&emsp;&emsp;Untuk tahap awal kita membuat konsep dan system dari aplikasi yang kita<br>
&emsp;&emsp;buat kemudian karena keterbatasan waktu jadi kita sesuiakan aplikasi yang <br>
&emsp;&emsp;kita buat itu seefesien mungkin bagi konsumen dan dapat dipahami<br>

  
&emsp;&emsp;**3.2 Asumsi-asumsi,ketergantungan/keterkaitan,danbatasan-batasan**<br>
&emsp;&emsp;Untuk sekarang ini maraknya jasa Laundry tapi masih menggunkan cara <br>
&emsp;&emsp;yang manual, dengan itu maka kami membuat aplikasi yang mempermudah<br>
&emsp;&emsp;jasa laundry dan konsumen dengan menggunakan aplikasi dan online. <br>

&emsp;&emsp;**3.3 Manajemen resiko**<br>
&emsp;&emsp;Keterlambatan pengiriman barang jikalau jauh dan kondisi eksternal <br>
&emsp;&emsp;serta admin harus standbay<br>

  
&emsp;&emsp;**3.4 Mekanisme monitoring dan kontroling**<br>
&emsp;&emsp;Dengan melihat status barang prosesnya sampai mana dan dapat dilihat <br>
&emsp;&emsp;dalam halaman admin<br>

  
&emsp;&emsp;**3.5 Perencanaan staf**<br>
&emsp;&emsp;Staf dibagi menjadi dua yaitu sebagai pengantar laundry dan kasir (admin)<br>

**4. Proses teknis**  <br>
&emsp;&emsp;**4.1 metoda,tool, dan teknik**<br>
&emsp;&emsp;Kemungkinan Kami akan menggunkan Bahasa pemograman PHP dan <br>
&emsp;&emsp;databasenya menggunakan mysql dengan cara menghubungkan antara <br>
&emsp;&emsp;database dengan data yang diprogram<br>

&emsp;&emsp;**4.2 Dokumentasi perangkat lunak**<br>
&emsp;&emsp;Dalam aplikasi ini akan terdapat fitur paket laundry, status laundry, <br>
&emsp;&emsp;pengantar laundry kekonsumen dsb.<br>

  
&emsp;&emsp;**4.3 Fungsi-fungsi pendukung proyek**<br>
&emsp;&emsp;Kami membutuhkan kolaborasi dengan kelompok lain dengan mereka<br>
&emsp;&emsp;membuat client berbasis mobile dan kami membuat server berbasis web<br>

**5. Paket pekerjaan,jadwal,dan budget** <br>
<b><ol>
	5.1 Paket pekerjaan<br></b>
	&emsp;Paket kerja yang akan dihasilkan dengan sebelumnya menentukan work breakdown structure (WBS). Paket kerja yang dibuat dilihat dari sisi teknis, yang meliputi :<br>
	&emsp;&emsp;a. Penentuan waktu, biaya dan seluruh kegiatan yang akan dikerjakan didalam proyek.<br>
	&emsp;&emsp;b. Pengadaan peralatan dan komponen alat pendukung proyek.<br>
	&emsp;&emsp;c. Perancangan software dengan membuat source code dan mengkompilasinya.<br>
	&emsp;&emsp;d. Mengintegrasikan software dengan hardware, serta mengujicobanya.<br>
	&emsp;&emsp;e. Menginstalasikan produk yang telah dihasilkan.<br>
	5.2 Ketergantungan/keterkaitan<br>
	&emsp;Dalam proses pengerjaan proyek yang kami buat ini, keterkaitan dari tugas masing-masing saling membantu agar terbentuknya ketelitian saat mengerjakan dan mendapatkan hasil yang bagus. Berikut adalah perinciaannya.<br>
	&emsp;Manager->	Anggota = Tugas manager adalah untuk mengawasi anggota-anggotanya jika singkata mengerjakan projek anggotanya lalai dengan tugasnya ketua tersebut berhak untuk menegur anggotanya dan yang Menjadi anggota tidak berhak untuk melawan.<br>
	&emsp;Programmer -> Tester = Salah satu tugas Tester yaitu untuk mengecek jika saat programmer salah dalam melakukan pengkodingan tersebut agar bisa langsung di perbaiki.<br>
	&emsp;Administrator -> Manager = Tugas Administrator bertanggung jawab untuk menyiapkan dokumen-dokumen yang akan di gunakan untuk penggarapan dan saat selesai hasil akhir projek.<br>
	&emsp;Analisis -> Programmer = Yang bertugas sebagai analisis yaitu memberi suatu gambaran projek dan pengkodian pada programer.<br>
	&emsp;Tester -> Programer = Bertugas sebagai memberi masukanmasukan kepada Programer untuk membuat program yang sedang di buat supaya bisa menarik konsumen juga bisa menarik konsumen saat program yang dibuat sudah selesai.<br>
	5.3 Kebutuhan-kebutuhan sumber daya<br>
	&emsp;5.3.1 Kebutuhan Sumber Daya Manusia<br>
	&emsp;&emsp;1. Rana Eka Millenio		= Manager, Programmer<br>
	&emsp;&emsp;2. Iis Juita Sari			= Sistem Analis, Programmer<br>
	&emsp;&emsp;3. Najwah					= Administrator, Tester<br>
	&emsp;5.3.2 Kebutuhan Sumber Daya Software<br>
	&emsp;&emsp;1. Sistem Operasi			= Windows 10 or  Higher<br>
	&emsp;&emsp;2. Bahasa Pemerograman		= PHP <br>
	&emsp;&emsp;3. Sofware Pengolah			= Sublime<br>
	&emsp;&emsp;4. Database Engine			= Xampp<br>
	&emsp;5.3.3 Kebutuhan Sumber Daya Hardware<br>
	&emsp;&emsp;1. Processor 				= Minimal Core i3 or Higher<br>
	&emsp;&emsp;2. Memory(RAM)				= Minimal 2GB or Hiher<br>
	&emsp;&emsp;3. Penyimpanan(Hardisk)		= 4GB free Space<br>
	&emsp;&emsp;4. Layar(Monitor)			= Resolusi 1240 x 768 colors<br>
	&emsp;&emsp;5. Keyboard					= Compatible with Windows<br>
	&emsp;&emsp;6. Mouse					= Compatible with Windows<br>
	5.4 Alokasi budget dan sumber daya<br>
	&emsp;Berikut adalah rincian biaya yang diperlukan untuk pengerjaan proyek kami, dapat dilihat pada tabel dibawah ini.<br>
	&emsp;5.4.1 Estimasi Biaya Software<br>
	&emsp;1 Windows 10 or Higher 			=Rp. ,-<br>
	&emsp;2 PHP				 				=Rp. ,-<br>
	&emsp;3 Sublime							=Rp. ,-<br>
	&emsp;4 Xampp 						    =Rp. ,-<br>
	5.5 Jadwal<br>
	&emsp;Untuk menyelesaikan Aplikasi Simulasi  Manajemen Proyek Perangkat Lunak ini diperlukan waktu kurang lebih 4 bulan.
</ol>

