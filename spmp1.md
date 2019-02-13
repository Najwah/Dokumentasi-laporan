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



