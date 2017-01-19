<span id="_Toc408562280" class="anchor"><span id="_Toc410625516" class="anchor"></span></span>BAB III
=====================================================================================================

<span id="_Toc408562281" class="anchor"><span id="_Toc410625517" class="anchor"></span></span>ANALISIS DAN PERANCANGAN
======================================================================================================================

<span id="_Toc408562282" class="anchor"><span id="_Toc410625518" class="anchor"></span></span>3.1 Analisis
----------------------------------------------------------------------------------------------------------

Analisis merupakan suatu tahap pembahasan terhadap suatu sistem yang akan dibuat. Tahap ini bertujuan untuk mengetahui sistem, proses yang terlibat dalam aplikasi serta hubungan antar proses. Analisis juga dapat didefinisikan sebagai penguraian dari suatu sistem di dalam bagian-bagian komponennya dengan maksud untuk mengidentifikasikan dan mengevaluasi masalah-masalah, hambatan-hambatan yang terjadi serta kebutuhan yang diharapkan sehingga dapat diusulkan perbaikan.

### Analisis sistem yang berjalan 

Sistem yang berjalan saat ini terdiri dari tiga prosedur yaitu penilaian kinerja pegawai dan kenaikan pangkat pegawai.

### 3.1.1.1. Analisis Prosedur (*Flowmap*)

1.  **Analisis Sistem Yang Berjalan Pada Penilaian Kinerja Pegawai**

Pada penilaian kinerja pegawai, HRD(admin) melihat data penilaian kinerja pegawai selama satu bulan periode. Kemudian HRD(admin) membuat hasil kinerja pegawai tersebut, kemudian pegawai akan melihat dan mendapatkan hasil kinerjanya.

![](./media/image1.emf)

*Gambar 3.1 prosedur penilaian kinerja pegawai sistem yang berjalan*

1.  **Analisis Sistem Yang Berjalan Pada Kenaikan Pangkat Pegawai**

Pada kenaikan pangkat pegawai, HRD(admin) melihat hasil kinerja pegawai selama satu bulan, didalam kinerja penilaian pegawai terdapat beberapa kriteria sebagai bahan pertimbangan, kemudian HRD(admin) memasukkan kriteria poin tersebut, setelah data sesuai HRD(admin) akan melihat hasil nilai dari pegawai apakah akan dinaikkan pangkat atau tidak dan pegawai akan melihat hasilnya.

*Gambar 3.2 prosedur kenaikan pangkat sistem yang berjalan*

1.  **3.1.1.2. Analisis Dokumen yang Digunakan**

Dokumen yang digunakan untuk membangun aplikasi ini sangat sederhana. Dokumen ini sangat berguna sekali karena dapat sebagai dasar pembuatan aplikasi. Dokumen yang dibutuhkan saat pembangunan aplikasi sebagai berikut :

1.  Dokumen Data Pegawai

2.  Dokumen Kriteria Penilaian pegawai

3.  Dokumen Nilai Pegawai

    1.  ### Analisis Sistem yang akan Dibangun

Analisis kebutuhan yang dimaksud disini berupa analisis *flowmap* mengenai sistem yang akan dibangun meliputi prosedur *login pada admin dan pegawai*, Prosedur data pegawai, Prosedur penilaian kinerja pegawai, Prosedur rekomendasi data pegawai, lihat data pegawai.

1.  **Analisis sistem yang akan dibangun pada prosedur login**

Pada prosedur login admin melibatkan 2 entitas (aktor) yaitu Admin ( Divisi HRD), dan pegawai pada PO Kramat Djati. Dimana setiap entitas (aktor) tersebut memiliki hak akses yang berbeda terhadap sistem atau aplikasi yang dibuat.

*Gambar 3.3 prosedur login yang akan dibangun*

1.  **Analisis sistem yang akan dibangun pada prosedur input data pegawai**

Pegawai akan menuju ke halaman utama apabila telah melakukan login, lalu pilih menu input data pegawai, kemudian pegawai menginputkan data pegawai. Setelah berhasil admin bisa melihat data pegawai yang telah diinputkan.

*Gambar 3.4 prosedur input data pegawai yang akan dibangun*

1.  **Analisis sistem yang akan dibangun pada prosedur penilaian kinerja pegawai**

admin akan masuk menu utama, masuk ke halaman pegawai dan memilih penilaian kinerja pegawai, setelah itu admin memilih kriteria penilaian yang diinginkan, kemudian admin menginputkan penilaian kinerja pegawai sesuai dengan persyaratan yang telah ada dan aplikasi akan menyimpan data kinerja pegawai tersebut.<span id="_Toc408562302" class="anchor"><span id="_Toc410625523" class="anchor"></span></span>

*Gambar 3.5 prosedur input penilaian kinerja pegawai*

1.  **Kebutuhan Fungsional (*Functional Requirements*)**

Analisis kebutuhan fungsional merupakan suatu kebutuhan yang berhubungan dengan kebutuhan sistem yang akan dibuat. Dimana menjabarkan mengenai fungsi-fungsi yang dapat mendukung jalannya sistem, adapun kebutuhan fungsional yang akan dibuat yaitu pengelolaan data sebagai berikut

1.  Data pegawai : Menu ini dapat digunakan untuk mendata pegawai yang ada di PO Kramat Djati. Admin dapat menambah atau mengahapus data tersebut dan pegawai juga bisa menginputkan data sendiri atau mengupdate data.

2.  Data kinerja pegawai : Menu ini dapat menampilkan nilai dari kinerja pegawai. Admin dapat memasukan nilai dari pegawai PO Kramat Djati

3.  Data kenaikan pangkat pegawai : Menu ini dapat menampilkan nilai pegawai yang nantinya masuk ke data rekomenasi

4.  Data rekomendasi : Menu ini menampilkan kelayakan pegawai untuk naik pangkat atau tidak

**3.1.2.2 Kebutuhan Non-Fungsional (*Non- Functional Requirement*)**

Analisis kebutuhan non fungsional dilakukan untuk mengetahui spesifikasi kebutuhan untuk sistem. Spesifikasi kebutuhan melibatkan analisis perangkat keras/*hardware*, analisis perangkat lunak/*software*, analisis pengguna/*User*. Adapun kebutuhan fungsional yang akan dibuat adalah sebagai berikut

1.  Perangkat Lunak (*software*) meliputi :

<!-- -->

1.  Perangkat Lunak menggunakan *Framework Laravel 5.3*

2.  Sistem operasi menggunakan *Microsoft Windows 7 Ultimate* 32-bit

3.  *Database* menggunakan *Mysql*

4.  Flowmap dan diagram dapat digambarkan pada *Star UML* atau *Microsoft Visio 2007.*

5.  Disain Antar Muka menggunakan *Photoshop Cs 3*

<!-- -->

1.  Perangkat Keras (*hardware*) meliputi :

<!-- -->

1.  Intel Core i3

2.  Memory 4 GB RAM

    1.  **Perancangan**

        Perancangan merupakan analisis untuk menggambarkan kebutuhan-kebutuhan dalam suatu aplikasi yang akan dibangun. Perancangan ini fokus terhadap perancangan data yang ada pada aplikasi, tahap perancangan data pada perangkat lunak tersebut dipakai ke dalam pemodelan yang umum yang digunakan yaitu menggunakan : *Use Case Diagram, Class Diagram, Sequence Diagram, Collaboration Diagram, Activity Diagram, Statechart Diagram, Componen Diagram,* dan *Deployment Diagram.*

        1.  **Use Case Diagram**

<img src="./media/image6.jpeg" width="598" height="486" />

*Gambar 3.6 use case diagram*

### Definisi Aktor

Definisi aktor merupakan penjelasan dari apa yang dilakukan oleh aktor-aktor yang terlibat dalam perangkat lunak yang dirancang. Adapun deskripsi dari aktor-aktor yang terlibat dalam aplikasi kinerja pegawai PO Kramat Djati adalah sebagai berikut :

| <span id="_Toc408562303" class="anchor"></span>**No** | **Aktor** | **Deskripsi**                                       |
|-------------------------------------------------------|-----------|-----------------------------------------------------|
| 1.                                                    | Admin     | -   Mengelola system                                
                                                                                                                          
                                                                     -   Mengelola data pegawai                           
                                                                                                                          
                                                                     -   Mengelola data penilaian kinerja pegawai         
                                                                                                                          
                                                                     -   Mengelola rekomendasi keputusan kinerja pegawai  |
| 2.                                                    | Pegawai   | -   Menginputkan data pegawai                       
                                                                                                                          
                                                                     -   Melihat kinerja                                  |

##### Tabel 3.1 Definisi Aktor

### Definisi Use Case

> *Use case* yang ada dalam diagram didefinisikan pada tabel di bawah ini :

##### Tabel 3.2 Definisi Use Case

| No  | No.definisi | Use Case                      | Keterangan                                                                                                                             |
|-----|-------------|-------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| 1.  | UC-01       | *Login*                       | Merupakan proses pemberian hak akses kepada *user* dan *Validasi* untuk semua *user* yang akan mengakses bagian tertentu dalam sistem. |
| 2.  | UC-02       | Kelola Data Pegawai           | Merupakan aktivitas yang dilakukan untuk mengelola data pegawai yang ada di PO Kramat Djati. Data tersebut akan disimpan di database.  |
| 3.  | UC-03       | Kelola Data Kinerja Pegawai   | Merupakan serangkaian aktivitas yang dilakukan untuk mengelola data kinerja pegawai,                                                   |
| 4.  | UC-04       | Kelola data admin             | Merupakan aktivitas yang dilakukan untuk menhelola data admin                                                                          |

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

1.  **Skenario Use Case Kelola Data Pegawai**

Skenario dalam diagram *use case* kelola data pegawai ada pada tabel dibawah ini

##### Tabel 3.4 Skenario Use case Kelola Data Pegawai

| **Identifikasi**                                                               |
|--------------------------------------------------------------------------------|
| Nomor                                                                          |
| Nama                                                                           |
| Tujuan                                                                         |
| Deskripsi                                                                      |
| Aktor                                                                          |
| **Skenario**                                                                   |
| Kondisi Awal                                                                   |
| **Aksi Aktor**                                                                 |
| Pegawai memilih menu Data Pegawai                                              |
| pegawai memilih tool simpan, ubah, dan hapus untuk menyimpani data, ubah data. |
| Pegawai melihat data pegawai                                                   |
| Kondisi Akhir                                                                  |

1.  **Skenario Use Case Kelola data Kinerja Pegawai**

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

**3.2.2 Class Diagram**

<img src="./media/image7.jpeg" width="493" height="379" />

*Gambar 3.7 Class Diagram*

Class diagram ini menggambarkan tentang hubungan dalam sistem yang akan dibangun. Dalam sistem yang akan dibangun Admin, Pegawai, login merupakan bagian dari sistem atau dengan kata lain jika tidak ada tiga pendukung tersebut maka sistem tidak akan berjalan. Sedangkan sistem terdapat menu kategori yang berisi , data pegawai dan data kinerja pegawai.

<span id="_Toc408562325" class="anchor"><span id="_Toc410625535" class="anchor"></span></span>

### 3.2.3 Sequence Diagram

#### 3.2.3.1 Sequence Diagram Login

<img src="./media/image8.jpeg" width="511" height="458" /> Berikut ini merupakan *sequence diagram* Login menjelaskan hubungan antara admin, pegawai login dan menu utama

*Gambar 3.8 Squence Diagram Login*

Keterangan :

1.  Admin/pegawai mengakses laman login

2.  Admin/pegawai memasukan username dan password

3.  Terhubung ke database untuk dicek sesuai atau tidak

4.  Jika username atau password yang diisikan di *form login* tidak sesuai maka pegawai tidak akan masuk kedalam system dan tetap di menu login

5.  Konfirmasi untuk membuka menu utama di Aplikasi

6.  Memilih toobar di menu utama

    1.  **Sequence Diagram Kelola Data Kinerja Pegawai**

        Berikut ini merupakan *sequence diagram* kelola data kinerja pegawai menjelaskan hubungan antara admin, menu utama dan menu data pegawai

<img src="./media/image9.jpeg" width="522" height="409" />

*Gambar 3.9 Squence Diagram kinerja Pegawai*

Keterangan :

1.  Admin mengakses halaman utama Aplikasi

2.  Admin mengakses menu data kinerja pegawai

3.  Admin memilih kinerja pengalaman dan memasukan data

4.  Admin memilih kinerja loyalitas dan memasukan data

5.  Admin memilih kinerja inisiatif dan kreatif dan memasukan data

6.  Admin kembali ke menu utama

    1.  **Sequence Diagram Kelola Data Pegawai**

        Berikut ini merupakan *sequence diagram* kelola data pegawai menjelaskan hubungan antara admin, menu utama dan menu data pegawai

        <img src="./media/image10.jpeg" width="493" height="406" />

*Gambar 3.10 Squence Diagram Kelola Data Pegawai*

Keterangan :

1.  Pegawai mengakses halaman utama Aplikasi

2.  Pegawai mengakses menu Data Pegawai dan memasukkan data

3.  Database akan melakukan query insert

4.  Database menyimpan data

5.  Pegawai mengakses halaman data pegawai dan memilih update data

6.  Pegawai mengubah data

7.  Database melakukan query update

8.  Database meyimpan data

    1.  **Collaboration Diagram**

        1.  **Collaboration Diagram Login **

            Berikut ini merupakan *Collaboration diagram* login yang menjelaskan proses login

<img src="./media/image11.jpeg" width="451" height="266" />

*Gambar 3.11 Collaboration Diagram Login*

**3.2.4.2 Collaborarion Diagram Kelola Kinerja Pegawai**

Berikut ini merupakan *Collaboration diagram* kelola kinerja pegawai yang menjelaskan proses admin mengelola kinerja pegawai

<img src="./media/image12.jpeg" width="459" height="236" />

*Gambar 3.11 Collaboration Diagram Login*

**3.2.4.2 Collaborarion Diagram kelola data pegawai**

Berikut ini merupakan *Collaboration diagram* kelola data pegawai yang menjelaskan proses mengelola data pegawai

<img src="./media/image13.jpeg" width="454" height="264" />

*Gambar 3.12 Collaboration Diagram kelola data pegawai*

Keterangan :

1.  Pegawai telah login dan masuk ke menu utama

2.  Pegawai memilih data pegawai

3.  Pegawai memasukkan data pegawai

4.  Database akan memvalidasi data pegawai

5.  Pegawai kembali menu data pegawai

6.  Logout

7.  Konfirmasi logout

<!-- -->

1.  **Activity Diagram **

    **3.2.5.1 Activity Diagram Login**

<img src="./media/image14.jpeg" width="506" height="410" />

*Gambar 3.13 Activiy Diagram Login*

Keterangan :

1.  Admin/Pegawai mengakses halaman utama dan login;

2.  Admin/Pegawai memasukan username dan password;

3.  Database mengkonfirmasi data;

4.  Jika valid maka akan muncul Tampilan Utama;

5.  Jika tidak akan kembali ke form login;

    **3.2.5.2 Activity Diagram Penilaian Kinerja Pegawai**

    <img src="./media/image15.jpeg" width="439" height="381" />

*Gambar 3.13 Activiy Diagram Login*

Keterangan :

1.  Admin mengakses ke data pegawai;

2.  Admin memilih menu data kinerja pegawai;

3.  Admin memasukan kinerja pegawai

4.  Admin melihat hasil dari kinerja pegawai

    **3.2.5.3 Activity Diagram Kelola Data Pegawai**

    <img src="./media/image16.jpeg" width="434" height="408" />

*Gambar 3.14 Activity diagram kelola data pegawai*

Keterangan :

1.  Pegawai melakukan login;

2.  Pegawai mengakses ke halaman utama;

3.  Pegawai memilih menu data pegawai;

4.  Pegawai melakukan tambah data, ubah data, hapus data

5.  Database mengkonfirmasi data;

6.  Jika valid maka data akan tersimpan

    1.  **Statechart Diagram**

        1.  **Statechart Diagram Login**

<img src="./media/image17.jpeg" width="546" height="245" />

*Gambar 3.15 Statechart Diagram Login*

1.  **Statechart Diagram Kinerja Pegawai**

<img src="./media/image18.jpeg" width="545" height="201" />

*Gambar 3.16 Statechart Diagram kinerja pegawai*

1.  **Statechart Diagram Data Pegawai**

    <embed src="./media/image19.emf" width="465" height="327" />

*Gambar 3.17 Statechart Diagram Data pegawai*

1.  **Component Diagram**

    <img src="./media/image20.jpeg" width="435" height="428" />

*Gambar 3.18 Component diagram *

1.  **Deployment Diagram**

<img src="./media/image21.jpeg" width="598" height="339" />

*Gambar 3.19 Deployment diagram*

> **3.2.9 Struktur Menu**

<img src="./media/image22.jpeg" width="408" height="282" />

*Gambar 3.20 Struktur menu*

**3.2.10 Perancangan Antarmka**

<img src="./media/image23.jpeg" width="546" height="371" /> **3.2.10.1 Halaman Utama**

*Gambar 3.21 perancangan antar muka Halaman Utama*

**
**

<img src="./media/image24.jpeg" width="546" height="371" />**3.2.10.2 Halaman Login**

*Gambar 3.22 perancangan antar muka Login*

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

> <img src="./media/image25.jpeg" width="546" height="371" />**3.2.10.3 Halaman register**

*Gambar 3.23 perancangan antar muka register*

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

<img src="./media/image26.jpeg" width="546" height="371" />**3.2.10.4 Halaman admin**

*Gambar 3.24 perancangan antar muka halaman admin*

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

<img src="./media/image27.jpeg" width="546" height="371" />**3.2.10.5 Halaman profile yang melakukan login**

*Gambar 3.25 perancangan antar muka profile yang melakukan login*

Algoritma :

Begin if

Pilih menu : back

Then kembali ke menu sebelumnya

End if

<img src="./media/image28.jpeg" width="546" height="371" />**3.2.10.6 Halaman Data Pegawai**

*Gambar 3.26 perancangan antar muka Data Pegawai*

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

<img src="./media/image29.jpeg" width="546" height="371" />**3.2.10.7 Halaman Menambahkan data pegawai**

*Gambar 3.26 perancangan antar muka meambahkan data pegawai*

Algoritma :

Begin if

Pilih menu : create

Then menambahkan data berhasil

End If

End

<img src="./media/image30.jpeg" width="546" height="371" />**3.2.10.8 Halaman Edit Data Pegawai**

*Gambar 3.27 perancangan antar muka Edit Data Pegawai*

Algoritma:

Begin if

Pilih menu : update

Then data behasil di update

End If

End

<img src="./media/image31.jpeg" width="545" height="371" />**3.2.10.9 Halaman View Data Pegawai**

*Gambar 3.28 perancangan antar muka view data pegawai*

Keterangan :

Pada form ini hanya menampilkan data saja**
**

<img src="./media/image32.jpeg" width="528" height="359" />**3.2.10.10 Halaman penilaian kinerja pegawai**

*Gambar 3.29 perancangan antar muka penilaian kinerja pegawai*

Algoritma :

Begin if

Pilih menu : penilaian kinerja pegawai

Then menampilkan Menu form dan data penilaian kinerja pegawai

End If

End

*
*

<img src="./media/image33.jpeg" width="528" height="359" />**3.2.10.11 Halaman input penilaian data pegawai**

*Gambar 3.30 perancangan antar muka input penilaian data pegawai*

Algoritma :

Begin if

Pilih menu : create

Then data berhasil di tambah

End If

End

**
**

<img src="./media/image34.jpeg" width="546" height="371" />**3.2.10.12 Halaman Pegawai**

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

<img src="./media/image35.jpeg" width="546" height="371" />**3.2.10.13 Halaman Input Data Pegawai**

*Gambar 3.32 perancangan antar muka input data pegawai *

Algoritma :

Begin if

Pilih menu : create

Then data berhasil di tambah

End If

End

**
**

<img src="./media/image36.jpeg" width="546" height="370" />**3.2.10.14 Halaman view data pegawai**

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

<img src="./media/image37.jpeg" width="546" height="371" />

*Gambar 3.34 perancangan antar muka profile yang login*

Keterangan :

Pada form ini hanya menampilkan profile dari data yang melakukan proses login.
