## Rangkuman Minggu Ke 3 Back-End
## Day -10
## Sequelize
### 1. Pengertian Sequelize
Sequelize adalah ORM (Object Relational Mapping) Node JS yang berbasis promise. Sequelize mendukung sebagian besar relational Database seperti MySQL, PostgresQL, 
MariaDB, SQLite dan Miscrosoft SQL Server. Dengan fitur fitur di Sequelize, kita bisa mengelola dan mengatur data di database kita dengan cepat, dan efisien.

### 2. Instalasi Sequelize
- install sequelize & driver sql

![ins-sequelize](https://user-images.githubusercontent.com/114325558/200263258-7f83cf6d-ffcd-434d-83fb-2edd0b1f4f5d.JPG)

- install sequelize cli

![sequelize-cli](https://user-images.githubusercontent.com/114325558/200261478-e586186d-1a04-4fc4-9dad-a83b9ba4b069.JPG)

### 3. Generate Sequelize
- Sequelize init

![sequelize-init](https://user-images.githubusercontent.com/114325558/200261983-b29b8132-b288-40e0-a54c-820fea6ea15c.JPG)

- Setting database

![setting-db](https://user-images.githubusercontent.com/114325558/200262384-936476cb-dbcf-4ca3-8154-f4ee08f513b5.JPG)

- Generate model

![generate-model](https://user-images.githubusercontent.com/114325558/200262752-67a4e37a-c554-4635-b74f-af917f7e6550.JPG)

- Generate seed

![generate-seed](https://user-images.githubusercontent.com/114325558/200263043-fefcbde7-b11c-430d-97a9-1e203d5c8ab7.JPG)

### 4. Membuat Crud Dengan Sequelize dan Express
- Get all todo

![get-all-todo](https://user-images.githubusercontent.com/114325558/200263548-d2cc7592-0956-43e8-9642-d6879d793a71.JPG)

- Get to do detail by-id

![get-todo-detail-byId](https://user-images.githubusercontent.com/114325558/200263845-cc07dcfd-928e-46e0-8e1c-bd457f8185e8.JPG)

- Create new todo

![create-new-todo](https://user-images.githubusercontent.com/114325558/200264391-ef21215b-13b7-4c9e-a59b-7d4d19d06314.JPG)

- Update todo by id

![update-todo-by-id](https://user-images.githubusercontent.com/114325558/200264587-f9b2e24e-aeea-4f11-a1d0-1f5bee09bb14.JPG)

&nbsp;

## Day -11
## MongoDB
### 1. pengenalan MongoDB
MongoDB adalah salah satu jenis database NoSQL yang cukup populer digunakan dalam pengembangan website. NoSQL sendiri adalah singkatan dari Not Only SQL. Artinya kita bisa mengolah database dengan fleksibel dan tidak membutuhkan Query. Berbeda dengan database jenis SQL yang menyimpan data menggunakan relasi tabel, MongoDB menggunakan dokumen dengan format JSON. 

![ilustrasi mongodb](https://user-images.githubusercontent.com/114325558/201625530-017d3a54-1dfb-452b-82ba-f3f6a1284a58.JPG)

Sistem database ini menggunakan beberapa komponen penting, yaitu: 
- Database – merupakan wadah dengan struktur penyimpanan yang disebut collection. 
- Collection – merupakan tempat kumpulan informasi data yang berbentuk dokumen. Collection dipadankan seperti tabel-tabel yang berisi data pada database SQL.  
- Document – merupakan satuan unit terkecil dalam MongoDB.

Keunggulan menggunakan MongoDB  yaitu :
- Performa lebih cepat.
- Sistem tidak membutuhkan tabel.
- Pengelolaan database lebih mudah.
- Mampu menampung banyak data yang bervariasi.
- Bisa mengelola query lebih baik.
- Memiliki kemampuan skalabilitas sesuai kebutuhan.
- Dapat memperbarui skema data tanpa downtime.

Sedangkan kekurangan menggunakan MongoDB yaitu :
- Tidak mendukung transaksi.
- Masalah konsistensi data.
- Menggunakan banyak memory.
- Hanya bisa menampung maksimal 16MB disetiap document.

### 2. Instalasi MongoDB
- Perintah instalasi 

![instalasi mongodb](https://user-images.githubusercontent.com/114325558/201628813-cb40501f-ddcb-4e2a-a4ea-3aeee721bf58.JPG)

- Mengaktifkan MongoDB

![use mongodb](https://user-images.githubusercontent.com/114325558/201629052-091ac0c3-ae4f-43a1-86d5-3e102ebd191b.JPG)

setelah aktif jalankan perintah berikut :

![start mongodb](https://user-images.githubusercontent.com/114325558/201629319-ddb8b9c5-f28d-4916-91a4-8e9087874cd1.JPG)

- Cek status

![cek status mongodb](https://user-images.githubusercontent.com/114325558/201629586-3e2d36cb-66cf-4fac-8a0b-481c0562ee3b.JPG)

Jika hasil tampilannya seperti berikut, berarti database MongoDB sudah aktif dan berjalan.

![tampilan status mongodb](https://user-images.githubusercontent.com/114325558/201630024-14c2a49f-bc7f-439e-a5ce-3f55a5408750.JPG)

### 3. Perintah Dasar Pada MongoDB
- Masuk ke database MongoDB

![masuk ke mongodb](https://user-images.githubusercontent.com/114325558/201631332-388e8343-be24-46b1-80fe-6c41789df517.JPG)

- Membuat database

![buat db mongo](https://user-images.githubusercontent.com/114325558/201631780-c7419895-a0c6-4e2a-aa13-d58c49efff8d.JPG)

- Melihat database

![lihat db](https://user-images.githubusercontent.com/114325558/201632065-6ad7cc49-bcd6-405e-9bc4-5e75771984fd.JPG)

- Menghapus database

![drop db](https://user-images.githubusercontent.com/114325558/201632244-789898fa-0967-42a9-8f13-4cb130ad3ee4.JPG)

- Insert data

![insert data](https://user-images.githubusercontent.com/114325558/201632471-98c4db23-fca8-4f86-9ada-ecdbe5b26689.JPG)

- Melihat daftar collection dalam database

![show collection](https://user-images.githubusercontent.com/114325558/201632929-8e565494-da2e-4739-8d08-e16b1c3e155e.JPG)

- Melihat isi collection

![melihat isi collection](https://user-images.githubusercontent.com/114325558/201633207-384de3f0-a2eb-4b6c-abf8-e9ef323a3d65.JPG)

- Melihat isi collection dalam bentuk JSON

![melihat collection json](https://user-images.githubusercontent.com/114325558/201633626-890b8e5c-5531-4f0d-9b75-2112d76b256a.JPG)

- Melihat isi collection hanya 1 result

![lht collection 1 result](https://user-images.githubusercontent.com/114325558/201641760-44eb6a78-77d0-42e5-afc8-ec2e81809541.JPG)

- Menghapus data

![hapus data](https://user-images.githubusercontent.com/114325558/201642010-d1bb3189-720a-4714-a8dc-1ed8dedd4f55.JPG)

- Mengubah data

![update data](https://user-images.githubusercontent.com/114325558/201642179-07a1f148-c39c-43e2-ace9-19eb4c4df0de.JPG)

- Menghapus Collection

![hapus collection](https://user-images.githubusercontent.com/114325558/201642349-c5fdab4d-5302-460a-8f75-f30dfb731c92.JPG)

&nbsp;

## Day -12
## Mongoose
### 1. Pengenalan Mongoose
Mongoose adalah sebuah Object Document Mapper (ODM). Ini berarti Mongoose mengizinkan kita untuk mendefinisikan obyek dengan skema yang benar-benar diketik yang dipetakan ke sebuah dokumen MongoDB.Mongoose adalah pustaka JavaScript yang memungkinkan Anda menentukan skema dengan data yang strongly-typed.  Setelah skema didefinisikan, Mongoose memungkinkan Anda membuat Model berdasarkan skema tertentu. Model Mongoose kemudian dipetakan ke Dokumen MongoDB melalui definisi skema Model.Setelah menentukan skema dan model, Mongoose berisi banyak fungsi berbeda yang memungkinkan kita untuk memvalidasi, menyimpan, menghapus, dan men-query data menggunakan fungsi MongoDB yang umum. Mongoose menyediakan jumlah fungsionalitas yang luar biasa yang berkaitan dengan pembuatan dan pengerjaan skema. Mongoose saat ini memiliki delapan tipe skema dimana propertinya disimpan seperti saat berada di MongoDB. Diantaranya:
- String
- Number
- Date
- Buffer
- Boolean
- Mixed
- ObjectId
- Array

Setiap tipe data memungkinkan kita untuk menentukan:
- Sebuah nilai default
- Sebuah fungsi validasi custom
- Menunjukan field yang dibutuhkan
- Fungsi get yang memungkinkan Anda untuk memanipulasi data sebelum dikembalikan sebagai obyek
- Sebuah set fungsi yang memungkinkan Anda untuk memanipulasi data sebelum disimpan ke database
- Membuat indeks yang memungkinkan data agar ditarik secara lebih cepat

### 2. Instalasi Mongoose
Untuk melakukan instalasi pada Mongoose menggunakan perintah :

![install mongose](https://user-images.githubusercontent.com/114325558/201644563-87d2e030-42b7-45a8-9aee-dac66293a6b4.JPG)

### 3. Membuat Connection

![create connection 1](https://user-images.githubusercontent.com/114325558/201644898-bd0d042f-7661-41c8-86a9-1f2ff7b8c544.JPG)

Membuat koneksi dengan menggunakan MongoDB database, yang diletakkan di .env :

![create connection 2](https://user-images.githubusercontent.com/114325558/201645160-8364e79d-ec4e-45d5-a227-38926aa30eea.JPG)

### 4. Membuat Schema
- Definisikan Skema, dan tipe data untuk setiap field yang akan digunakan.

![define schema 1](https://user-images.githubusercontent.com/114325558/201645858-536586de-ea51-4738-9fd1-1d35767e67cd.JPG)

- membuat validasi data, misal untuk field yang wajib diisi.

![define schema 2](https://user-images.githubusercontent.com/114325558/201646133-8e01e627-d36a-4a00-b121-c54c2383c804.JPG)

- Membuat model users dari schema yang telah kita buat untuk melakukan pengolahan data, atau operasi CRUD.

![define schema 3](https://user-images.githubusercontent.com/114325558/201646408-ee6a36c2-9c1f-4347-b93b-ca0eb9143654.JPG)

### 5. Membuat Simple Crud
- Sebelum membuat operasi CRUD,terlebih dahulu menginstall express untuk routing dan body-parser.

![simple crud1](https://user-images.githubusercontent.com/114325558/201647186-abd66f24-d6d2-4d74-bbfe-d6ab96a985ab.JPG)

- Kita bisa menggunakan fungsi find() untuk menampilkan keseluruhan data.

![simple crud 2](https://user-images.githubusercontent.com/114325558/201647533-6ecfb39c-a887-4d36-a1d2-98e06d4a3bfd.JPG)

- Kita bisa menggunakan method POST untuk mendaftarkan user, apabila data sudah ada maka akan menampilkan pesan error.

![simple crud 3](https://user-images.githubusercontent.com/114325558/201647902-d5c3ee83-59d2-4368-92f0-4d74a7791099.JPG)

- Mendapatkan data user berdasarkan id.

![simple crud 4](https://user-images.githubusercontent.com/114325558/201648336-a79df1cd-b992-4636-983f-46bc716c2df8.JPG)

- Menghapus satu data berdasarkan id.

![simple crud 5](https://user-images.githubusercontent.com/114325558/201648578-593c26a5-7a06-4782-bba4-6f55d281b508.JPG)

- Mengapdate data berdasarkan id.

![simple crud 6](https://user-images.githubusercontent.com/114325558/201648858-e9482868-6399-436b-80fc-4806252cee3f.JPG)

&nbsp; 

## Day -13
## Docker
### 1. Pengenalan Dokker
Docker adalah layanan yang menyediakan kemampuan untuk mengemas dan menjalankan sebuah aplikasi dalam sebuah lingkungan terisolasi yang disebut dengan container. Dengan adanya isolasi dan keamanan yang memadai memungkinkan kamu untuk menjalankan banyak container di waktu yang bersamaan pada host tertentu.
Docker ini diperkenalkan pada tahun 2013 oleh Solomon Hykes pada acara PyCon. Beberapa bulan setelahnya docker secara resmi diluncurkan, tepatnya pada tahun 2014. Semenjak itu docker menjadi sangat populer di kalangan developer luar negeri.
Fitur-fitur yang terdapat pada dokker yaitu :
- Docker engine
- Docker Hub
- Docker Compose
- Docker for Mac
- Docker for Linux
- Docker for Windows

### 2. Mengapa Menggunakan Dokker ?
Dalam pengembangan aplikasi, developer memerlukan virtualisasi di server agar aplikasi bisa berjalan di berbagai platform dengan konfigurasi hardware yang berbeda-beda. Sayangnya, ketika menggunakan virtualisasi harus menyiapkan satu sistem operasi secara penuh. Jika membutuhkan beberapa virtualisasi, server perlu resource yang besar. Nah, container bisa digunakan sebagai alternatif virtualisasi sehingga tidak perlu menyiapkan sistem operasi secara penuh. Dengan container, ukuran file menjadi lebih kecil dibandingkan virtualisasi yang biasa digunakan.
Kelebihan penggunaan dokker yaitu :
- Memiliki konfigurasi yang sederhana.
- Tingkat keamanan yang baik.
- Dapat dijalankan pada beberapa platform cloud.
- Dapat melakukan debugging.
- Dapat digunakan pada berbagai sistem operasi.

### 3. Konsep Container Pada Dokker
Dalam penggunaan Docker, Container adalah sebuah lingkungan khusus yang dibuat untuk instance Docker image. Menjalankan sebuah Image akan menghasilkan satu Docker container.
Image menyediakan template yang bisa digunakan dalam pembuatan container. Image mungkin berisi informasi yang dibutuhkan untuk membuat container, dan bisa disimpan di komputer atau secara remote.

### 4. Perintah Dasar Pada Dokker
- Dokker pull

![dokker pull](https://user-images.githubusercontent.com/114325558/201654681-2ceefda9-b2dc-4fa4-beee-095eedd6f30c.JPG)

- Docker images

![dokker images](https://user-images.githubusercontent.com/114325558/201655130-19fc0980-d7d8-4269-bb30-6e9395a751ec.JPG)

- Dokker run

![dokker run](https://user-images.githubusercontent.com/114325558/201654942-298d9447-97a4-4d55-b467-6c45b9132a34.JPG)

### 5. Dokker File
Dockerfile adalah file teks yang berisi semua perintah yang bisa dijalankan user pada baris perintah untuk membuat image. Ini mencakup semua instruksi yang diperlukan oleh docker untuk membangun image.
- Membuat dokker file

![dokker file 1](https://user-images.githubusercontent.com/114325558/201656089-789ad9c9-0fad-485e-8a87-6c0d37d16e48.JPG)

### 6. Dokker Compose 
Docker-Compose adalah alat untuk mendefinisikan dan menjalankan satu atau beberapa container yang saling terkait dengan sebuah command. Pada implementasinya kita dapat menggunakannya dengan membuat sebuah file berekstensi yaml/yml yang di dalamnya terdapat konfigurasi-konfigurasi terhadap service aplikasi yang akan dijalankan. Gambaran sederhananya seperti menyatukan semua Dockerfile dari setiap service aplikasi ke dalam sebuah file yaml (docker-compose file), dan selanjutnya dengan sebuah command, kita bisa meng-create dan men-start semua service yang telah didefinisikan pada file yml tersebut. script konfigurasi nya juga sangat mudah dan mirip dengan argumen-argumen saat kita ingin menjalankan sebuah Dockerfile. Kita bisa menggunakannya di semua lingkungan kerja : production, staging, development, dan testing.
- Proses Dasar Penggunaan Docker-Compose yaitu :
  - Mendefinisikan environment aplikasi dengan membuat Dockerfile sehingga bisa digunakan kembali dimana saja.
  - Mendefinisikan service lainnya (termasuk aplikasi kita) di dalam docker-compose.yml sehingga semuanya bisa berjalan bersamaan dalam environment yang terisolasi.
  - Jalankan command docker compose yaitu : docker-compose build dan docker-compose up melalui command prompt/shell (pastikan anda berada pada path yang sama dengan posisi file docker-compose.yml).
