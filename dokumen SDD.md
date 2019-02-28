Rincian SDD
<b>1. Pendahuluan</b><br>
&emsp;1.1 Tujuan<br>
&emsp;1.2 Lingkup<br>
&emsp;1.3 Definisi, Akronim, Singkatan<br>
<b>2. Referensi</b><br>
<b>3. Penjelasan Dekomposisi</b><br>
&emsp;3.1 Dekomposisi Modul<br>
&emsp;&emsp;3.1.1 Deskripsi Modul 1<br>
&emsp;&emsp;3.1.2 Deskripsi Modul 2<br>
&emsp;3.2 Dekomposisi Proses Konkuren<br>
&emsp;&emsp;3.2.1 Deskripsi Proses 1<br>
&emsp;&emsp;3.2.2 Deskripsi Proses 2<br>
&emsp;3.3 Dekomposisi Data<br>
&emsp;&emsp;3.3.1 Deskripsi Entri Data 1<br>
&emsp;&emsp;3.3.1 Deskripsi Entri Data 2<br>
<b>4. Deskripsi Ketergantungan/Keterkaitan</b><br>
&emsp;4.1 Keterkaitan inter modul<br>
&emsp;4.2 Keterkaitan inter proses<br>
&emsp;4.3 Keterkaitan data<br>
<b>5.	Deskripsi Antarmuka</b><br>
&emsp;5.1 Antarmuka modul<br>
&emsp;&emsp;5.1.1 Deskripsi modul 1<br>
&emsp;&emsp;5.1.2 Deskripsi modul 2<br>
&emsp;5.2 Antarmuka proses<br>
&emsp;&emsp;5.2.1 Deskripsi proses 1<br>
&emsp;&emsp;5.2.2 Deskripsi proses 2<br>
<b>6.	Desain detil/rinci</b><br>
&emsp;6.1  Rinci modul<br>
&emsp;&emsp;6.1.1 Rinci modul 1<br>
&emsp;&emsp;6.1.2 Rinci modul 2<br>
&emsp;6.2 Desain data secara rinci<br>
&emsp;&emsp;6.2.1 Rinci entiti data 1<br>
&emsp;&emsp;6.2.2 Rinci entiti data 2<br>
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

<b>2. Referensi</b><br>

&emsp;&emsp;&emsp;[https://klasiber.uii.ac.id/core/course/view.php?id=142717](https://klasiber.uii.ac.id/core/course/view.php?id=142717)<br>
&emsp;&emsp;&emsp;IEEE Std 830-1998, IEEE  Recommended Practice for Software <br>
&emsp;&emsp;&emsp;Requirements Specifications.<br>
&emsp;&emsp;&emsp;ISO/IEC/IEEE 29418-2011, System and software engineering<br>
