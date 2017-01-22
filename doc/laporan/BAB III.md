<span id="_Toc408562280" class="anchor"><span id="_Toc410625516" class="anchor"></span></span>BAB III
=====================================================================================================

<span id="_Toc408562281" class="anchor"><span id="_Toc410625517" class="anchor"></span></span>ANALISIS DAN PERANCANGAN
======================================================================================================================

<span id="_Toc408562282" class="anchor"><span id="_Toc410625518" class="anchor"></span></span>3.1 Analisis
----------------------------------------------------------------------------------------------------------

Tahap analisis merupakan suatu tahap pembahasan terhadap suatu sistem yang akan dibuat. Tahap ini bertujuan untuk mengetahui sistem, proses yang terlibat dalam aplikasi serta hubungan antar proses. Analisis juga dapat didefinisikan sebagai penguraian dari suatu sistem di dalam bagian-bagian komponennya dengan maksud untuk mengidentifikasikan dan mengevaluasi masalah-masalah, hambatan-hambatan yang terjadi serta kebutuhan yang diharapkan sehingga dapat diusulkan perbaikan.

Analisis adalah tahap yang sangat penting karena suatu kesalahan dalam tahap ini akan mempengaruhi pada tahap berikutnya. Penelitian juga membuktikan bahwa kesalahan yang diperbaiki setelah tahap analisa akan memakan biaya yang lebih besar dari pada jika di perbaiki saat dilakukan analisa.

1.  **Analisis sistem yang sedang berjalan**

Analisis sistem ini digunakan untuk mengetahui bagaimana sistem kenaikan pangkat yang digunakan sekarang di PO KRAMAT DJATI, adapun alur dari sistem pada ini adalah sebagai berikut :

1.  **Analisis *Procedure***

<!-- -->

1.  **Analisis sistem yang akan dibangun pada prosedur login**

Pada prosedur login admin melibatkan 2 entitas (aktor) yaitu Admin ( Divisi HRD), dan pegawai pada PO Kramat Djati. Dimana setiap entitas (aktor) tersebut memiliki hak akses yang berbeda terhadap sistem atau aplikasi yang dibuat.

*Gambar 3.1 prosedur login yang sedang berjalan*

1.  **Analisis sistem yang berjalan pada prosedur penilaian kinerja pegawai**

    Pada prosedur ini, pertama admin masuk ke laman login dan memasukkan username dan password, setelah username dan password valid admin akan masuk menu utama dan memilih kinerja, setelah itu admin memilih kriteria penilaian yang diinginkan, kemudian admin menginputkan hasil penilaian kinerja pegawai selama satu bulan dan aplikasi akan menyimpan data kinerja pegawai tersebut

*Gambar 3.2 prosedur kinerja penilaian pegawai yang sedang berjalan*

1.  **Analisis Sistem Yang Berjalan Pada Kenaikan Pangkat Pegawai**

Pada kenaikan pangkat pegawai, HRD melihat hasil kinerja pegawai selama satu bulan, didalam kinerja penilaian pegawai terdapat beberapa kriteria sebagai bahan pertimbangan, kemudian HRD memasukkan kriteria poin tersebut, setelah data sesuai HRD akan melihat hasil nilai dari pegawai apakah akan dinaikkan pangkat atau tidak dan pegawai akan melihat hasilnya.

*Gambar 3.3 prosedur kenaikan pangkat yang sedang berjalan*

1.  **3.1.1.2 Analisis Dokumen yang Digunakan**

Dokumen yang digunakan untuk membangun aplikasi ini sangat sederhana. Dokumen ini sangat berguna sekali karena dapat sebagai dasar pembuatan aplikasi. Dokumen yang dibutuhkan saat pembangunan aplikasi sebagai berikut :

1.  Dokumen Data Pegawai

2.  Dokumen keahlian khusus pegawai

3.  Dokumen Kinerja Penilaian pegawai

4.  Dokumen Nilai Pegawai

    1.  ### Analisis Sistem yang akan Dibangun

Dari analisis yang telah dilakukan, maka dapat dibuat sebuah analisis prosedur sistem kenaikan pengkat yang akan dibangun pada “PO Kramat Djati” yang menggambarkan proses penilaian dan kenaikan pangkat pegawai. Adapun alur proses yang akan dibangun adalah sebagai berikut :

**Flowmap yang akan dibangun**

1.  **Flowmap yang akan dibangun pada proses data pegawai**

Pertama-tama pegawai masuk ke menu login, setelah login pegawai akan masuk ke menu data pegawai. Pegawai dapat menginputkan datanya kemudian pegawai dapat memasukkan data keahlian khusus yang ia miliki.

<img src="./media/image4.PNG" width="357" height="403" />

*Gambar 3.4 prosedur data pegawai yang akan dibangun *

1.  **Flowmap yang akan dibangun pada proses kinerja pegawai**

    Pegawai masuk ke menu kinerja pegawai, kemudian umtuk memenuhi syarat pegawai memasukan data riwayat pendidikannya, prestasi kerja, pengalaman. Setelah itu data disimpan. Kemudian admin akan melihat data yang telah diinput pegawai, setelah itu admin akan menambahkan persyaratan tambahan untuk memenuhi kenaikan pangkat

*Gambar 3.5 prosedur kinerja pegawai* *yang akan dibangun*

1.  **Flowmap yang akan dibangun pada proses kenaikan pangkat pegawai**

    Admin masuk ke menu kenaikan pangkat. Admin mencari data pegawai yang akan diproses,. Kemudian admin menginputkan syarat pendukung kenaikan pangkat pegawai. Setelah itu akan tampil hasil apakah pegawai layak naik pangkat atau tidak.

*Gambar 3.6 prosedurkenaikan pangkat pegawai yang akan dibangun*

1.  **Kebutuhan Fungsional (*Functional Requirements*)**

Analisis kebutuhan fungsional merupakan suatu kebutuhan yang berhubungan dengan kebutuhan sistem yang akan dibuat. Dimana menjabarkan mengenai fungsi-fungsi yang dapat mendukung jalannya sistem, adapun kebutuhan fungsional yang akan dibuat yaitu pengelolaan data sebagai berikut

1.  Data pegawai : Menu ini dapat digunakan untuk mendata pegawai yang ada di PO Kramat Djati. Admin dapat menambah atau mengahapus data tersebut.

2.  Data kinerja pegawai : Menu ini dapat menampilkan nilai dari kinerja pegawai. Admin dapat memasukan nilai dari pegawai PO Kramat Djati

3.  Data pendukung kenaikan pangkat : Menu ini adalah syarat-syarat yang dibutuhkan pegawai untuk dapat naik pangkat

4.  Data kenaikan pangkat pegawai : Menu ini dapat menampilkan kelayakan pegawai untuk naik pangkat atau tidak

**3.1.2.2 Kebutuhan Non-Fungsional (*Non- Functional Requirement*)**

Analisis kebutuhan non fungsional dilakukan untuk mengetahui spesifikasi kebutuhan untuk sistem. Spesifikasi kebutuhan melibatkan analisis perangkat keras/*hardware*, analisis perangkat lunak/*software*, analisis pengguna/*User*. Adapun kebutuhan fungsional yang akan dibuat adalah sebagai berikut

1.  Perangkat Lunak (*software*) meliputi :

<!-- -->

1.  Perangkat Lunak menggunakan *Framework Laravel 5.3*

2.  Sistem operasi menggunakan *Microsoft Windows 7 Ultimate* 32-bit

3.  *Database* menggunakan *Mysql*

4.  Flowmap dan diagram dapat digambarkan pada *Star UML* atau *Microsoft Visio 2007.*

5.  Disain Antar Muka menggunakan *Photoshop CS*

<!-- -->

1.  Perangkat Keras (*hardware*) meliputi :

<!-- -->

1.  Intel Core i3

2.  Memory 2 GB RAM

    1.  **Perancangan**

        Perancangan merupakan analisis untuk menggambarkan kebutuhan-kebutuhan dalam suatu aplikasi yang akan dibangun. Perancangan ini fokus terhadap perancangan data yang ada pada aplikasi, tahap perancangan data pada perangkat lunak tersebut dipakai ke dalam pemodelan yang umum yang digunakan yaitu menggunakan : *Use Case Diagram, Class Diagram, Sequence Diagram, Collaboration Diagram, Activity Diagram, Statechart Diagram, Componen Diagram,* dan *Deployment Diagram.*

        1.  **Use Case Diagram**

<img src="./media/image7.jpg" width="545" height="424" />

*Gambar 3.7 Use Case*

### <span id="_Toc408562302" class="anchor"><span id="_Toc410625523" class="anchor"></span></span>Definisi Aktor

Definisi aktor merupakan penjelasan dari apa yang dilakukan oleh aktor-aktor yang terlibat dalam perangkat lunak yang dirancang. Adapun deskripsi dari aktor-aktor yang terlibat dalam aplikasi kenaikan pangkat pegawai PO

| **No** | **Aktor** | **Deskripsi**                       |
|--------|-----------|-------------------------------------|
| 1.     | Admin     | -   Mengelola system                
                                                           
                      -   Mengelola data pegawai           
                                                           
                      -   Mengelola data kinerja pegawai   
                                                           
                      -   Mengelola data kenaikan pankat   |
| 2.     | Pegawai   | -   Melihat dan kelola data pegawai 
                                                           
                      -   Melihat kinerja                  |

Kramat Djati adalah sebagai berikut :

##### Tabel 3.1 Definisi Aktor

### Definisi Use Case

> *Use case* yang ada dalam diagram didefinisikan pada tabel di bawah ini :

##### Tabel 3.2 Definisi Use Case

| No  | No.definisi | Use Case                       | Keterangan                                                                                                                                      |
|-----|-------------|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.  | UC-01       | *Login*                        | Merupakan proses pemberian hak akses kepada *user* dan *Validasi* untuk semua *user* yang akan mengakses bagian tertentu dalam sistem.          |
| 2.  | UC-02       | Kelola Data Pegawai            | Merupakan aktivitas yang dilakukan untuk mengelola data pegawai yang ada di PO Kramat Djati. Data tersebut akan disimpan di database.           |
| 3.  | UC-03       | Kelola Data Kinerja Pegawai    | Merupakan serangkaian aktivitas yang dilakukan untuk mengelola data kinerja pegawai,                                                            |
| 4.  | UC-04       | Kelola data kenaikan pangkat   | Merupakan aktivitas yang dilakukan untuk mengelola kenaikan pangkat pegawai yang diambil dari data kinerja pegawai dan syarat pendukung lainnya |
| 6.  | UC-06       | Hasil Kenaikan pangkat         | Merupakan aktivitas yang dilakukan untuk mengetahui layak atau tidaknya pegawai dalam naik pangkat                                              |

###  <span id="_Toc408562306" class="anchor"><span id="_Toc410625525" class="anchor"></span></span>Skenario Use Case Diagram

Skenario untuk masing-masing *use case* dari Pengembangan Aplikasi Kinerja Pegawai Bagian PO Kramat Djati adalah sebagai berikut:

1.  **Skenario Use Case Login**

Skenario dalam diagram *use case* login ada pada tabel dibawah ini

##### Tabel 3.3 Skenario Use Case Login

| **Identifikasi**                         |
|------------------------------------------|
| Nomor                                    |
| Nama                                     |
| Tujuan                                   |
| Deskripsi                                |
| Aktor                                    |
| **Skenario**                             |
| Kondisi Awal                             |
| **Aksi Aktor**                           |
| Aktor meminta *form login* kepada sistem |
| Memasukan *Username* dan *Password*      |
| Jika salah, kembali ke *form login.*     |
| Kondisi Akhir                            |

**3.2.1.3.2 Skenario Use Case Kelola Data Pegawai**

Skenario dalam diagram *use case* kelola data pegawai ada pada tabel dibawah ini

##### Tabel 3.4 Skenario Use case Kelola Data Pegawai

| **Identifikasi**                                                                                   |
|----------------------------------------------------------------------------------------------------|
| Nomor                                                                                              |
| Nama                                                                                               |
| Tujuan                                                                                             |
| Deskripsi                                                                                          |
| Aktor                                                                                              |
| **Skenario**                                                                                       |
| Kondisi Awal                                                                                       |
| **Aksi Aktor**                                                                                     |
| Admin memilih menu Data Pegawai                                                                    |
| Admin memilih tool simpan, ubah, dan hapus untuk menyimpani data, ubah data, dan hapus data pegawi |
| Pegawai melihat data pegawai                                                                       |
| Kondisi Akhir                                                                                      |

**3.2.1.3.3 Skenario Use Case Kelola data Kinerja Pegawai**

Skenario dalam diagram *use case* kelola data absensi ada pada tabel dibawah ini

##### Tabel 3.5 Skenario Use case Kelola Data Kinerja Pegawai

| **Identifikasi**                                                                              |
|-----------------------------------------------------------------------------------------------|
| Nomor                                                                                         |
| Nama                                                                                          |
| Tujuan                                                                                        |
| Deskripsi                                                                                     |
| Aktor                                                                                         |
| **Skenario**                                                                                  |
| Kondisi Awal                                                                                  |
| **Aksi Aktor**                                                                                |
| Admin memailih menu Data Kinerja *Pegawai*                                                    |
| Admin memilih menu penilaian kinerja penyelesaian pekerjaan dan mengisi hasil kinerja pegawai |
| Admin memilih menu penilaian kinerja kepemimpinan dan mengisi hasil kinerja pegawai           |
| Admin memilih menu penilaian kinerja sikap dan kesopan dan mengisi hasil kinerja pegawai      |
| Admin memilih menu penilaian kinerja pengetahuan dan mengisi hasil kinerja pegawai            |
| Kondisi Akhir                                                                                 |

1.  **Skenario Use Case Kelola data Kenaikan pangkat **

Skenario dalam diagram *use case* kelola data absensi ada pada tabel dibawah ini

##### Tabel 3.6 Skenario Use case Kelola Data Kenaikan Pangkat

| **Identifikasi**                              |
|-----------------------------------------------|
| Nomor                                         |
| Nama                                          |
| Tujuan                                        |
| Deskripsi                                     |
| Aktor                                         |
| **Skenario**                                  |
| Kondisi Awal                                  |
| **Aksi Aktor**                                |
| Admin memailih menu data kenaikan pangkat     |
| Admin menginputkan data hasil kinerja pegawai |
| Kondisi Akhir                                 |

1.  **Skenario Use Case hasil kenaikan pangkat **

Skenario dalam diagram *use case* kelola data absensi ada pada tabel dibawah ini

##### Tabel 3.7 Skenario Use case hasil kenaikan pangkat

| **Identifikasi**                              |
|-----------------------------------------------|
| Nomor                                         |
| Nama                                          |
| Tujuan                                        |
| Deskripsi                                     |
| Aktor                                         |
| **Skenario**                                  |
| Kondisi Awal                                  |
| **Aksi Aktor**                                |
| Admin memailih menu data kenaikan pangkat     |
| Admin menginputkan data hasil kinerja pegawai |
| Kondisi Akhir                                 |

**3.2.2 Class Diagram**

<img src="./media/image8.jpg" width="546" height="477" />

> *Gambar 3.8 Class Diagram*

Class diagram ini menggambarkan tentang hubungan dalam sistem yang akan dibangun. Dalam sistem yang akan dibangun Admin, Pegawai, login merupakan bagian dari sistem atau dengan kata lain jika tidak ada tiga pendukung tersebut maka sistem tidak akan berjalan. Sedangkan sistem terdapat menu kategori yang berisi , data pegawai, data kinerja pegawai dan data kenaikan pangkat.

### <span id="_Toc408562325" class="anchor"><span id="_Toc410625535" class="anchor"></span></span>3.2.3 Sequence Diagram

**3.2.3.1 Sequence Diagram Kelola Data Kinerja Pegawai**

Berikut ini merupakan *sequence diagram* kelola data kinerja pegawai menjelaskan hubungan antara admin, dengan kelola data kinerja pegawai

<img src="./media/image9.jpg" width="519" height="420" />

> *Gambar 3.9 Sequence Diagram kinerja pegawai*

Keterangan :

1.  Admin login dan masuk ke menu kelola kinerja pegawai

2.  Koneksi database

3.  Konfirmasi database

4.  Admin melihat dan mencari data pegawai yang akan diolah

5.  Koneksi database pegawai

6.  Konfirmasi pegawai dari database

7.  Admin memasukkan data persyaratan tambahan

8.  Koneksi database

9.  Konfirmasi database

10. Data persyaratan yang diinputkan tersimpan

11. Admin maemasukan data persyaratan tambahan

12. Koneksi Database

13. Konfirmasi Database

14. Data Tersimpan

15. Hasil dari kinerka pegawai akan muncul

    1.  **Sequence Diagram Kelola Data Kenaikan Pangkat **

        Berikut ini merupakan *sequence diagram* kelola data kenaikan pangkat pegawai menjelaskan hubungan antara admin, dan menu kenaikan pangkat

<img src="./media/image10.jpg" width="559" height="472" />

> *Gambar 3.10 Sequence diagram kenaikan pangkat*

Keterangan :

1.  Admin login dan masuk ke menu kenaikan pangkat

2.  Koneksi databse

3.  Konfirmasi database

4.  Admin melihat data pegawai

5.  Admin mencari data pegawai yang akan diproses

6.  Koneski ke database kenaikan pangkat

7.  Konfirmasi data

8.  Admin memasukkan data pendukung pertama untuk kenaikan pangkat pegawai

9.  Admin memasukkan data pendukung kedua untuk kenaikan pangkat pegawai

10. Admin memasukkan data pendukung ketiga untuk kenaikan pangkat pegawai

11. Koneksi ke database kenaikan pangkat

12. Konfirmasi data

13. Data tersimpan

14. Admin dapat melihat hasil kenaikan pangkat

    1.  **Collaboration Diagram**

**3.2.4.1 Collaborarion Diagram Kelola Kinerja Pegawai**

Berikut ini merupakan *Collaboration diagram* kelola kinerja pegawai yang menjelaskan proses admin mengelola kinerja pegawai

<img src="./media/image11.jpg" width="510" height="374" />

> *Gambar 3.11 Collaboration Diagram Kinerja Pegawai*

Keterangan :

1.  Admin login dan masuk ke menu kinerja pegawai

2.  Koneksi ke database kinerja pegawai

3.  Konfirmasi database

4.  Insert persyaratan tambahan untuk kinerja pegawai

5.  Validasi data kinerja sudah selesai

6.  Data kinerja pegawai sudah tersimpan

**3.2.4.2 Collaborarion Diagram Kelola Kenaikan Pangkat**

Berikut ini merupakan *Collaboration diagram* kelola kenaikan pangkat pegawai yang menjelaskan proses admin mengelola kinerja pegawai

<img src="./media/image12.jpg" width="546" height="348" />

> *Gambar 3.12 Collaboration Diagram kenaikan pangkat pegawai*

Keterangan :

1.  Admin login dan masuk ke menu kenaikan pangkat pegawai

2.  Koneksi ke database kenaikan pangkat

3.  Konfirmasi database

4.  Insert persyaratan data data pendukung untuk kenaikan pangkat yang terdiri dari data pelatihan, kursus, dan sertifikat

5.  Validasi data kenaikan pangkat sudah selesai

6.  Data kenaikan pangkat sudah tersimpan

<img src="./media/image13.jpg" width="538" height="230" />**3.2.5 Statechart Diagram**

**3.2.5.1 Statechart Diagram Kinerja Pegawai**

> *Gambar 3.13 Statechart diagram kinerja pegawai*

**3.2.5.2 Statechart Diagram Kenaikan Pangkat Pegawai**

<img src="./media/image14.jpg" width="546" height="233" />

> *Gambar 3.14 Statechart kenaikan pangkat *

1.  **Activity Diagram **

    <img src="./media/image15.jpg" width="498" height="450" />

    **3.2.6.1 Activity Diagram Kinerja Pegawai**

> *Gambar 3.15 Activity diagram kinerja pegawai*

**3.2.6.2 Activity Diagram Kenaikan Pangkat Pegawai**

> <img src="./media/image16.jpg" width="514" height="505" />*Gambar 3.16 Activity diagram kenaikan pangkat*

1.  **Component Diagram**

    <img src="./media/image17.jpg" width="546" height="396" />

*Gambar 3.17 Componet diagram*

1.  **Deployment Diagram**

> <img src="./media/image18.jpg" width="546" height="270" />*Gambar 3.18 Deployment diagram*

1.  **Struktur menu**

    <img src="./media/image19.PNG" width="482" height="326" />

*Gambar 3.19 Struktur menu*

**3.2.10 Perancangan Antarmka**

<img src="./media/image20.jpeg" width="546" height="371" /> **3.2.10.1 Halaman Utama**

*Gambar 3.20 perancangan antar muka Halaman Utama*

**
**

<img src="./media/image21.jpeg" width="546" height="371" />**3.2.10.2 Halaman Login**

*Gambar 3.21 perancangan antar muka Login*

Algoritma :

Begin if

Pilih menu : Masuk login

If admin

Then menampilkan Menu home admin

Else if

Pegawai Then menampilkan menu home pegawai

Pilih Item close: Keluar Halaman

End If

End

*
*

> <img src="./media/image22.jpeg" width="546" height="371" />**3.2.10.3 Halaman register**

*Gambar 3.22 perancangan antar muka register*

Algoritma :

> If pilih tombol : register
>
> Then regiter berhasil
>
> Else if register admin
>
> Then masuk menu home admin
>
> Else register pegawai
>
> Then masuk menu home pegawai
>
> End if
>
> End

<img src="./media/image23.jpeg" width="546" height="371" />**3.2.10.4 Halaman admin**

*Gambar 3.23 perancangan antar muka halaman admin*

Algoritma :

Begin if

Pilih menu : profile

Then menampilkan Menu profile yang melakukan login

Else if

Pilih menu : data pegawai

Then menampilkan menu data pegawai

Else if

Pilih menu : syarat kenaikan pangkat

Then menampilkan menu syarat syarat kenaikan pangkat

Else

Pilih menu : keputusan kenaikan pangkat

Then menampilkan keputusan kenaikan pangkat sesuai rekomendasi

Pilih Item logout: kembali ke menu utama

End If

End

<img src="./media/image24.jpeg" width="546" height="371" />**3.2.10.5 Halaman profile yang melakukan login**

*Gambar 3.24 perancangan antar muka profile yang melakukan login*

Algoritma :

Begin if

Pilih menu : back

Then kembali ke menu sebelumnya

End if

<img src="./media/image25.jpeg" width="546" height="371" />**3.2.10.6 Halaman Data Pegawai**

*Gambar 3.25 perancangan antar muka Data Pegawai*

Algoritma :

Begin if

Pilih menu : data pegawai

Then menampilkan data data pegawai

Else if

Pilih menu : penilaian kinerja pegawai

Then menampilkan form penilaian

End If

End

*
*

<img src="./media/image26.jpeg" width="546" height="371" />**3.2.10.7 Halaman Menambahkan data pegawai**

*Gambar 3.26 perancangan antar muka meambahkan data pegawai*

Algoritma :

Begin if

Pilih menu : create

Then menambahkan data berhasil

End If

End

<img src="./media/image27.jpeg" width="546" height="371" />**3.2.10.8 Halaman Edit Data Pegawai**

*Gambar 3.27 perancangan antar muka Edit Data Pegawai*

Algoritma:

Begin if

Pilih menu : update

Then data behasil di update

End If

End

<img src="./media/image28.jpeg" width="545" height="371" />**3.2.10.9 Halaman View Data Pegawai**

*Gambar 3.28 perancangan antar muka view data pegawai*

Keterangan :

Pada form ini hanya menampilkan data saja**
**

<img src="./media/image29.jpeg" width="528" height="359" />**3.2.10.10 Halaman penilaian kinerja pegawai**

*Gambar 3.29 perancangan antar muka penilaian kinerja pegawai*

Algoritma :

Begin if

Pilih menu : penilaian kinerja pegawai

Then menampilkan Menu form dan data penilaian kinerja pegawai

End If

End

*
*

<img src="./media/image30.jpeg" width="528" height="359" />**3.2.10.11 Halaman input penilaian data pegawai**

*Gambar 3.30 perancangan antar muka input penilaian data pegawai*

Algoritma :

Begin if

Pilih menu : create

Then data berhasil di tambah

End If

End

**
**

<img src="./media/image31.jpeg" width="546" height="371" />**3.2.10.12 Halaman Pegawai**

*Gambar 3.31 perancangan antar muka pegawai*

Algoritma :

Begin if

Pilih menu : profile

Then menampilkan Menu profile yang melakukan login

Else if

Pilih menu : input data

Then menampilkan menu penginputan data pegawai

Else

Pilih menu : syarat view data

Then menampilkan menu data yang sudah diinputkan

End If

End

**
**

<img src="./media/image32.jpeg" width="546" height="371" />**3.2.10.13 Halaman Input Data Pegawai**

*Gambar 3.32 perancangan antar muka input data pegawai *

Algoritma :

Begin if

Pilih menu : create

Then data berhasil di tambah

End If

End

**
**

<img src="./media/image33.jpeg" width="546" height="370" />**3.2.10.14 Halaman view data pegawai**

*Gambar 3.33 perancangan antar muka view data pegawai*

Algoritma :

Begin if

Pilih menu : back

Then kembali ke halaman sebelumnya

Else if

End If

End

**
**

**3.2.10.15 Halaman profile pegawai yang login**

<img src="./media/image34.jpeg" width="546" height="371" />

*Gambar 3.34 perancangan antar muka profile yang login*

Keterangan :

Pada form ini hanya menampilkan profile dari data yang melakukan proses login.
