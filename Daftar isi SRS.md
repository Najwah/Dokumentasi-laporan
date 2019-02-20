<h1>***Software Requirement Specification (SRS)***</h1>
<b>1. Pendahuluan</b><br>
&emsp;1.1 Tujuan<br>
&emsp;1.2 Lingkup<br>
&emsp;1.3 Definisi, Akronim, Singkatan<br>
&emsp;1.4 Referensi<br>
&emsp;1.5 Overview<br>
<b>2. Gambaran Umum</b><br>
&emsp;2.1 Perspektif produk<br>
&emsp;&emsp;2.1.1 Antarmuka sistem<br>
&emsp;&emsp;2.1.2 Antarmuka pengguna<br>
&emsp;&emsp;2.1.3 Antarmuka perangkat keras <br>
&emsp;&emsp;2.1.4 Antarmuka perangkat lunak<br>
&emsp;&emsp;2.1.5 Antarmuka komunikasi<br>
&emsp;&emsp;2.1.6 Batasan-batasan memori<br> 
&emsp;&emsp;2.1.7 Operasi-operasi<br>
&emsp;&emsp;2.1.8 Kebutuhan-kebutuhan dalam tahapan adaptasi<br>
&emsp;2.2 Fungsi-fungsi produk<br>
&emsp;2.3 Karakteristik pengguna<br>
&emsp;2.4 Batasan-batasan<br> 
&emsp;2.5 Asumsi-asumsi dan ketergantungan/keterkaitan<br>
&emsp;2.6 Kebutuhan-kebutuhan penyeimbang<br>
<b>3. Kebutuhan lain yang spesifik</b><br>
<b>4.  Informasi pendukung</b><br>
<br>
<br>
<br>

<b>1. Pendahuluan </b> <br>
&emsp;&emsp;Dokumen ini akan berisi Spesifikasi  Kebutuhan Perangkat Lunak<br>
(SKPL) atauSoftware RequirementSpecification (SRS) untuk sistem aplikasi<br>
Laundry. Untukpenamaan dokumen ini selanjutnya akan  digunakan istilah<br>
SKPL. Isi dari dokumen ini sebagian besar adalah terjemahan dari<br>
dokumen IEEE  Std 830-1993.<br>

&emsp;&emsp;&emsp;1.1 Tujuan<br>
&emsp;&emsp;&emsp;&emsp;&emsp; Dokumen spesifikasi kebutuhan perangkat lunak ini  merupakan<br>
&emsp;&emsp;&emsp;dokumen spesifikasi kebutuhan perangkat lunak yang akan<br>
&emsp;&emsp;&emsp;dikembangkan. Dokumen ini digunakan oleh pengembang perangkat<br>
&emsp;&emsp;&emsp;lunak sebagaiacuan teknis untuk pengembang perangkat lunak pada<br>
&emsp;&emsp;&emsp;tahap  selanjutnya.<br>

&emsp;&emsp;&emsp;1.2 Lingkup<br>
&emsp;&emsp;&emsp;&emsp;&emsp; Aplikasi laundry adalah perangkat lunak yang digunakan untuk<br>
&emsp;&emsp;&emsp;mengelola dan mengatur sistem informasi laundry. Usaha jasalaundry ini<br>
&emsp;&emsp;&emsp;menawarkan beragam layanan,  menggunakan jasa  antar jemput, ada juga<br>
&emsp;&emsp;&emsp;dengan perhitungan per kilogram. Kebanyakan usaha laundry<br>
&emsp;&emsp;&emsp;pengelolaannya dilakukan secara manual dansederhana. Hal ini tentunya<br>
&emsp;&emsp;&emsp;tidak praktis dan memakan banyak waktu. Sehingga dari permasalahan ini<br>
&emsp;&emsp;&emsp;dibuatlah sebuah aplikasi laundry yang dapat membantu jasa laundry<br>
&emsp;&emsp;&emsp;dalam meningkatkan pelayanannya. Maka dengan adanya aplikasi laundry<br>
&emsp;&emsp;&emsp;ini pihak jasa laundry dapat lebih praktis dan efektif dalam menyimpan<br>
&emsp;&emsp;&emsp;dan mengeloladata seputar usaha laundrynya, meliputi informasi<br>
&emsp;&emsp;&emsp;customer dan informasi transaksi. Sehingga kegiatan operasional usaha<br> 
&emsp;&emsp;&emsp;ini tetap dapat berjalan dengan lancar.<br>

&emsp;&emsp;&emsp;1.3 Definisi, Akronim, dan Singkatan<br>
&emsp;&emsp;&emsp;&emsp;&emsp; Definisi :<br>
&emsp;&emsp;&emsp;a.&emsp;Laundry adalah usaha yang bergerak dibidang  jasa cuci dan setrika,<br>
&emsp;&emsp;&emsp;&emsp;&emsp;secara umum sebenarnya sepertimencuci di rumah namun karena hasil<br>
&emsp;&emsp;&emsp;&emsp;&emsp;akhir dinilai oleh customer.<br>
&emsp;&emsp;&emsp;b.&emsp;Aplikasi adalah suatu subkelas  perangkat lunak komputer yang<br>
&emsp;&emsp;&emsp;&emsp;&emsp;memanfaatkan kemampuan komputerlangsung untuk melakukan<br>
&emsp;&emsp;&emsp;&emsp;&emsp;suatu tugas yang diinginkan customer<br>
&emsp;&emsp;&emsp;c. &emsp;Sistem Informasi adalah suatu sistem yang dibuat oleh manusia yang<br>
&emsp;&emsp;&emsp;&emsp;&emsp; terdiri dari komponen-komponendalam organisasi untuk mencapai<br>
&emsp;&emsp;&emsp;&emsp;&emsp; suatu tujuan yaitu penyajian informasi. (Leman. 1998, h.3)<br>
&emsp;&emsp;&emsp;d. &emsp;Use Case adalah urutan langkah-langkah yang secara  tindakan saling<br> 
&emsp;&emsp;&emsp;&emsp;&emsp; terkait, baik terotomatisasimaupun secara manual, untuk tujuan<br>
&emsp;&emsp;&emsp;&emsp;&emsp; melengkapi satu tugas bisnis tunggal. (Jeffery  L. Whitten. 2004,h.257)<br>

&emsp;&emsp;&emsp;&emsp;&emsp;Akronim dan Singkatan :<br>
&emsp;&emsp;&emsp;&emsp;a. &emsp;SKPL &emsp; : Spesifikasi  Kebutuhan  Perangkat  Lunak<br>
&emsp;&emsp;&emsp;&emsp;b. &emsp;SQL &emsp;&emsp;: Structure Query Language<br>
&emsp;&emsp;&emsp;&emsp;c. &emsp;SRS &emsp;&emsp; : Software Requirement Specification<br>

&emsp;&emsp;&emsp;1.4 Referensi<br>

&emsp;&emsp;&emsp;[https://klasiber.uii.ac.id/core/course/view.php?id=142717](https://klasiber.uii.ac.id/core/course/view.php?id=142717)<br>
&emsp;&emsp;&emsp;IEEE Std 830-1998, IEEE  Recommended Practice for Software <br>
&emsp;&emsp;&emsp;Requirements Specifications.<br>
&emsp;&emsp;&emsp;ISO/IEC/IEEE 29418-2011, System and software engineering<br>

&emsp;&emsp;&emsp;1.5 Overview<br>
&emsp;&emsp;&emsp;&emsp;&emsp; Dokumen SPL ini dibagi menjadi lima bagian utama, yaitu :<br>
&emsp;&emsp;&emsp; -&emsp;Bagian pertama berisi penjelasan tentang dokumen SPL yang<br>
&emsp;&emsp;&emsp;&emsp;&emsp;mencakup tujuan  pembuatan dokumenini, lingkup masalah yang<br>
&emsp;&emsp;&emsp;&emsp;&emsp;diselesaikan oleh  perangkat lunak yang dikembangkan, definisi,<br>
&emsp;&emsp;&emsp;&emsp;&emsp;referensi dan deskripsi umum.<br>
&emsp;&emsp;&emsp;-&emsp; Bagian kedua berisi penjelasan secara umum mengenai aplikasi laundry<br>
&emsp;&emsp;&emsp;&emsp;&emsp;yang akan dikembangkan,meliputi fungsi dari perangkat lunak,<br>
&emsp;&emsp;&emsp;&emsp;&emsp;karakteristik customer, batasan dan asumsi yang diambil dalam<br>
&emsp;&emsp;&emsp;&emsp;&emsp;pengembangan perangkat lunak.<br>
&emsp;&emsp;&emsp;-&emsp; Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih<br>
&emsp;&emsp;&emsp;&emsp;&emsp;rinci.<br>
&emsp;&emsp;&emsp;-&emsp;Bagian keempat berisi model analisis dari perangkat lunak ini.<br>
&emsp;&emsp;&emsp;-&emsp;Bagian kelima merupakan bagian terakhir yang berisi  lampiran serta <br>
&emsp;&emsp;&emsp;&emsp; penjelasan dan penggambaran layarcustomer.<br>
