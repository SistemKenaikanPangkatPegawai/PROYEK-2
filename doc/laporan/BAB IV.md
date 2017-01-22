<span id="_Toc408562678" class="anchor"><span id="_Toc410626293" class="anchor"></span></span>**BAB IV**
========================================================================================================

<span id="_Toc408562679" class="anchor"><span id="_Toc410626294" class="anchor"></span></span>**IMPLEMENTASI DAN PENGUJIAN**
============================================================================================================================

<span id="_Toc408562680" class="anchor"><span id="_Toc410626295" class="anchor"></span></span>**Lingkungan Implementasi**
-------------------------------------------------------------------------------------------------------------------------

Lingkungan implementasi dari suatu program aplikasi adalah perangkat keras dan perangkat lunak serta program aplikasi lainnya yang mendukung terhadap implementasi program aplikasi tersebut. Agar perancangan program aplikasi dapat berjalan dengan baik maka dibutuhkan perangkat keras pendukung dan perangkat lunak yang sesuai yaitu:

### <span id="_Toc408562681" class="anchor"><span id="_Toc410626296" class="anchor"></span></span>**4.1.1 Perangkat Keras Pendukung**

1.  Processor Intel Core i3 atau yang setara

2.  Memori 4 GB

3.  Monitor dengan resolusi 1024 x 768

4.  Keybord dan Mouse

5.  Harddisk 80 GB

### <span id="_Toc408562682" class="anchor"><span id="_Toc410626297" class="anchor"></span></span>**4.1.2 Perangkat Lunak Pendukung**

1.  Windows 7 atau yang setara

2.  MYSQL

3.  Framework Laravel

4.  Microsoft Visio 2007

5.  Star UML

<span id="_Toc408562683" class="anchor"><span id="_Toc410626298" class="anchor"></span></span>**
**
------------------------------------------------------------------------------------------------

**Pembahasan Hasil Implementasi**
---------------------------------

Berdasarkan perancangnan antar muka yang telah dibuat, di hasilkan implementasi antar muka sebagai berikut :

1.  **Menu Utama**

<img src="./media/image1.jpeg" width="601" height="321" />Gambar 4.1 Tampilan Menu Utama

Keterangan :

Menu ini adalah Menu utama. Didalam menu ini ada dua actor yaitu Admin dan Pegawai.

1.  **Menu Login**

<img src="./media/image2.jpeg" width="601" height="320" />Gambar 4.2 Tampilan Menu Login

Keteragan :

Menu Login ini adalah memberikan hak akses pada admin dan user saat melakukan login

1.  **Menu Register**

<img src="./media/image3.jpeg" width="601" height="321" />Gambar 4.3 Tampilan Menu Register

Keterangan :

Menu Register ini adalah apabila admin atau pegawai yang belum mempunyai akun saat melakukan login aktor bisa registrasi terlebih dahulu.

1.  **Menu Home Admin**

<img src="./media/image4.jpeg" width="547" height="293" />

Gambar 4.4 Tampilan Menu Home Admin

Keterangan :

Menu Home Admin ini adalah menu pada saat admin melakukan login, dan menu ini hanya bisa masuk dengan akun si admin.

1.  **Menu Data Pegawai**

<img src="./media/image5.jpeg" width="547" height="292" />

Gambar 4.5 Tampilan Menu Data Pegawai

Keterangan :

Menu data pegawai ini adalah menu yang hanya bisa melihat biodata pegawai yang sebelumya melakukan proses penginputan data pegawai itu sendiri.

1.  **Menu Create Data Pegawai**

<img src="./media/image6.jpeg" width="547" height="292" />

Gambar 4.6 Tampilan Menu Create Data Pegawai

Keterangan :

Menu ini adalah menu menambahkan data pegawai yang dilakukan oleh pegawai saat melakukan login diberi hak akses sebagai pegawai bukan admin.

1.  **Menu Edit Data Pegawai**

<img src="./media/image7.jpeg" width="547" height="428" />

Gambar 4.7 Tampilan Menu Data Edit Data Pegawai

Keterangan :

Menu Edit Data Pegawai ini sama seperti sebelumnya, menu ini mengedit data pegawai yang sebelumnya sudah di inputkan terlebih dahulu.

1.  **Menu View Data Pegawai**

<img src="./media/image8.jpeg" width="526" height="312" />

Gamabar 4.8 Tampilan Menu View Data Pegawai

Keterangan :

Menu ini adalah Menampilkan data yang telah di inputkan ataupun telah di edit, di menu ini tidak langsung muncul di menu data pegawai melainkan saat menekan button view di menu data pegawai.

1.  **Menu Penilaian Kinerja Pegawai**

<img src="./media/image9.jpeg" width="547" height="291" />

Gambar 4.9 Tampilan Menu Penilaian Kinerja Pegawai

Keterangan :

Menu ini adalah menu yang menginputkan nilai nilai data pegawai yang meliputi persyaratan persyaratan yang telah di sepakati bersama.

1.  **Menu Syarat Kenaikan Pangkat**

<img src="./media/image10.jpeg" width="601" height="321" />

Gamabr 4.10 Tampilan Menu Syarat Kenaikan Pangkat

Keterangan :

Menu ini adalah menu yang menampilkan persyaratan persyaratan tidak ada yang spesial dari menu ini karna hanya view saja, terdapat 6 persyaratan salah satu contohnya seperti di bawah ini :

<img src="./media/image11.jpeg" width="547" height="291" />

<span id="_Toc408562704" class="anchor"><span id="_Toc410626308" class="anchor"></span></span>**4.3 Pengujian dan Hasil Pengujian**
-----------------------------------------------------------------------------------------------------------------------------------

> Pengujian dilakukan untuk mengetahui layak atau tidaknya suatu aplikasi yang akan di berikan kepada *client.* Pengujian ini merupakan pengujian *blackbox,* dan digunakan juga untuk mengetahui fungsi – fungsi pada aplikasi telah berjalan dengan baik.

### <span id="_Toc408562705" class="anchor"><span id="_Toc410626309" class="anchor"></span></span>**4.3.1 Identifikasi Pengujian**

##### Tabel 4.1 Identifikasi Pengujian

| **Kelas Uji**    | **Butir Uji**                  | **Tingkat Pengujian** | **Nomor Identifikasi** | **Jenis**     
                                                                                                                     
                                                                                                      **Pengujian**  |
|------------------|--------------------------------|-----------------------|------------------------|---------------|
| Validasi *login* | Validasi *login*               | Pengujian sistem      | UC-01                  | *Blackbox*    |
| Memasukan        
                   
 Data              | Data Pegawai                   | Pengujian sistem      | UC-02                  | *Blackbox*    |
|                  | Data penilaian Kinerja Pegawai | Pengujian sistem      | UC-03                  | *Blackbox*    |
|                  | Data Kenaikan Pangkat Pegawai  | Pengujian sistem      | UC-04                  | *Blackbox*    |

### <span id="_Toc408562707" class="anchor"><span id="_Toc410626310" class="anchor"></span></span>

### **4.3.2 Deskripsi dan Hasil uji**

#### 4.3.2.1 Validasi Login

> Bagian yang menjelaskan tentang pengujian *fitur – fitur* yang ada di dalam sistem aplikasi yang dibangun oleh penulis.

##### Tabel 4.2 Validasi Login

| **No Identifikasi** | **Deskripsi**                                  | **Prosedur Pengujian**                                   | **Keluaran yang diharapkan**                      | **Kriteria Evaluasi Hasil**                             | **Hasil Yang didapat**        | **Kesimpulan** |
|---------------------|------------------------------------------------|----------------------------------------------------------|---------------------------------------------------|---------------------------------------------------------|-------------------------------|----------------|
| UC-01               | Menguji validasi *login* untuk masuk ke sistem | Ketikkan *username* dan *password* kemudian klik *login* | Tampil *Form* Utama yang telah memiliki hak akses | Ketika tombol *login* diklik, tampil halaman menu utama | Sesuai dengan yang diharapkan | OK             |

#### 4.3.2.2 Memasukan Data

##### Tabel 4.3 Memasukan Data

| **No Identifikasi** | **Deskripsi**                             | **Prosedur Pengujian**                                                              | **Keluaran yang diharapkan**        | **Kriteria Evaluasi Hasil**                                                                                                                                                             | **Hasil Yang didapat**        | **Kesimpulan** |
|---------------------|-------------------------------------------|-------------------------------------------------------------------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|----------------|
| UC-02               | Menguji penginputan data pegawai          | Admin dapat memasukan, menghapus, dan memperbarui data Pegawai yang telah terdaftar | Data muncul dalan *DataGridView, *  | Admin dapat memasukan data dengan menekan tombol simpan. Untuk menghapus dapat menggunakan tombol hapus dan jika ingin memperbarui data admin dapat menekan isi di dalam DataGrid View. | Sesuai dengan yang diharapkan | OK             |
| UC-03               | Menguji penginputan Data Kinerja Pegawai  | Admin dapat memasukan, data kinerja pegawai                                         | Data akan disimpan didalam database | Admin dapat memasukan data kinerja pegawai dengan menekan tombol simpan dan admin dapat melihat hasilnya                                                                                | Sesuai dengan yang diharapkan | OK             |
| UC-04               | Menguji penginputan Data Kenaikan Pangkat | Admin dapat melihat hasil kinerja pegawai                                           | Data muncul dalam *DataGridView*    | Admin dapat melihat hasil kinerja pegawai dengan menekan tombol hasil.                                                                                                                  | Sesuai dengan yang diharapkan | OK             |
